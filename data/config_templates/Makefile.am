#
# This file is a part of the NsCDE - Not so Common Desktop Environment
# Author: Hegel3DReloaded
# Licence: GPLv3
#

localscriptsdir = $(NSCDE_DATADIR)/config_templates/
localscripts_SCRIPTS = fontmgr.local colormgr.local

localdatadir = $(NSCDE_DATADIR)/config_templates/
localdata_DATA = Dunst.conf dot_xscreensaver

clean-local:
	-rm -f $(localscripts_SCRIPTS) $(localdata_DATA)

install-data-hook:
	$(mkinstalldirs) $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/app-defaults $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/fvwm $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Gkrellm $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/progbits $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/BGdefault $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Dunst.conf $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/dot_xscreensaver $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/rofi_config $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Xset.conf $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/GeoDB.ini $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Stalonetray.conf $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Xdefaults $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Xdefaults.fontdefs $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Xdefaults.mouse $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/Xsettingsd.conf $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
	-cp -r $(srcdir)/colormgr.addons $(DESTDIR)$(NSCDE_DATADIR)/config_templates/
