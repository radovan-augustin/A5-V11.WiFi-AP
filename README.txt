
A5-V11.WiFi-AP is set of files of specific firmware for A5-V11 board (2.)

Features:
  - Minimalistic OpenWrt/LEDE configuration:
    - without luci, telnet, SSH
    - with TCP/IPv4, netfilter, iptables, uci, DHCP client, DHCP server
    - with drivers for RT5370 USB WiFi adapter

Default firmware configuration:
  - Without root password
  - USB WiFi adapter access point mode
  - eth network interface with DHCP client
  - wlan network interface with DHCP server, IP address 192.168.1.1
  - NAT for allowed connections from wlan

How to compile firmware:
  - Copy files from A5-V11.WiFi-AP into directory with OpenWrt/LEDE 17.01.4
  - Run make

Links:
1. https://www.openwrt.org/
2. http://wiki.openwrt.org/toh/unbranded/a5-v11
