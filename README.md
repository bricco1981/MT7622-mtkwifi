# MT7622-mtkwifi

MEDIATEK WIFI DRIVER FOR OpenWrt


put the mtk folder in /package,follow the path to the target folder and deposit the files respectively. inside we have a bootcount to replace and a patch to allow the mt7622 radio to scan for other access points.
luci-app-mtk custom for the mt7622 and mt7915 radio


please i'll not take care of updating this repo, is tested on openwrt 22.03.2

this will work on this kernel, test yourself if you will be on 5.15.x kernel

just make sure the .patch for mt7622 is in the right kernel directory

there is also a compiled version of OpenWrt-22.03.2 for xiaomi ax3200

1) clone openwrt repo!
2) put all the files right,
3) ./scripts/feeds update -a
4) ./scripts/feeds install -a
5) make        or make your openwrt command
