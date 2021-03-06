# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

----

## [2.0.0] => 2020-SEP-

### Added

* Github autopublishing of changelogs
* New CI procedures based on new ColdBox modules
* More formatting goodness and watchers

### Removed

### Fixed

----

## [1.5.0]

* `Improvement` : Updated to new template style
* `Improvement` : ColdBox 5 updates
* `Improvement` : Moved i18n listener to afterAspectsLoad to avoid module loading collisions
* `Bug` : Invalid `instance` scope usage in models

----

## [1.4.0]

* Few docuementation fixes
* Fix implementation of `getTZoffset()` thanks to Seb Duggan
* CCM-47 Case sensitivity resolved for resource service thanks to @wpdebruin
* Updated TestBox version

----

## [1.3.2]

* Unified workbench
* Encapsulation of module bundle resources

----

## [1.3.1]

* Varscoping fixes
* Travis updates

----

## [1.3.0]

* Implements the ability to add a custom Resource Service for distributed i18n
* Fixes issues with non-ISO characters in properties files

----

## [1.2.0]

* New configuration setting for logging when no translation is found `logUnknownTranslation`
* Adding Travis CI support

----

## [1.1.0]

* Updated build process
* Updated docs and instructions

----

## [1.0.2]

* Fixes on `getRBKeys()` and `getRBString()` to load correct file paths.

----

## [1.0.1]

* production ignore lists
* Unloading of helpers

----

## [1.0.0]

* Create first module version