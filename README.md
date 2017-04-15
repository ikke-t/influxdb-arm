# influxdb-arm
Sets up Influxdb on arm device (raspi) from official influxdb binaries.

I wrote this to collect my home automation values from Node-Red and OpenHab. I display the data via Grafana.

This works on my Raspberry Pi 3 running Raspbian Linux. I wrote it due Influxdb does not provide .debs but just file package. I use NAS box to store the data over NFS, so you'll need to set ```nas_ip``` variable or just remove the mount stuff.
