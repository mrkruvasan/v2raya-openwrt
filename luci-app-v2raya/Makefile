include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for v2rayA
LUCI_DEPENDS:=+v2raya

PKG_VERSION:=12
PKG_RELEASE:=1
PKG_PO_VERSION:=$(PKG_VERSION)

PKG_LICENSE:=Apache-2.0
PKG_MAINTAINER:=OpenWrt

include $(TOPDIR)/feeds/luci/luci.mk

$(eval $(call BuildPackage,luci-app-v2raya))
