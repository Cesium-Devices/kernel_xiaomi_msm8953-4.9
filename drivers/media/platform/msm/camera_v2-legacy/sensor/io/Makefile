# Silence Clang warning
ifeq ($(cc-name),clang)
EXTRA_CFLAGS += $(call cc-option, -Wframe-larger-than=6144)
endif

ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/
ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/sensor
ccflags-y += -Idrivers/media/platform/msm/camera_v2-legacy/sensor/cci
ccflags-y += -Idrivers/misc/
obj-$(CONFIG_MSMB_CAMERA)   += msm_camera_cci_i2c.o msm_camera_qup_i2c.o msm_camera_spi.o msm_camera_dt_util.o msm_camera_tz_i2c.o
