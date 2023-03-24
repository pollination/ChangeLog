# ChangeLog
A public repo for saving user-friendly change logs of each release of each platform.
These change logs can be used in the user manu.


# Reference example
https://installbuilder.com/changelog

## Version 23.1.0 2023-01-13
- Rebrand to Backstaff
- Updated internal dependencies
- Updated documentation
- Fixed macOS signatures not being properly created when using binary launchers and supporting osx-arm64

## Version 22.10.0 2022-10-26
- Support using HTML values in <infoParameter> for all graphical modes
- Added new <enableGlobMatching> setting to <deleteFile> action to allow deleting special filenames
- Improved generation of unique identifiers
- Improved DLL loading on Qt installers

## Version 22.8.0 2022-08-09
- Added Swiss and Austrian languages
- Updated internal dependencies
- Fixed some HTML licenses making installers crash on Windows x64 when running in win32 mode
- Fixed malformed osx-arm64 signatures when using built-in signing