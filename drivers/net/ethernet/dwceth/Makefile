################################################################################
#
#   Copyright (c) 2014 Minoca Corp.
#
#    This file is licensed under the terms of the GNU General Public License
#    version 3. Alternative licensing terms are available. Contact
#    info@minocacorp.com for details. See the LICENSE file at the root of this
#    project for complete licensing information.
#
#   Module Name:
#
#       DesignWare Ethernet
#
#   Abstract:
#
#       This module implements the Synopsys DesignWare Ethernet network driver.
#
#   Author:
#
#       Evan Green 5-Dec-2014
#
#   Environment:
#
#       Kernel
#
################################################################################

BINARY = dwceth.drv

BINARYTYPE = so

BINPLACE = bin

OBJS = dwceth.o    \
       dwcethhw.o  \

DYNLIBS = $(BINROOT)/kernel                 \
          $(BINROOT)/netcore.drv            \

include $(SRCROOT)/os/minoca.mk

