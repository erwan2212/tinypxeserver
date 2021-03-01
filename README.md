# tinypxeserver

 A small portable dhcp server including a tftp and a http server.

This is freeware (and will always be), should be opensource and the unique here idea is to share and contribute.

-dhcp daemon supports an alternative filename based on the user-class thus enabling chainloading (gpxe->pxelinux, ipxe->script, etc), and also support settings dhcp options (which can then be used by your boot loader)
-tftp daemon supports tsize and blksize commands.
-http daemon support head, range (mandatory for ipxe sanboot options) and over 2gb iso.
-new in version 1.0.0.7 : BINL (RIS & WDS) support
-new in version 1.0.0.10 : DNS daemon
-new in version 1.0.0.14 : ProxyDHCP option
-new in version 1.0.0.18 : support pcbios/EFI mode
-new in version 1.0.0.23 : php,vbs,py files can be processed server side using php, vbs, py entries under web section

Discuss it here : http://reboot.pro/index.php?showtopic=18488 .
