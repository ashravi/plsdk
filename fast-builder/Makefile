include $(BUILDER_HOME)/builder.mk

lib_dirs := \
	pl-kernel-headers \
	python-headers \
	external/eglib \
	libplutil \
	libplepaper \
	mod_plepaper \
	libpldraw \
	libplinput \
	libplhw \
	pldata/ \
	pldata/lzss/lib \
	plsdk/libplsdk \
	pyplsdk \
	pldata/lzss/python \
	external/zlib \
	external/libpng \
	external/libjpeg \
	external/zlibmodule \
	external/pil

app_dirs := \
	eptest \
	epview \
	plinput \
	plottest \
	plhwtools \
	pldata/lzss/app

subdirs := $(lib_dirs) $(app_dirs)

.PHONY: all

all: print-arch sub-make
