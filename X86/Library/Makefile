CURDIR=$(shell pwd)
PACKAGE_VERSION :=
U8glib_Arduino_PACKAGE_NAME := U8glib_Arduino
U8glib_Arduino_PACKAGE_DIR := U8glib_Arduino
RF24_master_PACKAGE_NAME := RF24-master
RF24_master_PACKAGE_DIR := RF24-master
PACKAGE_CONF :=
first_rule: all

all: build install

build:

config_rule:

install_rule install:
		$(warning ******************************* Install library u8glib_arduino **************************************)
		tar xvf $(CURDIR)/$(U8glib_Arduino_PACKAGE_DIR)/$(U8glib_Arduino_PACKAGE_NAME).tar.gz -C $(CURDIR)/../arduino/arduino-1.6.11/libraries/; \

		$(warning ******************************* Install library RF24-master **************************************)
		$(warning ******************************* Download from https://github.com/maniacbug/RF24/ **************************************)
		tar xvf $(CURDIR)/$(RF24_master_PACKAGE_DIR)/$(RF24_master_PACKAGE_NAME).tar.bz2 -C $(CURDIR)/../arduino/arduino-1.6.11/libraries/; \
				
clean_rule distclean clean:

uninstall_rule uninstall:

