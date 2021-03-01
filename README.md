# tinypxeserver

 A small portable dhcp server including a tftp and a http server. </br>
</br>
This is freeware (and will always be), should be opensource and the unique here idea is to share and contribute.</br>
</br>
-dhcp daemon supports an alternative filename based on the user-class thus enabling chainloading (gpxe->pxelinux, ipxe->script, etc), and also support settings dhcp options (which can then be used by your boot loader)</br>
-tftp daemon supports tsize and blksize commands.</br>
-http daemon support head, range (mandatory for ipxe sanboot options) and over 2gb iso.</br>
-new in version 1.0.0.7 : BINL (RIS & WDS) support</br>
-new in version 1.0.0.10 : DNS daemon</br>
-new in version 1.0.0.14 : ProxyDHCP option</br>
-new in version 1.0.0.18 : support pcbios/EFI mode</br>
-new in version 1.0.0.23 : php,vbs,py files can be processed server side using php, vbs, py entries under web section</br>
</br>
Discuss it here : hhttp://reboot.pro/index.php?showtopic=18962 .</br>
