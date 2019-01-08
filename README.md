# Mate-Flag-Icons
Language flags for MATE Desktop. Checked with Linux Mint 19.1
<br>

# Installation
	For system-wide: /usr/share/pixmaps (plase folder flags)
	For user-only: ~/icons (plase folder flags)
Then run dconf-editor (or install it and then run it)
Then go to section: org->mate->desktop->peripherals->keyboard->indicatorn
Switch key “show-flags” from "false" to "true"

(
   ALSO FOR Terminal:
	gsettings set org.mate.peripherals-keyboard-xkb.indicator show-flags true
)

If you want disable it set back to false!
<br><br>
PROFIT!!!!
