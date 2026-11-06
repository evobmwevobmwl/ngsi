# Ngsi (No more gsi updates)

Generic System Images built from stock firmware, with extra fixes and debloat.
Maintainer: **ArtemOPENGnu**.

## Branches
| Branch | Content |
|---|---|
| `main` | this page and the build index |
| `android-16` | Android 16 build cards |
| `android-15` | Android 15 build cards |
| `android-14` | Android 14 build cards |

Images are attached to [Releases](../../releases). Large images are split into parts
(`.zip.001`, `.zip.002`): open the first part with 7-Zip / WinRAR, or join them with
`cat file.zip.0* > file.zip`.

## Builds
<!-- NGSI-INDEX-START -->
_No builds yet._
<!-- NGSI-INDEX-END -->

## Install (short)
1. Unlocked bootloader, Treble-compatible device.
2. `fastboot reboot fastboot` → `fastboot flash system Ngsi-*.img` → `fastboot -w` → reboot.

Includes components licensed under the Apache-2.0 license.
