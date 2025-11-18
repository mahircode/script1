#! /bin/bash

cat /etc/default/grub

cat /etc/udev/rules.d/70-persistent-net.rules

ip address

ifconfig

ip link show

cat /etc/network/interfaces

sudo cat /opt/versa/scripts/van-scripts/vandriver.conf

sudo cat /opt/versa/scripts/van-scripts/vansetup.conf

route -n

lsb_release -a

uname -r

free -h

df -h

top -H


CLI Command

show system details | nomore

show system package-info

show security osspack info

show log-collector-exporter local collectors status

show log-collector-exporter local collectors connections | nomore

show log-collector-exporter local collectors connections | count

show log-collector-exporter remote collectors connection | nomore

show log-collector-exporter remote collectors connection | count

show configuration | display set | nomore

show configuration | display set | count
