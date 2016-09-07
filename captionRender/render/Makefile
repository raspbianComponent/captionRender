OBJS=font.o graphics.o vgft.o main.o
BIN=captionRender

LDFLAGS+=-lfreetype -lz
INCLUDES+=-I$(PKG_CONFIG_SYSROOT_DIR)/usr/include/freetype2 -I$(PKG_CONFIG_SYSROOT_DIR)/usr/include -I$(PKG_CONFIG_SYSROOT_DIR)/usr/include/c++/5.2.1/arm-rdk-linux-gnueabi

include ../Makefile.include

