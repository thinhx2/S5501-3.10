include $(srctree)/drivers/misc/mediatek/Makefile.custom

obj-y   +=  mt65xx_lcm_list.o


ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"otm1283a_hd720_dsi_vdo")
obj-y   +=  otm1283a_hd720_dsi_vdo.o
endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"otm1283a_hd720_dsi_vdo_dijing")
obj-y   +=  nt35590_hd720_dsi_cmd_auo_wvga.o
endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"nt35521_hd720_dsi_vdo_tcl")
obj-y   +=  nt35521_hd720_dsi_vdo_tcl.o
endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"hx8394a_dsi_vdo")
obj-y   +=  hx8394a_dsi_vdo.o
endif
