#
# Makefile for the Cavium Octeon specific kernel interface routines
# under Linux.
#
# This file is subject to the terms and conditions of the GNU General Public
# License.  See the file "COPYING" in the main directory of this archive
# for more details.
#
# Copyright (C) 2005-2009 Cavium Networks
#

obj-y := cpu.o setup.o serial.o octeon-platform.o octeon-irq.o csrc-octeon.o
obj-y += dma-octeon.o flash_setup.o
obj-y += octeon-memcpy.o

obj-$(CONFIG_SMP)                     += smp.o

EXTRA_CFLAGS += -Werror
