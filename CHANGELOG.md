# Changelog

## 08/10/2018 - Version 0.3.10

Release changes:

* Optimised Prod construction ([#261](https://github.com/frees-io/iota/pull/261))
* Scalaz IsoSet macros ([#262](https://github.com/frees-io/iota/pull/262))


## 08/06/2018 - Version 0.3.9

Release changes:

* update dependencies ([#248](https://github.com/frees-io/iota/pull/248))
* Cut release with updated deps ([#249](https://github.com/frees-io/iota/pull/249))


## 06/05/2018 - Version 0.3.8

Release changes:

* Implement hashcode for all data types ([#219](https://github.com/frees-io/iota/pull/219))
* Releases iota 0.3.8 ([#221](https://github.com/frees-io/iota/pull/221))


## 05/14/2018 - Version 0.3.7

Release changes:

* Filter out some deps from the updates report ([#186](https://github.com/frees-io/iota/pull/186))
* Add full path for scala.Int type to macros ([#188](https://github.com/frees-io/iota/pull/188))
* Add fully quialified names to avoid problems with -Xno-import ([#189](https://github.com/frees-io/iota/pull/189))
* Fixed bug in NT macro ([#190](https://github.com/frees-io/iota/pull/190))
* Cut 0.3.7 release ([#191](https://github.com/frees-io/iota/pull/191))


## 02/20/2018 - Version 0.3.6

Release changes:

* Makes coproducts serializable (fixes #151) ([#152](https://github.com/frees-io/iota/pull/152))
* Release 0.3.6 ([#153](https://github.com/frees-io/iota/pull/153))


## 02/12/2018 - Version 0.3.5

Release changes:

* Add first item evidence for CopK ([#110](https://github.com/frees-io/iota/pull/110))
* Use blackbox macros when possible ([#111](https://github.com/frees-io/iota/pull/111))
* Add TListH ([#112](https://github.com/frees-io/iota/pull/112))
* First pass of scalacheck module for summoning scalacheck evidence ([#113](https://github.com/frees-io/iota/pull/113))
* Add support for coproducts of H functors ([#66](https://github.com/frees-io/iota/pull/66))
* Fix bounds for CopK.Inject ([#114](https://github.com/frees-io/iota/pull/114))
* Release 0.3.5 ([#115](https://github.com/frees-io/iota/pull/115))
* Improves CI Pipeline ([#119](https://github.com/frees-io/iota/pull/119))


## 01/03/2018 - Version 0.3.4

Release changes:

* Fixes CHANGELOG.md and README.md ([#101](https://github.com/frees-io/iota/pull/101))
* Bump to cats 1.0.1 ([#106](https://github.com/frees-io/iota/pull/106))
* Release 0.3.4 with support for Cats 1.0.1 ([#107](https://github.com/frees-io/iota/pull/107))
* Upgrade iota Build ([#109](https://github.com/frees-io/iota/pull/109))


## 11/22/2017 - Version 0.3.3

Release changes:

* Add Scalaz examples ([#90](https://github.com/frees-io/iota/pull/90))
* Add 100 algebra entry bench plot data ([#92](https://github.com/frees-io/iota/pull/92))
* Stop file validations in build ([#93](https://github.com/frees-io/iota/pull/93))
* Add inject/injectK syntax ([#81](https://github.com/frees-io/iota/pull/81))
* Split README / Fix Scalaz ([#94](https://github.com/frees-io/iota/pull/94))
* Release 0.3.3 ([#96](https://github.com/frees-io/iota/pull/96))
* Move scalac options to a "plugin" ([#97](https://github.com/frees-io/iota/pull/97))
* Upgrades sbt-freestyle plugin ([#100](https://github.com/frees-io/iota/pull/100))


## 09/29/2017 - Version 0.3.1

Release changes:

* Support Scalaz ([#73](https://github.com/frees-io/iota/pull/73))
* Fix module names: iota-corez to iotaz-core ([#75](https://github.com/frees-io/iota/pull/75))
* Cleanup readme ([#74](https://github.com/frees-io/iota/pull/74))
* Cut release of version 0.3.1 ([#77](https://github.com/frees-io/iota/pull/77))


## 09/27/2017 - Version 0.3.0

Release changes:

* Update ProjectPlugin.scala ([#40](https://github.com/frees-io/iota/pull/40))
* Take ScalaJS back in time so that the badge shows up ([#42](https://github.com/frees-io/iota/pull/42))
* Show raw type trees for parser errors ([#47](https://github.com/frees-io/iota/pull/47))
* Ensure type refinements are carried through computations ([#46](https://github.com/frees-io/iota/pull/46))
* Fix polytype bug ([#48](https://github.com/frees-io/iota/pull/48))
* Migrates iota to frees-io organization ([#50](https://github.com/frees-io/iota/pull/50))
* Add Remove operation ([#45](https://github.com/frees-io/iota/pull/45))
* Adjust toolbelt organization/documentation ([#52](https://github.com/frees-io/iota/pull/52))
* Rename KList to TListK ([#54](https://github.com/frees-io/iota/pull/54))
* fix typo in README.md ([#55](https://github.com/frees-io/iota/pull/55))
* Fix typo in the source for the README.me file ([#56](https://github.com/frees-io/iota/pull/56))
* Add a CODEOWNERS file ([#57](https://github.com/frees-io/iota/pull/57))
* Bump cats to 1.0.0-MF; adjust Injects ([#58](https://github.com/frees-io/iota/pull/58))
* adds comm support statement ([#59](https://github.com/frees-io/iota/pull/59))
* Ensure Idents are qualified/attributed when creating FastFunctionKs ([#60](https://github.com/frees-io/iota/pull/60))
* Use NEL.one instead of NEL.of ([#61](https://github.com/frees-io/iota/pull/61))
* Add error handling free algebra example ([#62](https://github.com/frees-io/iota/pull/62))
* Use TL Scala for tests only ([#63](https://github.com/frees-io/iota/pull/63))
* Fix the links to tests in README.md ([#65](https://github.com/frees-io/iota/pull/65))
* Upgrade to sbt 1.0.x ([#68](https://github.com/frees-io/iota/pull/68))
* Release 0.3.0 ([#69](https://github.com/frees-io/iota/pull/69))
* [WIP] Support Scalaz ([#70](https://github.com/frees-io/iota/pull/70))
* Skip publishing for Scalaz until it is ready ([#72](https://github.com/frees-io/iota/pull/72))
* Remove Typelevel Scala from test code ([#71](https://github.com/frees-io/iota/pull/71))


## 06/01/2017 - Version 0.2.0

Release changes:

* Add operations to type lists ([#31](https://github.com/47deg/iota/pull/31))
* Generalize creation of FastFunctionK as a toolbelt API ([#30](https://github.com/47deg/iota/pull/30))
* Fix ShowTrees flag ([#32](https://github.com/47deg/iota/pull/32))
* Use recursion schemes in toolbelt ([#33](https://github.com/47deg/iota/pull/33))
* Reorganize toolbelt code & other misc cleanup ([#34](https://github.com/47deg/iota/pull/34))
* Add Product type for TList ([#35](https://github.com/47deg/iota/pull/35))
* Refactor recursion to support Cofree ([#36](https://github.com/47deg/iota/pull/36))
* Release 0.2.0 ([#39](https://github.com/47deg/iota/pull/39))


## 05/11/2017 - Version 0.1.0

Release changes:

* Adds Freestyle to the Iota's in the wild section ([#22](https://github.com/47deg/iota/pull/22))
* Misc cleanup ([#20](https://github.com/47deg/iota/pull/20))
* Fixes typo in README ([#25](https://github.com/47deg/iota/pull/25))
* Clean up macros; Support reflection ([#24](https://github.com/47deg/iota/pull/24))
* Add syntax comparison to README ([#27](https://github.com/47deg/iota/pull/27))
* Bump to & release v0.1.0 ([#28](https://github.com/47deg/iota/pull/28))


## 04/30/2017 - Version 0.0.2

Release changes:

* Upgrades sbt-org-policies version to fix the badges ([#15](https://github.com/47deg/iota/pull/15))
* Search KList/TList by type eqv instead eq ([#17](https://github.com/47deg/iota/pull/17))
* Bump to 0.0.2 ([#18](https://github.com/47deg/iota/pull/18))


## 04/27/2017 - Version 0.0.1

Release changes:

* Add missing build infrastructure ([#1](https://github.com/47deg/iota/pull/1))
* Clean up macros & add prelim benchmark code ([#2](https://github.com/47deg/iota/pull/2))
* Update travis paths from andyscott to 47deg; Fix project name in README ([#4](https://github.com/47deg/iota/pull/4))
* Demo injection in README ([#5](https://github.com/47deg/iota/pull/5))
* Cross compile to ScalaJS ([#7](https://github.com/47deg/iota/pull/7))
* Add macro debugging options ([#8](https://github.com/47deg/iota/pull/8))
* Fully qualify paths to types in generated code ([#10](https://github.com/47deg/iota/pull/10))
* Add myself as a maintainer ([#11](https://github.com/47deg/iota/pull/11))
* Linkify twitter ([#12](https://github.com/47deg/iota/pull/12))
* Integrates sbt-org-policies sbt Plugin ([#9](https://github.com/47deg/iota/pull/9))
* Code generate proper benchmarks ([#13](https://github.com/47deg/iota/pull/13))
* pre-release: 0.0.1 ([#14](https://github.com/47deg/iota/pull/14))