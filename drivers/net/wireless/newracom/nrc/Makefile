# SPDX-License-Identifier: GPL-2.0

obj-$(CONFIG_NRC7394) += nrc.o

nrc-y := \
	hif.o \
	mac80211-ext.o \
	nrc-bd.o \
	nrc-debug.o \
	nrc-dump.o \
	nrc-fw.o \
	nrc-init.o \
	nrc-mac80211.o \
	nrc-mac80211-twt.o \
	nrc-netlink.o \
	nrc-pm.o \
	nrc-ps.o \
	nrc-s1g.o \
	nrc-stats.o \
	nrc-trace.o \
	nrc-trx.o \
	nrc-twt-sched.o \
	wim.o \
	nrc-hif-cspi.o

ccflags-y += -I$(src)
ccflags-y += -DCONFIG_NRC_HIF_CSPI
ccflags-y += -DCONFIG_NRC_TRACING
ccflags-y += -Wall -Werror
