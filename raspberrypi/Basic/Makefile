MODULE_NAME = basic_driver
TOOLCHAIN = /Users/yatheesha/Documents/Softwares/ToolChain/raspberrypi/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian/bin/arm-linux-gnueabihf-
KDIR = /Users/yatheesha/Documents/Softwares/ToolChain/raspberrypi/linux


TARGET = arm
#PWD=$(shell pwd)
MODULE_UPLOAD = $(MODULE_NAME).ko
obj-m += $(MODULE_NAME).o

all:
	make -C $(KDIR) M=$(shell pwd) ARCH=$(TARGET) CROSS_COMPILE=$(TOOLCHAIN) modules
clean:
	make -C $(KDIR) M=$(shell pwd) ARCH=$(TARGET) CROSS_COMPILE=$(TOOLCHAIN) clean