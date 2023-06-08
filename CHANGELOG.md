## [0.2.2] - add topics

- add topics to pubspec.yaml

## [0.2.1] - Fix dependencies

- move checks to dev dependencies

## [0.2.0] - Dart 3

- upgrade Dart 3
- use HardwareKeyboard API instead of RawKeyboard API

## [0.1.3] - Fixed Windows support

- Fix for empty scan on Windows
- Added Windows example
- Updated example to latest Flutter release

## [0.1.2] - Added useKeyDown parameter

- Implemented `useKeyDown` parameter to enable using `RawKeyDownEvent` instead of `RawKeyUpEvent`

## [0.1.1+2] - Changed MacOS implementation from keyLabel to characters

- MacOS implementation now listens to `characters` instead of `keylabel`

## [0.1.1+1] - characterCodePoint instead of keyLabel for Windows

- Windows implementation now handles characterCodePoint instead of keyLabel

## [0.1.1] - Web and Desktop support

- Implemented support for web, MacOs, Linux and Windows

## [0.1.0] - Null safety

- Migrated to null safety

## [0.0.3] - Updated example

- Updated widget name

## [0.0.2] - Refactored character buffering

- Moved to internal buffering instead of stream buffering for improved performance.

## [0.0.1] - Initial release

- First working version
