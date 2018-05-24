CURDIR=$(shell pwd)
PACKAGE_VERSION :=
PACKAGE_DIR :=
PACKAGE_CONF :=
first_rule: all

all: build install

build:
	$(MAKE) -C $(CURDIR)/PACKAGE/ncurses-5.9      first_rule

config_rule:

install_rule install:
		$(warning *********************************************************************)
		cp OBJ/lib/* $(CURDIR)/../arduino/arduino-1.6.11/hardware/tools/avr/lib -Rf
		
clean_rule distclean clean:

uninstall_rule uninstall:

