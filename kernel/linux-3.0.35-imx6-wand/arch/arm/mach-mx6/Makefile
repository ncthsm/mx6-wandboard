#
# Makefile for the linux kernel.
#

# Object file lists.
obj-y   := cpu.o mm.o system.o irq.o bus_freq.o \
cpu_op-mx6.o mx6_wfi.o cpu_regulator-mx6.o \
 mx6_ddr_freq.o mx6sl_ddr.o mx6sl_wfi.o etm.o

obj-$(CONFIG_PM) += pm.o 
obj-$(CONFIG_MMC_SDHCI_ESDHC_IMX) += mx6_mmdc.o
obj-$(CONFIG_USB_EHCI_ARC_HSIC) += usb_h2.o usb_h3.o
obj-$(CONFIG_GENERIC_GPIO) += devices.o dummy_gpio.o
obj-$(CONFIG_FEC) += mx6_fec.o 
obj-$(CONFIG_REGULATOR_ANATOP) += mx6_anatop_regulator.o
obj-$(CONFIG_ARCH_MX6) += clock.o mx6_suspend.o clock_mx6sl.o
obj-$(CONFIG_MACH_MX6Q_ARM2) += board-mx6q_arm2.o
obj-$(CONFIG_MACH_MX6SL_ARM2) += board-mx6sl_arm2.o mx6sl_arm2_pmic_pfuze100.o
obj-$(CONFIG_MACH_MX6SL_EVK) += board-mx6sl_evk.o mx6sl_evk_pmic_pfuze100.o
obj-$(CONFIG_MACH_MX6Q_SABRELITE) += board-mx6q_sabrelite.o
obj-$(CONFIG_MACH_MX6Q_SABRESD) += board-mx6q_sabresd.o mx6q_sabresd_pmic_pfuze100.o
obj-$(CONFIG_MACH_MX6Q_SABREAUTO) += board-mx6q_sabreauto.o mx6q_sabreauto_pmic_pfuze100.o
obj-$(CONFIG_SMP) += plat_hotplug.o platsmp.o headsmp.o
obj-$(CONFIG_LOCAL_TIMERS) += localtimer.o
obj-$(CONFIG_IMX_PCIE) += pcie.o
obj-$(CONFIG_USB_EHCI_ARC_H1) += usb_h1.o
obj-$(CONFIG_USB_FSL_ARC_OTG) += usb_dr.o
obj-$(CONFIG_MACH_WANDBOARD) += board-wand.o
obj-$(CONFIG_WANDBOARD_BASE) += baseboard-wand.o

