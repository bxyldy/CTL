## Process this file with automake to produce Makefile.in

EXTRA_DIST = \
	utilities.ctl \
	transform_RRT.ctl \
	transform_display_video.ctl


ctldatadir = $(libdir)/CTL
ctldata_DATA = \
	utilities.ctl \
	transform_RRT.ctl \
	transform_display_video.ctl

# since ctl files appear above, tell the makefile to do nothing
# with them (except install them)
%.ctl:
	@true
