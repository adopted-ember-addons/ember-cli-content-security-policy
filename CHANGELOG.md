# Changelog






## v2.0.3 (2022-01-02)

#### :bug: Bug Fix
* [#277](https://github.com/rwjblue/ember-cli-content-security-policy/pull/277) Fixing tiny typo in deprecation-warning ([@GabrielCousin](https://github.com/GabrielCousin))

#### Committers: 1
- Gabriel Cousin ([@GabrielCousin](https://github.com/GabrielCousin))

## v2.0.2 (2021-12-20)

#### :bug: Bug Fix
* [#271](https://github.com/rwjblue/ember-cli-content-security-policy/pull/271) Fastboot instance initializer throws if reportOnly config is false ([@JoeyBG](https://github.com/JoeyBG))

#### Committers: 1
- Joey Bolduc-Gilbert ([@JoeyBG](https://github.com/JoeyBG))

## v2.0.1 (2021-12-13)

#### :bug: Bug Fix
* [#274](https://github.com/rwjblue/ember-cli-content-security-policy/pull/274) fix: pass environment into readConfig ([@guidojw](https://github.com/guidojw))

#### :house: Internal
* [#272](https://github.com/rwjblue/ember-cli-content-security-policy/pull/272) use a recent fastboot version in tests ([@jelhan](https://github.com/jelhan))

#### Committers: 2
- Guido de Jong ([@guidojw](https://github.com/guidojw))
- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))

## v2.0.0 (2021-11-12)

v2.0.0 is the same as last pre-release (v2.0.0-5). It does not include any additional changes.


## v2.0.0-5 (2021-10-28)

#### :boom: Breaking Change
* [#243](https://github.com/rwjblue/ember-cli-content-security-policy/pull/243) drop support for node 10 ([@jelhan](https://github.com/jelhan))

#### :bug: Bug Fix
* [#249](https://github.com/rwjblue/ember-cli-content-security-policy/pull/249) use environment from appConfig instead of deriving it ourselves ([@jelhan](https://github.com/jelhan))

#### :memo: Documentation
* [#246](https://github.com/rwjblue/ember-cli-content-security-policy/pull/246) document Embroider compatiblity ([@jelhan](https://github.com/jelhan))

#### :house: Internal
* [#198](https://github.com/rwjblue/ember-cli-content-security-policy/pull/198) Update Ember CLI blueprints to 3.26.0 ([@snewcomer](https://github.com/snewcomer))
* [#202](https://github.com/rwjblue/ember-cli-content-security-policy/pull/202) Run scenarios with expected Ember CLI version ([@jelhan](https://github.com/jelhan))

#### Committers: 3
- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v2.0.0-4 (2021-05-06)

#### :bug: Bug Fix
* [#201](https://github.com/rwjblue/ember-cli-content-security-policy/pull/201) Support Ember CLI >= 3.26.0 and match injected script element by all supported Ember CLI versions with same RegExp ([@snewcomer](https://github.com/snewcomer))

#### Committers: 1
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))


## v2.0.0-3 (2021-04-16)

#### :bug: Bug Fix
* [#197](https://github.com/rwjblue/ember-cli-content-security-policy/pull/197) Support Ember CLI >= 3.25.1 ([@snewcomer](https://github.com/snewcomer))

#### :memo: Documentation
* [#195](https://github.com/rwjblue/ember-cli-content-security-policy/pull/195) Fix typo `form-ancestors` -> `frame-ancestors` in readme ([@nicomihalich](https://github.com/nicomihalich))
* [#188](https://github.com/rwjblue/ember-cli-content-security-policy/pull/188) remove duplicated entry in config interface documentation ([@jelhan](https://github.com/jelhan))

#### Committers: 4
- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))
- Nico Mihalich ([@nicomihalich](https://github.com/nicomihalich))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)


## v2.0.0-2 (2021-01-09)

#### :bug: Bug Fix
* [#172](https://github.com/rwjblue/ember-cli-content-security-policy/pull/172) remove report-uri from policy delivered through meta ([@jelhan](https://github.com/jelhan))
* [#152](https://github.com/rwjblue/ember-cli-content-security-policy/pull/152) append frame-src config in test mode ([@chbonser](https://github.com/chbonser))
* [#158](https://github.com/rwjblue/ember-cli-content-security-policy/pull/158) Support live reload and add optional debug log ([@jelhan](https://github.com/jelhan))
* [#156](https://github.com/rwjblue/ember-cli-content-security-policy/pull/156) Remove existing 'none' keyword when applying to source list ([@jelhan](https://github.com/jelhan))

#### :memo: Documentation
* [#160](https://github.com/rwjblue/ember-cli-content-security-policy/pull/160) doc: updated default mixpanel config ([@MichalBryxi](https://github.com/MichalBryxi))

#### :house: Internal
* [#170](https://github.com/rwjblue/ember-cli-content-security-policy/pull/170) migrate from TravisCI to GitHub Actions ([@jelhan](https://github.com/jelhan))
* [#164](https://github.com/rwjblue/ember-cli-content-security-policy/pull/164) test that addon does not break newly generated projects ([@jelhan](https://github.com/jelhan))
* [#162](https://github.com/rwjblue/ember-cli-content-security-policy/pull/162) setup Prettier ([@zg3d](https://github.com/zg3d))
* [#161](https://github.com/rwjblue/ember-cli-content-security-policy/pull/161) run tests against untouched package ([@jelhan](https://github.com/jelhan))
* [#154](https://github.com/rwjblue/ember-cli-content-security-policy/pull/154) refactor tests to use Ember Addon Tests ([@jelhan](https://github.com/jelhan))

#### Committers: 4
- Chris Bonser ([@chbonser](https://github.com/chbonser))
- Devansh Shah ([@zg3d](https://github.com/zg3d))
- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))
- Michal Bryxí ([@MichalBryxi](https://github.com/MichalBryxi))


## v2.0.0-1 (2020-04-15)

#### :bug: Bug Fix

- [#143](https://github.com/rwjblue/ember-cli-content-security-policy/pull/143) development server should use config for test if serving /tests/ ([@jelhan](https://github.com/jelhan))

#### Committers: 1

- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))

## v2.0.0-0 (2020-04-13)

This releases cumulates the work of 1 1/2 years. Main changes are:

- It allows projects to test for CSP compliance.
- It integrates with Ember FastBoot to set CSP header in FastBoot App Server.
- It moves it's own configuration to `config/content-security-policy.js` and avoids injecting unnecessary configuration into run-time.
- It introduces tests for it's own implementation to avoid regressions and increase stability.

The existing configuration syntax in `config/environment.js` is still supported but deprecated. You are recommended to migrate your configuration to `config/content-security-policy.js` as soon as possible. The [deprecation guide](DEPRECATIONS.md) contains migration instructions.

#### :boom: Breaking Change

- [#135](https://github.com/rwjblue/ember-cli-content-security-policy/pull/135) Do not set X-Content-Security-Policy header ([@jelhan](https://github.com/jelhan))
- [#107](https://github.com/rwjblue/ember-cli-content-security-policy/pull/107) Ensure `csp-headers` command emits to standard out (to allow for piping into other programs) ([@Exelord](https://github.com/Exelord))
- [#130](https://github.com/rwjblue/ember-cli-content-security-policy/pull/130) Drop Node 8, 9, and 11 support. ([@rwjblue](https://github.com/rwjblue))
- [#87](https://github.com/rwjblue/ember-cli-content-security-policy/pull/87) Drop Ember CLI < 2.13 and Node 4 support ([@loganrosen](https://github.com/loganrosen))

#### :rocket: Enhancement

- [#91](https://github.com/rwjblue/ember-cli-content-security-policy/pull/91) Add ability to fail application / addon tests when a CSP violation is detected. ([@jelhan](https://github.com/jelhan))
- [#113](https://github.com/rwjblue/ember-cli-content-security-policy/pull/113) Set CSP header in FastBoot ([@jelhan](https://github.com/jelhan))
- [#104](https://github.com/rwjblue/ember-cli-content-security-policy/pull/104) Move config to config/content-security-policy.js ([@jelhan](https://github.com/jelhan))
  Previous Iterations:
  - [#94](https://github.com/rwjblue/ember-cli-content-security-policy/pull/94) Refactor configuration to use ember-cli-content-security-policy (instead of contentSecurityPolicy) ([@jelhan](https://github.com/jelhan))
  - [#97](https://github.com/rwjblue/ember-cli-content-security-policy/pull/97) Allow configuration to be specified in ember-cli-build.js ([@jelhan](https://github.com/jelhan))
- [#101](https://github.com/rwjblue/ember-cli-content-security-policy/pull/101) Avoid merging policies in build time configuration ([@jelhan](https://github.com/jelhan))
- [#84](https://github.com/rwjblue/ember-cli-content-security-policy/pull/84) Add option to output raw CSP (Closes [#81](https://github.com/rwjblue/ember-cli-content-security-policy/issues/81)) ([@YoranBrondsema](https://github.com/YoranBrondsema))
- [#121](https://github.com/rwjblue/ember-cli-content-security-policy/pull/121) Inject runtime config only if needed (if FastBoot dependency exists) ([@jelhan](https://github.com/jelhan))

#### :bug: Bug Fix

- [#122](https://github.com/rwjblue/ember-cli-content-security-policy/pull/122) Consistent test results regardless of environment ([@jelhan](https://github.com/jelhan))
- [#134](https://github.com/rwjblue/ember-cli-content-security-policy/pull/134) Prevent unnecessary meta + reportOnly warning ([@reidab](https://github.com/reidab))
- [#136](https://github.com/rwjblue/ember-cli-content-security-policy/pull/136) Do not override existing CSP headers in fastboot ([@jelhan](https://github.com/jelhan))
- [#129](https://github.com/rwjblue/ember-cli-content-security-policy/pull/129) Set status-code to 204 (no content) ([@sandstrom](https://github.com/sandstrom))
- [#128](https://github.com/rwjblue/ember-cli-content-security-policy/pull/128) Don't add nonce to script-src when it already contains 'unsafe-inline' ([@joukevandermaas](https://github.com/joukevandermaas))
- [#109](https://github.com/rwjblue/ember-cli-content-security-policy/pull/109) Fix support for --live-reload-host option ([@jelhan](https://github.com/jelhan))
- [#107](https://github.com/rwjblue/ember-cli-content-security-policy/pull/107) Ensure `csp-headers` command emits to standard out (to allow for piping into other programs) ([@Exelord](https://github.com/Exelord))
- [#96](https://github.com/rwjblue/ember-cli-content-security-policy/pull/96) Fix inconsistency between meta element and HTTP header regarding live reload support ([@jelhan](https://github.com/jelhan))
- [#95](https://github.com/rwjblue/ember-cli-content-security-policy/pull/95) Remove trailing whitespace from generated CSP string ([@jelhan](https://github.com/jelhan))

#### :memo: Documentation

- [#108](https://github.com/rwjblue/ember-cli-content-security-policy/pull/108) Upgrade deprecation message for legacy configuration ([@jelhan](https://github.com/jelhan))
- [#102](https://github.com/rwjblue/ember-cli-content-security-policy/pull/102) Add a deprecation guide ([@jelhan](https://github.com/jelhan))

#### :house: Internal

- [#115](https://github.com/rwjblue/ember-cli-content-security-policy/pull/115) Run tests against different Ember CLI versions in CI ([@jelhan](https://github.com/jelhan))
- [#131](https://github.com/rwjblue/ember-cli-content-security-policy/pull/131) Add automated release setup. ([@rwjblue](https://github.com/rwjblue))
- [#126](https://github.com/rwjblue/ember-cli-content-security-policy/pull/126) Upgrade dependencies ([@jelhan](https://github.com/jelhan))

#### Committers: 8

- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))
- Jouke van der Maas ([@joukevandermaas](https://github.com/joukevandermaas))
- Logan Rosen ([@loganrosen](https://github.com/loganrosen))
- Maciej Kwaśniak ([@Exelord](https://github.com/Exelord))
- Reid Beels ([@reidab](https://github.com/reidab))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Yoran Brondsema ([@YoranBrondsema](https://github.com/YoranBrondsema))
- [@sandstrom](https://github.com/sandstrom)
