# Ngsi (No more gsi updates)

Generic System Images built from stock firmware, with extra fixes and debloat.
Maintainer: **ArtemOPENGnu**.

## Branches
| Branch | Content |
|---|---|
| `main` | this page and the build index |
| `android-17` … `android-10` | build cards for that Android version (one branch per version) |

Images are attached to [Releases](../../releases). Large images are split into parts
(`.zip.001`, `.zip.002`): open the first part with 7-Zip / WinRAR, or join them with
`cat file.zip.0* > file.zip`.

## Builds
<!-- NGSI-INDEX-START -->
| Build | Android | OEM | Files |
|---|---|---|---|
| Ngsi-Xiaomi-MIUI-zeus-A13-V13.2.7.0.TLBCNXM-20261107 | Android 13 | Xiaomi-MIUI | [download](https://github.com/evobmwevobmwl/ngsi/releases/tag/Ngsi-Xiaomi-MIUI-zeus-A13-V13.2.7.0.TLBCNXM-20261107) |
<!-- NGSI-INDEX-END -->

## Install (short)
1. Unlocked bootloader, Treble-compatible device.
2. `fastboot reboot fastboot` → `fastboot flash system Ngsi-*.img` → `fastboot -w` → reboot.

Includes components licensed under the Apache-2.0 license.
