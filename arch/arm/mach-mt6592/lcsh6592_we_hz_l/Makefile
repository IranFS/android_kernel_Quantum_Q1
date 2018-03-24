
include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Module project related part

obj-y	+=  alsps/rpr410/
obj-y   +=  accelerometer/bma056/
obj-y	+=  magnetometer/bmm056-new/

ifneq ($(CONFIG_ARCH_MTK_PROJECT),)
ARCH_MTK_PROJECT := $(shell echo $(CONFIG_ARCH_MTK_PROJECT))
obj-y	+= core/
obj-y	+= dct/dct/
endif

obj-y	+=  camera/camera/
obj-y   +=  flashlight/constant_flashlight/
obj-y	+=  vibrator/
obj-y	+=  leds/
obj-y	+=  keypad/
obj-y	+=  sound/
obj-y	+=  accdet/

obj-y	+=  hdmi/

