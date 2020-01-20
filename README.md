# IP-wall
List of IP addresses and ranges, caught during hacking and/or intrussion attempts.

List produced by: `sudo iptables -S | grep DROP | sort -u | sed -ne 's/^.*-s \(.*\) -j.*$/\1/pg'`

Starting 2020 (and partially december of 2019) all offending logs are provided right away.

Current coverage of the "whole internet" can be seen [here](http://commi.ddns.info/ISec), updates twice a day.

We have surpassed 35%!

If you own any of the listed ranges and would like to clear your name, feel free to open an issue with the related ranges and/or ASN in the topic to possibly receive the offending logs and fix the issue from your side.
