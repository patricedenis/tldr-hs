# 0.9.1

* When the [`NO_COLOR`](https://no-color.org/) environment variable is set, the client will not color the output.
* Added `--[no-]color` options which enable/disable output coloring (overrides `NO_COLOR`).

# 0.9.0

* When pages are updated, the client now shows the download location.
* Add optional auto-update functionality (`--auto-update-interval`)

# 0.8.0

* Split the library into more parts.
* Fix [multiple line bugs](https://github.com/psibi/tldr-hs/issues/26 "multiple line bugs")

# 0.7.1

* Client gives non zero exit status for non-existent pages.

# 0.7.0

* Make it obey --language (-L) option.

# 0.6.4

* Fix cabal file

# 0.6.3

* Drop `-optl-static` for linux builds

# 0.6.2

* package.yaml support for configuring package
* CI releases binary now

# 0.6.1

* Implement --about option

# 0.6.0

* Make it obey --platform option
* Add -u as an alias for --update
* Make parsing more robust

# 0.5.1

* Proper options handling

# 0.5.0

* Obey XdgData for storing the files.
* Also search pages from sunos directory now.
* Support subcommands ie. tldr git submodule will now work.

# 0.4.0.2

* Fix double initialization bug. Credits to @Kove-W-O-Salter

# 0.4.0

* Add proper coloring back
* Update gitignore rule
* Update travis and appveyor configuration

# 0.3.1

* Add golden testing using tasty
* Fix grep render [#11](https://github.com/psibi/tldr-hs/issues/11)
* Fixes [#2](https://github.com/psibi/tldr-hs/issues/2)

# 0.3.0

* Add default completion support from optparse-applicative
* Add windows support. Credits to @ShrykeWindgrace.

# 0.2.5

* Fix eager cloning

# 0.2.4

* Don't do cloning unnecessarily [#7](https://github.com/psibi/tldr-hs/issues/7)
* Fix Paths_tldr warning from cabal

# 0.2.3

* Fix coloring bug under bash during some circumstances [#6](https://github.com/psibi/tldr-hs/pull/6/files)

# 0.2.2

* Fix `--version` option

# 0.2.1

* Fix background color [bug](https://github.com/psibi/tldr-hs/pull/3)

# 0.2.0

* Compliance with the tldr spec
* Fix `--update` flag bug
* Backported till GHC 7.8.3 and lts-2.22
