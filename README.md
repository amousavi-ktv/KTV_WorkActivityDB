# KTV_WorkActivityDB

Public **GitHub Pages publish target** for the WorkActivities database object
dependency explorer. (The local working folder is `KTV_WorkActivityDB_GitHub` to
distinguish it on disk from a database export; the repo itself is `KTV_WorkActivityDB`.)

- **Live page:** https://amousavi-ktv.github.io/KTV_WorkActivityDB/
- `index.html` — the self-contained interactive tree (tables / views / stored procedures + foreign-key links) for `WorkActivities_DEV_CLAUDE`.

This repo contains **only structural metadata** (object and column names, dependency
edges) — no application code, no data, no credentials. It is generated from the live
database and updated by the refresh script in the private application repo. Do not
edit `index.html` here by hand; it is overwritten on each refresh.
