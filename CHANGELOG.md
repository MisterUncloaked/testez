# TestEZ Changelog

## Unreleased Changes

## 0.2.0 (2020-03-04)
* Added support for init.spec.lua. Code in this file is treated as belonging to the directory's node in the test tree. This allows for lifecycle hooks to be attached to all files in a directory.
* Added TestEZ CLI, a Rust tool that bundles TestEZ and Lemur, and can run tests via Lemur or Roblox-CLI ([#61](https://github.com/Roblox/testez/pull/61))

## 0.1.1 (2020-01-23)
* Added beforeAll, beforeEach, afterEach, afterAll lifecycle hooks for testing
	* The setup and teardown behavior of these hooks attempt to reach feature parity with [jest](https://jestjs.io/docs/en/setup-teardown).


## 0.1.0 (2019-11-01)
* Initial release.
