# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	rock-4c-plus-radxa-display-10fhd.dtbo \
	rock-5b-radxa-display-10hd.dtbo \
	rock-5b-hdmi1-8k.dtbo \
	rock-5b-hdmi2-8k.dtbo \

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
	README.rockchip-overlays

targets += $(dtbo-y) $(dtbotxt-y)

always-y		:= $(dtbo-y) $(dtbotxt-y)
clean-files		:= *.dtbo

