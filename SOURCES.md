# Upstream sources and attribution

The distributed firmware is an unmodified OpenWrt image. Copyright and component licenses remain with the respective upstream authors. Kaktusoff does not claim authorship of OpenWrt, its Linux kernel, LuCI, drivers or bundled packages.

- [Official image directory and checksums](https://downloads.openwrt.org/releases/25.12.5/targets/ramips/mt7621/)
- [OpenWrt source revision recorded in the image](https://github.com/openwrt/openwrt/tree/f5dae5ece4805730c5e2850f8aa84765af2f6b32)
- [OpenWrt v25.12.5 release tag](https://github.com/openwrt/openwrt/tree/v25.12.5)
- [Kernel build definitions and patches at the recorded revision](https://github.com/openwrt/openwrt/tree/f5dae5ece4805730c5e2850f8aa84765af2f6b32/target/linux)
- [Upstream source archive mirror for components](https://sources.openwrt.org/)
- [OpenWrt license](https://github.com/openwrt/openwrt/blob/f5dae5ece4805730c5e2850f8aa84765af2f6b32/LICENSES/GPL-2.0)

Official build inputs copied from the release directory:

- [config.buildinfo](metadata/config.buildinfo)
- [feeds.buildinfo](metadata/feeds.buildinfo)
- [version.buildinfo](metadata/version.buildinfo)

The complete extracted package inventory, including package license identifiers, is in [packages.json](metadata/packages.json). Firmware components have their own licenses; this repository does not relicense them.

The source revision embedded in the image and the release tag are recorded separately rather than assumed identical. All source references should be evaluated against the saved build inputs when reproducing the image. No local patches were applied to the published binary.

