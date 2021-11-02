# Linux WiFi driver rtl8xxxu backported from mainline 5.14 to 3.18
#  Tested on RTL8723BU running on tiny ARM linux system
#  Small memory footprint, but lacks power management
#  
# The driver at:
#   https://github.com/brentr/rtl8723bu.git
# is derived from the RealTek's source.  
# It is 800KB (vs. 550KB), but draws only 25% of the power.

# You get to choose.
