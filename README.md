# zabbix-check-mdadm2

**This version is archived. It still should work on OS's with python2 and small changes with python3 too. A newer simpler version in POSIX sh can be found here: [zabbix-check-mdadm3 ](https://github.com/zabbix-deb/zabbix-check-mdadm3)**

## Description

A script to monitor mdadm RAID with [Zabbix](https://zabbix.com).

This is a rewrite of the first version (zabbix-check-mdadm) in Python. In addition to the number of failed disks, it can also return the overall status of the RAID.

## Usage

* Clone this repo and build the debian package yourself with `LANG=C debuild -us -uc -b; dh clean`
**or**
* Install it directly from @istoph's [repository](https://blog.chr.istoph.de/repository/)
**or**
* Clone this repo and install the script and config by hand

## Dependencies

* Python (>= 2.6)

## Licence

New BSD License/BSD 3-Clause License (see [debian/copyright](debian/copyright))

## Template for the Zabbix frontend

A template for the Zabbix frontend can be found, as usual in our packages, in [/usr/share/doc/${package_name}/](usr/share/doc/zabbix-check-mdadm2/)

