SPK_NAME = exfat
SPK_VERS = 1.2.2
SPK_REV = 1
SPK_ICON = src/exfat.png

DEPENDS = cross/fuse-exfat cross/exfat-utils

MAINTAINER = SynoCommunity
DESCRIPTION = This project aims to provide a full-featured exFAT file system implementation for Unix-like systems. It consists of a FUSE module \(fuse-exfat\) and a set of utilities \(exfat-utils\).
DISPLAY_NAME = exFAT
STARTABLE = no
CHANGELOG = "Initial release"
BETA = 1

HOMEPAGE = https://github.com/relan/exfat
LICENSE  = GNU GPLv2

INSTALLER_SCRIPT = src/installer.sh
SSS_SCRIPT       = src/dsm-control.sh

INSTALL_PREFIX = /usr/local/$(SPK_NAME)

include ../../mk/spksrc.spk.mk

