#
# Makefile for the QCOM specific video device drivers
# based on V4L2.
#
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifdef CONFIG_VENDOR_SMARTISAN_OSCAR
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_oscar/
else
ifdef CONFIG_VENDOR_SMARTISAN_ODIN
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_odin/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif # CONFIG_VENDOR_SMARTISAN_ODIN
endif
obj-y += sde/
