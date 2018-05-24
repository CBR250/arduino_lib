first_rule: all

all: build install

PACKAGE_NAME := arduino-1.6.11-linux64

build: 
	if [ ! -d $(CURDIR)/../arduino ]; then \
	   mkdir $(CURDIR)/../arduino/; \
	   tar xvf $(CURDIR)/$(PACKAGE_NAME).tar.xz -C $(CURDIR)/../arduino/; \
	fi

install_rule install:

config_rule:

clean_rule:

uninstall_rule:
