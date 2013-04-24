Change log

1.56
- bug fixes
- improve HTMP area
- added many IB topology related information snapshot
=====================================================================================================================
1.24 
  - More files... to files section /proc/net/dev_mcast /proc/net/bonding/* /sys/class/net/*
=====================================================================================================================

1.22
  - more commands: ip a s, ip m s, ip n s and files, etc/isse, /proc/net/sdp. 

=====================================================================================================================
1.18
  - added Infiniband switches scan to show switches properties (revision, firmware version, date, PSID, etc) 

=====================================================================================================================

1.04
  - Added the '-t' flag for text only output, no HTML, requested by David Bahi
  - Added index at the last HTML entry
  - Read /etc/sysconfig/sysinfo-snapshot, if exists, for extra files and commands
  - Added /var/log/messages to the files list
  - Added mount and uptime commands to the commands list
  - Sort the list of files and commands (in the columns and not along the rows)
  - CGI autodetect CGI mode, generate HTML to standard output and not into file with the correct headers

=====================================================================================================================

Version 1.1 
April, 14 2009
Yair Ifergan


  - added InfiniBand SM activity check: 
  - added HW info to dump all network cards: hwinfo --netcard
  - added files  /etc/hosts.allow 
                 /etc/hosts.deny
  - added following netstat calles:
	netstat -nlp
	netstat -nr
	netstat -i
  - added IPtables rules list:
	iptables -t filter -nvL
	iptables-save -t filter
	iptables -t nat -nvL
	iptables-save -t nat
	iptables -t mangle -nvL
	iptables-save -t mangle

