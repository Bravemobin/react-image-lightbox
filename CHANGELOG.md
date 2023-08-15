# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [6.0.1](https://github.com/Bravemobin/react-image-lightbox/compare/v6.0.0...v6.0.1) (2023-08-15)

## 6.0.0 (2023-08-15)


### ⚠ BREAKING CHANGES

* you must you must import the css for the component yourself,
using `import 'react-image-lightbox/style.css';`. You only need to do this
once in your application.
* Versions of IE earlier than IE 11 are no longer supported.

### Features

* Add react@16 support ([e3e63b6](https://github.com/Bravemobin/react-image-lightbox/commit/e3e63b69a66590a83d913d69ea9c05f921023c1a))
* allow for override of react-modal props ([45a756d](https://github.com/Bravemobin/react-image-lightbox/commit/45a756d69a459a59281d4e2f90fe429402abf26a))
* Custom error message prop for when images fail to load ([419998d](https://github.com/Bravemobin/react-image-lightbox/commit/419998d94d449c305a4482d576753503f8da0b63)), closes [#82](https://github.com/Bravemobin/react-image-lightbox/issues/82)
* migrated away from style-loader ([e74b7c9](https://github.com/Bravemobin/react-image-lightbox/commit/e74b7c99eb4642a42631d2372b46645f044b8414))
* onImageLoad API ([b08be00](https://github.com/Bravemobin/react-image-lightbox/commit/b08be0081f2c4b99f4003105a2d1f3cfb4d0ce80))
* typescript declarations files ([#116](https://github.com/Bravemobin/react-image-lightbox/issues/116)) ([357a801](https://github.com/Bravemobin/react-image-lightbox/commit/357a801f1f799325708e36b281d332bdc73ed4b4))


### Bug Fixes

* Allow older versions of react ([a2dbf63](https://github.com/Bravemobin/react-image-lightbox/commit/a2dbf633873f72ccdeae9b57770e278a1a6167ed))
* allow React.ReactNode as imageTitle and imageCaption in TypeScript projects ([#158](https://github.com/Bravemobin/react-image-lightbox/issues/158)) ([f1858a3](https://github.com/Bravemobin/react-image-lightbox/commit/f1858a3efe25b66b850565b308688669bd7bab66))
* avoid cross-origin errors from using window.top ([5bb5ac9](https://github.com/Bravemobin/react-image-lightbox/commit/5bb5ac9cc06c7cb5a7447c74060c3e9c3f44fb07))
* change focus when zoom buttons becomes disabled to be able to still use arrow keys (fix issue [#132](https://github.com/Bravemobin/react-image-lightbox/issues/132)) ([#135](https://github.com/Bravemobin/react-image-lightbox/issues/135)) ([30ba946](https://github.com/Bravemobin/react-image-lightbox/commit/30ba9466e3b18cacf9f1647c7a3b33ae54348b2c))
* Change wording of aria-label s ([f57bedb](https://github.com/Bravemobin/react-image-lightbox/commit/f57bedb002ca29f8641de29cf1a08536880154ae))
* Default to null height instead of 0 ([faa996c](https://github.com/Bravemobin/react-image-lightbox/commit/faa996c1e767faa67b56118ead25ff1059bcd83f)), closes [#66](https://github.com/Bravemobin/react-image-lightbox/issues/66)
* demo parcel site on github pages ([822140e](https://github.com/Bravemobin/react-image-lightbox/commit/822140ed665f55f664c1a5ea851f6b3aeaed31db))
* don't prevent default inside a passive listener ([b2b6a79](https://github.com/Bravemobin/react-image-lightbox/commit/b2b6a798671de7027635123baec8584e3fefaaf2))
* fix cross origin iframe detection ([6683a29](https://github.com/Bravemobin/react-image-lightbox/commit/6683a29639f0df2609849d9c71f7da0fa08a4882))
* fix getOrigin issue within iFrames ([#175](https://github.com/Bravemobin/react-image-lightbox/issues/175)) ([f290cb3](https://github.com/Bravemobin/react-image-lightbox/commit/f290cb344ac89f6359b39c0fd4ab8fe00bb36205)), closes [#136](https://github.com/Bravemobin/react-image-lightbox/issues/136)
* fix lint ([c2acf2c](https://github.com/Bravemobin/react-image-lightbox/commit/c2acf2ccd86610ad89f3af497e4eefc911da68ac))
* handle environment with no navigator. Fixes [#97](https://github.com/Bravemobin/react-image-lightbox/issues/97) ([7f36b72](https://github.com/Bravemobin/react-image-lightbox/commit/7f36b72b3ab82b3fca3de2b6d000c89a2d81d8aa))
* Hide orange outline around viewer in Chrome on Android ([359e9bd](https://github.com/Bravemobin/react-image-lightbox/commit/359e9bdc359a306a6be326f02632770ab6d3cf56))
* Improve rendering on zoom in Safari ([bab9ca1](https://github.com/Bravemobin/react-image-lightbox/commit/bab9ca146da0d9988352dd9d24b6393c911be073)), closes [#70](https://github.com/Bravemobin/react-image-lightbox/issues/70)
* silence react-modal warning by setting appElement ([a26d597](https://github.com/Bravemobin/react-image-lightbox/commit/a26d5978b623019ff87920aeaf82f5af9c0a59bf))

### [5.1.6](https://github.com/Bravemobin/react-image-lightbox/compare/v5.1.5...v5.1.6) (2023-07-09)

### [5.1.5](https://github.com/Bravemobin/react-image-lightbox/compare/v5.1.4...v5.1.5) (2023-07-09)
