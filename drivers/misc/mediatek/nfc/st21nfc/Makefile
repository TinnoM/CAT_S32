#
# Makefile for ST21NFC
#

ifneq ($(strip $(TARGET_BUILD_VARIANT)),user)
ccflags-y += -DCONFIG_NFC_DEBUG
endif

ccflags-y += -I$(srctree)/drivers/misc/mediatek/base/power/include
obj-y +=st21nfc.o
# ccflags-$(CONFIG_NFC_DEBUG) := -DDEBUG
