# MT7622-mtkwifi

MEDIATEK WIFI DRIVER FOR OpenWrt


put the mtk folder in /package,follow the path to the target folder and deposit the files respectively. inside we have a bootcount to replace and a patch to allow the mt7622 radio to scan for other access points.
luci-app-mtk custom for the mt7622 and mt7915 radio
it's tested on openwrt 22.03.x
this will work on this kernel, test yourself if you will be on 5.15.x kernel

"to do"

1) clone openwrt repo!
2) put all the files right,
3) ./scripts/feeds update -a
4) ./scripts/feeds install -a
5) make menuconfig
6) select luci app mtwifi,select mt7622 and mt_wifi in kernel module, in extra package select l1profile
7) make download
8) make

"forse la fine"
