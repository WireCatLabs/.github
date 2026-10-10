# WireCat GitHub defaults

Shared community policies for WireCat repositories that do not define local
policies. The source of truth is [WireCatLabs/community](https://github.com/WireCatLabs/community).

Edit the policies there, then run `python3 scripts/sync-defaults.py --apply` from
that repository. Use `--check` to detect drift. This repository must remain public
and named `.github` for GitHub to inherit its community files.

These defaults do not change any project's license. Each project must ship its
own LICENSE and required third-party notices. Original material here uses
[Apache-2.0](LICENSE).
