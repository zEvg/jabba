# Changelog
All notable changes to this project will be documented in this file.  
This project adheres to [Semantic Versioning](http://semver.org/).

## [0.3.2](https://github.com/shyiko/jabba/compare/0.3.1...0.3.2) - 2016-03-26

### Fixed
* Zulu OpenJDK installation.

## [0.3.1](https://github.com/shyiko/jabba/compare/0.3.0...0.3.1) - 2016-03-26

### Fixed
* `current` (previously output was written to stderr instead of stdout).

## [0.3.0](https://github.com/shyiko/jabba/compare/0.2.0...0.3.0) - 2016-03-26

### Added
* Zulu OpenJDK support (e.g. `jabba install zulu@<version>`).
* Ability to install JDK from `zip` archives (in addition to already implemented `dmg`/`tar.gz`/`bin`).
* Support for custom registries (e.g. `JABBA_INDEX=https://github.com/shyiko/jabba/raw/master/index.json jabba install ...`). 

### Fixed
* `which <alias>`.

## [0.2.0](https://github.com/shyiko/jabba/compare/0.1.0...0.2.0) - 2016-03-24

### Added 
* `alias default`/`unalias default`, `which`, `deactivate` commands. 

## 0.1.0 - 2016-03-23
