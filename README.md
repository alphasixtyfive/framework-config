# framework-config
Various config notes for Framework 13 Laptop

# Keyboard brightness controls

```
sudo nano /etc/modprobe.d/framework-als-blacklist.conf
```
```
blacklist hid_sensor_hub
```
```
sudo update-initramfs -u
```
