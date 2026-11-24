# ServiceDesk for Mac

Release builds and the update feeds of ServiceDesk.

## Install

Open the [latest release](https://github.com/Lumyk/servicedesk-releases/releases/latest) and download the disk image for your Mac:

- Apple Silicon (M1 and later): the file ending in `-arm64.dmg`
- Intel: the file ending in `-x86_64.dmg`

Open the image, drag ServiceDesk to Applications and launch it from there. Requires macOS 15 or later.

## Updates

The app updates itself: Settings → General → Check for Updates. `appcast-arm64.xml` and `appcast-x86_64.xml` in this repository are the signed update feeds it reads, and the `.zip` files of a release are what an update downloads.
