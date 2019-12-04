PROJECT := $(subst full_,,$(TARGET_PRODUCT))
ccflags-y += -I$(srctree)/tinno/$(PROJECT)/touchpanel/hxchipset/
#$(warning   -----------------------TARGET_PRODUCT:  $(TARGET_PRODUCT)-----------------------------)
#$(warning   -----------------------PROJECT:  $(PROJECT)-----------------------------)
# Linux driver folder
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
#ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/$(CONFIG_TOUCHSCREEN_MTK_FTS_DIRECTORY)
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/
ccflags-y += -I$(srctree)/drivers/base
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/hwmon/include
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/alsps/inc

ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/hxchipset/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
#ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
#ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/i2c/$(MTK_PLATFORM)/

# Makefile for the Himax touchscreen drivers.

obj-y += himax_platform.o himax_ic.o himax_common.o himax_debug.o
obj-$(CONFIG_TOUCHSCREEN_HIMAX_ITO_TEST)	+= himax_ito_test.o
