# IP-wall
List of IP addresses and ranges, caught during hacking and/or intrussion attempts.

List produced by: `sudo iptables -S | grep DROP | sort -u | sed -ne 's/^.*-s \(.*\) -j.*$/\1/pg'`

Current coverage of the "whole internet" can be seen [here](http://commi.ddns.info/ISec), updates twice a day.
