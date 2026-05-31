# [ tonion-automation ]
[*] Shell based simple script Tor+firewall+no ipv6 automation for linux distros

[*] Dependencies(pkgs): openbsd-netcat curl tor iptables iproute2 networkmanager e2fsprogs coreutils util-linux bash iptables-nft nftables sudo obfs4proxy

[!] Script actions: --start, --stop, --restart, --boot-enable, --boot-disable, --myip, --change, --fix, --set-bridges --restart-torrc, --help.

[!] Get it right now: git clone https://github.com/NewMaster27/tonion && cd tonion && chmod +x make_bin.sh && sudo ./make_bin.sh && tonion help

[!] In addition: 
- Recommended: Configure a browser that provides anonimity out of the box(as torbrowser or mullvad), to use this script. 
- Recommended: Use Tor bridges or a VPN connection like openvpn, wireguard (this always before running the script, requires custom interface configuration on firewall rules), just in case you want to hide tor from your ISP.
