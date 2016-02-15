# glinetpineapple
Wifi Pineapple firmware for for GL.iNet GL-AR150

how to build:
build firmware-mod-kit https://code.google.com/archive/p/firmware-mod-kit/wikis/Documentation.wiki
extract wifipineapple firmware (https://www.wifipineapple.com/nano) with firmware-mod-kit
clone https://github.com/domino-team/openwrt-cc
cp firmware-mod-kit/fmk/rootfs/* openwrt-cc/files/*
build openwrt-cc
