# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [5.0.1](https://github.com/capawesome-team/sponsorware/compare/v5.0.0...v5.0.1) (2023-06-03)


### Bug Fixes

* **android:** `format()` method failed on some tags ([#13](https://github.com/capawesome-team/sponsorware/issues/13)) ([43f7290](https://github.com/capawesome-team/sponsorware/commit/43f7290d2bf4846aa7b037566a1f83e32383d269))

## [5.0.0](https://github.com/capawesome-team/sponsorware/compare/v0.3.2...v5.0.0) (2023-05-04)


### ⚠ BREAKING CHANGES

* This plugin now only supports Capacitor 5.

### Features

* update to Capacitor 5 ([#11](https://github.com/capawesome-team/sponsorware/issues/11)) ([4221923](https://github.com/capawesome-team/sponsorware/commit/4221923be3a40016b5dec50a1a5ede919cf227b7))


### Bug Fixes

* **android:** `Cannot invoke method toList() on null object` ([00f9e96](https://github.com/capawesome-team/sponsorware/commit/00f9e960cb9559a87d999e2b2169c066c1a102f2))

### [0.3.2](https://github.com/capawesome-team/sponsorware/compare/v0.3.1...v0.3.2) (2023-05-01)


### Bug Fixes

* **android:** `Attempt to get length of null array` ([#12](https://github.com/capawesome-team/sponsorware/issues/12)) ([f271da6](https://github.com/capawesome-team/sponsorware/commit/f271da68533fccbd15c66beb9026af9d97b250a9))

### [0.3.1](https://github.com/capawesome-team/sponsorware/compare/v0.3.0...v0.3.1) (2023-02-06)


### Features

* **utils:** add methods `convertBytesToHex` and `convertHexToBytes` ([#9](https://github.com/capawesome-team/sponsorware/issues/9)) ([1969c8b](https://github.com/capawesome-team/sponsorware/commit/1969c8bf8eaf252369b6e9a1e286ba15d907f850))


### Bug Fixes

* **ios:** restart polling after reading a tag ([#8](https://github.com/capawesome-team/sponsorware/issues/8)) ([50ff554](https://github.com/capawesome-team/sponsorware/commit/50ff554097c109f95e44b6742c84dd1164f817c3))
* **utils:** add missing `UriIdentifierCode` option ([#10](https://github.com/capawesome-team/sponsorware/issues/10)) ([b82600e](https://github.com/capawesome-team/sponsorware/commit/b82600e46ef6eaff9cf2b87668f4462e3db407ca))

## [0.3.0](https://github.com/capawesome-team/sponsorware/compare/v0.2.0...v0.3.0) (2022-11-11)


### ⚠ BREAKING CHANGES

* **android:** Error messages on Android are now no longer localized.

### Features

* add `erase` and `format` methods ([#6](https://github.com/capawesome-team/sponsorware/issues/6)) ([8c7c8a5](https://github.com/capawesome-team/sponsorware/commit/8c7c8a5c03697f605278c6849b224e6d3a887bd5))
* **android:** return non-localized error messages ([#7](https://github.com/capawesome-team/sponsorware/issues/7)) ([0d16442](https://github.com/capawesome-team/sponsorware/commit/0d164427026bef5394d21a5409788ea268347891))
* support NFC raw commands ([#5](https://github.com/capawesome-team/sponsorware/issues/5)) ([a00bfd9](https://github.com/capawesome-team/sponsorware/commit/a00bfd97a165ddc077fe59c9e3040027c12aa562))


### Bug Fixes

* **android:** add missing `makeReadOnly` implementation ([#4](https://github.com/capawesome-team/sponsorware/issues/4)) ([326d4a5](https://github.com/capawesome-team/sponsorware/commit/326d4a5505346a6b369e28c4ae07a62d937b6814))

## [0.2.0](https://github.com/capawesome-team/capacitor-nfc-sponsorware/compare/v0.1.1...v0.2.0) (2022-10-03)

### ⚠ BREAKING CHANGES

* FeliCa tags are no longer detected by default on iOS. The polling option must be configured using `pollingOptions`. (#3)

### Features

* **ios:** add `pollingOptions` option ([#3](https://github.com/capawesome-team/capacitor-nfc-sponsorware/issues/3)) ([8d809e8](https://github.com/capawesome-team/capacitor-nfc-sponsorware/commit/8d809e838f679b2a7ce873854218f05de951f49a))

### [0.1.1](https://github.com/capawesome-team/capacitor-nfc-sponsorware/compare/v0.1.0...v0.1.1) (2022-09-07)


### Bug Fixes

* **android:** catch all native errors ([1244330](https://github.com/capawesome-team/capacitor-nfc-sponsorware/commit/124433014bf882c11376e3886c781d59a6f6fb63))

## [0.1.0](https://github.com/capawesome-team/capacitor-nfc-sponsorware/compare/v0.0.1...v0.1.0) (2022-08-20)


### ⚠ BREAKING CHANGES

* update to Capacitor 4 (#1)

### Features

* update to Capacitor 4 ([#1](https://github.com/capawesome-team/capacitor-nfc-sponsorware/issues/1)) ([da113e5](https://github.com/capawesome-team/capacitor-nfc-sponsorware/commit/da113e5307a57f745deb19bc2eaf088a8e6a0372))

## 0.0.1 (2022-08-12)

Initial release 🎉
