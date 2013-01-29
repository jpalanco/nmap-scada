nmap-scada
==========

nse scripts for scada identification

nmap --script ./Siemens-PCS7.nse <host> -p 80

nmap -sU --script ./Siemens-Scalance-module.nse <host> -p 161

nmap -sU --script ./Siemens-WINCC.nse <host> -p 137