# bash
general-virtual-ips-script was something I used to create an isolated (internal to the test server) 200+ IP network<br>
It allowed for the emulation of an IP Farm. You can expand on the size by changing the subnet parameters.<br>
Mostly used for physical devices needing to be soak tested against large ip ranges without having to use real network<br>
hardware and not having access to hypervisors at the time.<br><br>
get-int-ext-ip-addresses is useful. It saves me looking up how to check my external IP Address with curl, I never remember the URLs.<br><br>
yad-sysconfig.sh needs to have yad installed before use. Unlike dialog or whiptail, yad leverages GTK toolkit for a GUI interface<br> 
so you can use it as a wrapper to then execute your scripts or share information.<br>
<br>
ginettanyk
