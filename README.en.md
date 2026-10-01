# D-Link DIR-2150 R1 — OpenWrt 25.12.5

[Русский](README.md) · English

A verified mirror of the **unmodified official OpenWrt image** for **D-Link DIR-2150 R1**, with a checksum and maintenance notes. Firmware credit belongs to the OpenWrt project and contributors. Kaktusoff maintains this publication and its documentation; this is not a custom firmware build.

## Download

[GitHub release](https://github.com/Kaktusoff/D-Link-DIR-2150-R1-OpenWrt/releases/tag/openwrt-25.12.5) · [Official upstream image](https://downloads.openwrt.org/releases/25.12.5/targets/ramips/mt7621/openwrt-25.12.5-ramips-mt7621-dlink_dir-2150-r1-squashfs-sysupgrade.bin)

- Device: **DIR-2150 R1**, `dlink,dir-2150-r1`; not A1.
- OpenWrt: **25.12.5**, `r33051-f5dae5ece4`.
- Target: `ramips/mt7621`; architecture: `mipsel_24kc`; kernel: **6.12.94**.
- File: `openwrt-25.12.5-ramips-mt7621-dlink_dir-2150-r1-squashfs-sysupgrade.bin`.
- Size: **8,305,196 bytes**.
- SHA256: `ea1a68ab4588bbb6d7b319bbda153cc5a511ae8d982e2e41a286f643a3ba8459`.

The saved file was checked against [OpenWrt's official checksums](https://downloads.openwrt.org/releases/25.12.5/targets/ramips/mt7621/sha256sums) on October 1, 2026. Its bytes and original filename are unchanged.

## Contents and installation scope

The image includes the official base system and LuCI with Bootstrap. See the [161-package inventory](metadata/packages.json).

**Podkop, Sing-box, Zapret, Adblock, WireGuard and subsequent personal settings are not embedded.** These were installed separately on a serviced router. [Configuration notes](CONFIGURATION-NOTES.md) describe that historical setup; they are not an installer or a transferable configuration backup.

This is a **sysupgrade image for an existing OpenWrt installation on R1**, not an OEM factory-install image. Check the hardware revision, save your own configuration backup, verify SHA256 and let LuCI validate compatibility before upgrading. Do not bypass a failed compatibility check.

The embedded compatibility version is `1.1`, with a **swconfig-to-DSA migration warning**. Do not preserve an old swconfig network configuration. Resolve the migration for your installed version before proceeding. Consult the [OpenWrt device page](https://openwrt.org/toh/hwdata/d-link/d-link_dir-2150_r1) for first installation from D-Link firmware.

No personal credentials or device backup are distributed. A fresh image has no preset root password: set your own at first login. Prior operation was observed on one R1 unit; no new hardware validation was performed for this publication.

## Sources, questions and optional support

[Sources and attribution](SOURCES.md) · [Image audit](metadata/image-audit.json) · [GitHub Issues](https://github.com/Kaktusoff/D-Link-DIR-2150-R1-OpenWrt/issues)

For questions, include the hardware revision, installed OpenWrt version and exact error. Never post passwords, private keys or VPN credentials.

[Optional support for Kaktusoff's work](DONATE.md). Downloads and documentation are free; donations are not required for access or support. The firmware itself is the work of OpenWrt and its contributors.

