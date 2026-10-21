# ThreadShelf Local Suite manual

Read the illustrated user manual at **https://davoda1.github.io/ThreadShelf-Local-Suite-Manual/**.

This repository hosts the generated documentation for ThreadShelf Local Reader 1.0.0,
Local Analytics 1.0.0, Local Alternative 1.0.0 and the search integration patch for
ThreadShelf 1.3.0. It includes installation, settings, workflows, troubleshooting,
and screenshots made with synthetic data.

Application sources, editable manual content and desktop releases are maintained in
[Davoda1/ThreadShelf-Local-Suite](https://github.com/Davoda1/ThreadShelf-Local-Suite).
That repository can remain private while this manual is public; source and download
links become available to everyone when the main repository is made public.

## Website updates

Build the manual from the main repository with `python3 manual/build.py`.
Synchronize the generated **contents** of `docs/` into this repository's root,
including `.nojekyll`. Remove obsolete generated files while retaining this README
and all required license/notices files. Review the diff before committing.
GitHub Pages publishes from `master` and `/(root)` with HTTPS enforced.

This website contains static documentation and required notices. It does not contain
desktop application sources, binaries, personal configuration or real conversation
archives. It also works offline: download the site and open `index.html`.

## Licenses

Original suite documentation: Copyright (c) 2026 davoda1, [MIT](LICENSE).
Gopher HTTP 3.0.0 website engine: [MIT](GOPHER-LICENSE.txt).
See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for attribution and scope.
