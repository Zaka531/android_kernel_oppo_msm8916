#
# Makefile for the vl6180 drivers.
#

# Each configuration option enables a list of files.

ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_51
ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_51/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_51/sensor/cci
ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_51/sensor/vl6180/inc
obj-$(CONFIG_MSMB_CAMERA)			+= stmvl6180.o
stmvl6180-objs				:= stmvl6180_module.o src/vl6180x_api.o src/vl6180x_i2c.o src/vl6180x_port_i2c.o 
#obj-$(CONFIG_MSMB_CAMERA)			+= stmvl6180_module.o
#obj-$(CONFIG_MSMB_CAMERA)			+= src/vl6180x_api.o
#obj-$(CONFIG_MSMB_CAMERA)			+= src/vl6180x_i2c.o
#obj-$(CONFIG_MSMB_CAMERA)			+= src/vl6180x_port_i2c.o