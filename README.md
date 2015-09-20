# P2812HNUFx-Pre-Build
P2812HNUFx images and files

Files are TRUNK based, OpenWrt Designated Driver r46993, kernel 3.18.21.
<p>
Image contains: luci, Lantiq atm/ptm driver, wireless calibration data, VDSL firmware and some basic modules, fixed F3 WiFi.
<p>
Annex firmware can be changed (replaced to one in VDSL firmware folder) after flashing.
<p>
<p>
ADSL/VDSL Firmware updated to:
<p>
5.7.4.4.1.7-5.7.1.5.0.2 - ADSL Annex B / VDSL over ISDN incl. vectoring support
<p>
5.7.4.4.1.7-5.7.1.8.0.1 - ADSL Annex A / VDSL over ISDN incl. vectoring support
<p>
LAN part reverted back to separate WAN/LAN (gets rid of "tx ring" errors)
<p>
Flashing instruction can be found on OpenWRT wiki.
<p>
After flashing, software repo can be changed to one in "repo.txt". it points to packages for this builds on my server. 
<p>
