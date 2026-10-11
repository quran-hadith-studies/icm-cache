# icm-cache

Projects of the ICM wizard (ebadollah.ir/icm): one directory per hadith family.
Written by the server (`icm-bot`); never edited by hand. Nothing here is overwritten or deleted.

```text
index.json, hadith_index.json      lists regenerated from projects/
projects/<pid>/project.json        seed, owner, status, step, current_run
projects/<pid>/decisions/<step>/   append-only user decisions (selection, identities, phylogeny)
projects/<pid>/runs/<run>/         stage outputs for one combination of decisions + pipeline version
```

Code: https://github.com/quran-hadith-studies/icm
