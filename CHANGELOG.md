# Changelog

## Contao branch (November 21, 2020)

Optimized for use in [Contao CMS](https://contao.org)

- dropped Panini
- dropped Style Sherpa
- dropped UNCSS
- changed build destination directory
- use external jQuery provided by Contao, instead of including it in the build (build footprint optimization)
- browser-sync proxies local Contao installation
- changed browser-sync port
- added `--mode=css` option for npm tasks (development speed optimization)
- watch for `*.html5` changes in `/templates` folder in addition to css and js
