# influxdb-arm
Sets up Influxdb on arm device (raspi) from official influxdb binaries.

I wrote this to collect my home automation values from Node-Red and OpenHab. I display the data via Grafana.

This works on my Raspberry Pi 3 running Raspbian Linux. I use NAS box to store the data over NFS, so you'll need to set ```nas_ip``` variable or just remove the mount stuff.

I wrote it due Influxdb did not provide .debs but just file package. Later I found out there are .debs afterall, and changed this to add the correct repo to find the .debs. If you however want to go back to version with no debs used (rpm based distro for example), this is the version which works there:

https://github.com/ikke-t/influxdb-arm/tree/7f7c94a628de1a450102df02e1d15e9a6c120eb3
