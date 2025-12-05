## [2.0.1] - December 5, 2025

* Replaced `dart:html` with `package:web` for WASM compatibility
* Updated SDK constraint to `>=3.0.0` to support `package:web`
* Fixed WASM dry run incompatibility: `dart:html unsupported` error
* This change enables Flutter WASM builds to compile successfully
* Resolves build warnings when targeting WebAssembly: "package:flutter_keyboard_visibility_web/flutter_keyboard_visibility_web.dart 1:1 - dart:html unsupported"

## [2.0.0] - March 4, 2021

* Migrated to null safety

## [2.0.0-nullsafety.0] - November 30, 2020

* Migrated to null safety

## [1.0.1] - November 23, 2020

* Documentation updates

## [1.0.0] - November 23, 2020

* Initial support so Flutter apps that run on web won't encounter errors. Visibility is returned as false.