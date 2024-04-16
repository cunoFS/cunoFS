# cunoFS Changelog

## v1.2.2

- Fix for long running AWS IAM credentials expiry
- Fix corner-case internal lock conditions in cuno mount
- Miscellaneous fixes and performance improvements

## v1.2.1

- Fix for handling AWS IAM credential renewals on long sessions
- Improved `freopen` compatibility
- FUSE mounts have `auto_cache` enabled by default
- Miscellaneous fixes and performance improvements

## v1.2.0

- ML acceleration integration (with separate `Python` package)
- Fixes for some `mmap` conditions in direct mode
- Miscellaneous fixes and performance improvements
- Trial sign-up is optional/interactive during installation

## v1.1.10

- Static binary interception - performance improvements
- Better support for multi-process directory listings

## v1.1.9

- Added "cuno fusion" command for easier pairing of local and cloud storage
- Added new automated trial license scheme
- Fixed support for some static binaries
- Fixed cuno creds manager to work better on MacOS

## v1.1.8

- Fusion-mode - added support for flock and posix_lock
- Fixes for corner-case of rmdir and rename dir after mkdir
- Fixes for static binary interception in posix_spawn, and syscall filtering
- Miscellaneous fixes for Fusion mode
- Added URI compatibility by default for ffprobe/ffplay

## v1.1.7

- Some performance improvements for media workloads
- Add support for custom mount locations in flexmount mode
- Add mmap write support on objects
- Fusion mode improvements and fixes
- Miscellaneous fixes
- Added Musl build

## v1.1.6

- Fix for slow S3 providers
- cunoFS Fusion Beta release

## v1.1.5

- Added the `cuno-mac` script for launching cunoFS-enabled containers on macOS

## v1.1.4

- Initial cunoFS public release.
