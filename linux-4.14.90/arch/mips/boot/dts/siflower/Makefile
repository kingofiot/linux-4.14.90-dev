# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_DT_SF16A18_FULLMASK_P10)	+= sf16a18_fullmask_p10.dtb
dtb-$(CONFIG_DT_SF16A18_FULLMASK_P10M)	+= sf16a18_fullmask_p10m.dtb
dtb-$(CONFIG_DT_SF16A18_FULLMASK_X10)	+= sf16a18_fullmask_x10.dtb
dtb-$(CONFIG_DT_SF16A18_FULLMASK_86V)	+= sf16a18_fullmask_86v.dtb
dtb-$(CONFIG_DT_SF16A18_FULLMASK_P10_FLASH)	+= sf16a18_fullmask_p10_flash.dtb
dtb-$(CONFIG_DT_SF16A18_FULLMASK_P20)	+= sf16a18_fullmask_p20.dtb
dtb-$(CONFIG_DT_SF16A18_FULLMASK_ACCTL)	+= sf16a18_fullmask_ac.dtb

obj-y		+= $(patsubst %.dtb, %.dtb.o, $(dtb-y))
always				:= $(dtb-y)
clean-files			:= *.dtb *.dtb.S
