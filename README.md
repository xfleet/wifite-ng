
This is a modified wifite fork, with patches & fixes to meet todays needs of deps & libs.
If your interested in participating to keep this tool alive & working in the future..
  -- Feel free to join up, we want you on our team!

* Now support Pixie attack + a timeout switch
* Fixes for tshark from https://github.com/darkr4y/wifite-mod
* Macchanger fix
* Oui lookup for pingen attack

# NEW Added flags
    -pto <sec>        # configurable timeout for pixiewps attack, default 660
    -ponly            # uses only pixiewps and reaver up until M3
    -pnopsk           # do not run retrieved pin through reaver
    -paddto <sec>     # add n seconds to timeout on each hash retrevial, default 30
    -update           # now updates to this fork instead of original wifite
    -endless          # will now loop through targets forever until stopped
    
    
# Required Tools / Dependencies

    You must install Pixiewps by Wiire (https://github.com/wiire/pixiewps)
      and 
    You must install reaver-wps-fork-t6x by t6x (https://github.com/t6x/reaver-wps-fork-t6x)
      and maybe, just maybe..
    You want "bully" (https://github.com/kimocoder/bully) - a fork from "wiire"

# TODO
    * Add check for pixiewps, modified reaver, and offer option to install.
    * Add check to see if update is needed before performing.
    * Add option to dynamically spoof connected client while running attack.
    * Add option to auto-skip previously cracked AP instead of prompting.
    * Add recording for individual access points(clients, signal strenght, hashes, solved pins, etc).   
    * Add option to download and install pixiewps and modified reaver from github
    * Add mdk3 support
    * Add default pin calculations and options
    * Add "airmon-ng check" & "check kill" for killing the stuff that may cause interferance with the tool.
    * Extend the "updater" with checks for "reaver", "pixiewps" & "bully" and other dependencies.
    
    * Add --clients option to filter on station clients.
      - This feature is an idea from [https://github.com/derv82/wifite/pull/64/commits/18e7ae0299218aed4361cf3fa7558001cb3c1da5]


# Thanks to all nerds who made this tool working again!

A shoutout to the owner/maintainer of the original, "derv82" - original source to be found @ [https://www.github.com/derv82]
but also a big thanks to Wiire, aanarchyy, DataHead, soxrok2212, nxxxu, nuroo and the great binkybear & g0tm1lk @ Kali / NetHunter for bringing all the patches & fixes that made it work again!

