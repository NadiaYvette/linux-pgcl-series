# linux-pgcl-series

Page-clustering (PGCL / "larpage" forward-port) for Linux, as a patch series.

- `patches/` — `git format-patch v7.1..nadia.chambers/pgcl-mmupage-mapcount` (174 patches, base **v7.1**, tip **0aceb3e9864a**).
- `COVER-LETTER.md` — project narrative (describes the curated linux-mm RFC; `patches/` here is the full dev series).

## Apply
```
git clone --branch v7.1 git://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git
cd linux && git am /path/to/linux-pgcl-series/patches/*.patch
```
Commits are GPG-signed with key E64334A1D1792658D410DF23E1FD01992205E28F.
Exact-history form: see the companion **pgcl-kernel-bundle** repo.
