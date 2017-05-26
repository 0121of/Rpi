# 5inch_lcd

# uncomment if hdmi display is not detected and composite is being output
hdmi_force_hotplug=1

# uncomment to force a specific HDMI mode (this will force VGA)
hdmi_group=2
hdmi_mode=87
hdmi_cvt 800 480 60 6 0 0 0

# Next two lines forces audio through the jack - HDMI-audio crashes the display!
hdmi_drive=1
hdmi_ignore_edid_audio=1
