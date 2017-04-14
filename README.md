
This is a modified wifite fork, with patches to make it work again.
If your interested in joining up keeping this tool alive & working -- feel free to join up!

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

# TODO
    * Add check for pixiewps, modified reaver, and offer option to install.
    * Add check to see if update is needed before performing.
    * Add option to dynamically spoof connected client while running attack.
    * Add option to auto-skip previously cracked AP instead of prompting.
    * Add recording for individual access points(clients, signal strenght, hashes, solved pins, etc).   
    * Add option to download and install pixiewps and modified reaver from github
    * Add mdk3 support
    * Add default pin calculations and options

