#
# Makefile for wrapping the merged archive of GAP packages
#
# update: to test with the last release in the stable branch
# minor : to test with the tip of the stable branch
# major : to test with the tip of the default branch
# integration : to test with the tip of the integration branch

pkg-update:
	./mergePackages tip matgrp=no citrus=no

pkg-minor:
	./mergePackages tip matgrp=no citrus=no

pkg-major:
	./mergePackages tip citrus=no

pkg-integration:
	./mergePackages tip citrus=no
