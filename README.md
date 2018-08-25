# proxmox_4.4_hpt_rocket750
Updated hptdrv-monitor script to work with ProxMox v4.4

Changes involve renaming:

"linux-image" becomes "pve-image"

"pve-kernel" becomes "pve-kernel"

Tested on ProxMox 4.4

Instructions:

Get Linux <= 4.9 driver package from http://www.highpoint-tech.com/USA_new/series_r750-Download.htm

Run install per README (will fail)

Copy hptdrv-monitor to /etc/init.d/htpdrv-monitor

Run install again (ignore udev errors)

Reboot
