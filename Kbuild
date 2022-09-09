ifeq ($(CONFIG_ARCH_KALAMA), y)
dtbo-y += kalama-audio.dtbo \
                 kalama-audio-cdp.dtbo \
                 kalama-audio-cdp-nfc.dtbo \
                 kalama-audio-wsa883x-cdp.dtbo \
                 kalama-audio-mtp.dtbo \
                 kalama-audio-mtp-nfc.dtbo \
                 kalama-audio-qrd.dtbo \
                 kalama-audio-atp.dtbo \
                 kalama-audio-rcm.dtbo \
                 kalama-audio-rumi.dtbo \
                 kalama-audio-hdk.dtbo \
                 kalama-sg-audio-hhg.dtbo
endif

ifeq ($(CONFIG_ARCH_SA8155), y)
dtbo-y +=  sa8155-audio.dtbo
endif

ifeq ($(CONFIG_ARCH_KHAJE), y)
dtbo-y += khaje-audio.dtbo \
		khaje-audio-idp.dtbo \
		khaje-audio-qrd.dtbo \
		khaje-audio-qrd-hvdcp3p5.dtbo \
		khaje-audio-idp-nopmi.dtbo \
                khajeg-audio-idp.dtbo \
                khajeg-audio-idp-90hz.dtbo \
		khaje-nowcd.dtbo
endif

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
