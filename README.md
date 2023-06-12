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

# Libre Office
```
sudo apt-get install libreoffice-kf5
```
# Outdated Citrix 

Open firefox config
```
security.tls.version.min 3 -> 1
``
