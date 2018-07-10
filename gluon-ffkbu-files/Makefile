include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-ffkbu-files
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/gluon-ffkbu-files
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:= Different configfiles for Freifunk KBU Hood Bonn
  DEPENDS:=
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-ffkbu-files/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-ffkbu-files/postinst
endef

$(eval $(call BuildPackage,gluon-ffkbu-files))
