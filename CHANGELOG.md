# Changelog
<!--
    Placeholder for the next version (at the beginning of the line):
    ## __WORK IN PROGRESS__
-->

## 1.8.3 (2021-01-11)
* Changelog entries like `* (Author 1, Author 2) Whazaaaap!` are now correctly handled when creating the `io-package.json` news entries.

## 1.8.2 (2021-01-05)
* Updated dependencies

## 1.8.1 (2020-09-15)
* Add `--no-verify` to `git commit` command when using lerna. Otherwise, cleaning up becomes a royal PITA.

## 1.8.0 (2020-09-01) · 2020 Doomsday release :)
* The changelog headline may now contain free text after the placeholder

## 1.7.1 (2020-09-01)
* Fix: The git branch status is now detected using machine-readable commands instead of the (possibly localized) `git status`
* The release-script now uses itself to create new releases

## v1.7.0 (2020-08-24)
* It is now possible to configure some of the settings with a config file
* Added the `beforePush` hook to run scripts before creating and pushing the release commit

## v1.6.0 (2020-06-21)
* Added support for monorepos that are managed with [lerna](https://github.com/lerna/lerna)

## v1.5.1 (2020-06-06)
* Added support for splitting the changelog into README.md and CHANGELOG_OLD.md
