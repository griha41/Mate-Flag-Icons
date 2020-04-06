# Mate Languages Flags
Language flags for MATE Desktop. 
<br>

# Installation
 Place "flags" folder in:
  - For system-wide: /usr/share/pixmaps
  - For user-only: ~/icons
 
 GUI-way:
  1. Run dconf-editor (or install it 'sudo apt install dconf-editor' and then run it)
  2. Then go to section: org->mate->desktop->peripherals->keyboard->indicatorn
  3. Switch key “show-flags” from "false" to "true"

 Terminal:
   - gsettings set org.mate.peripherals-keyboard-xkb.indicator show-flags true
   
  If you want disable it set back to false!
 
 PROFIT!!!!
 
# Checked on:
Linux Mint 18.3<br>
Linux Mint 19.1<br>
Linux Mint 19.2<br>
Linux Mint 19.3<br>
GNU\Linux Debian 10 "Buster"<br>
GNU\Linux Debian 10.1 "Buster"<br>
GNU\Linux Debian 10.2 "Buster"<br>
GNU\Linux Debian 10.3 "Buster"<br>

# Support
 If you check on other Linux-based OS, please report issue with header "Confirmed on ...".<br>
 Example: "Confirmed on Debian 9.5" and this OS will added to Readme.md.
