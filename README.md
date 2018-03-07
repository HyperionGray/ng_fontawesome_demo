This repo contains a demo application for
[ng_fontawesome](https://github.com/HyperionGray/ng_fontawesome).

View [the
demo](https://hyperiongray.github.io/ng_fontawesome_demo/) on GitHub Pages.

If you want to run this demo locally, clone the repo and run `pub serve` from
this directory.

To update the build, run `pub build` from this directory, then
`git rm -fr docs && mv build/web/ docs/ && git add docs`. You can test the build
by running a web server from the `docs/` directory, e.g.
`cd docs && python3 -m http.server`.
