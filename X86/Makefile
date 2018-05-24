CURDIR=$(shell pwd)
PACKAGE_VERSION :=
PACKAGE_DIR :=
PACKAGE_CONF :=
first_rule: all

all: build

build:
	$(MAKE) -C $(CURDIR)/arduino-1.6.11      first_rule
	$(MAKE) -C $(CURDIR)/readline            first_rule
	$(MAKE) -C $(CURDIR)/ncurses-5.9         first_rule
	
config_rule:

install_rule install:

clean_rule distclean clean:

uninstall_rule uninstall:

