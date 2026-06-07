# **Proxmox Computer:**
- [ ] RAM: At least 16 GB
- [ ] CPU: 6 core 12 thread processor (potentially could use a 4 core 8 thread processor)
- [ ] Storage: 256 GB M.2 SSD (the storage size can be lower and the device can be a SATA SSD but if you're planning to give your VMs more storage I recommend this size)
- [ ] NIC: 1 Gb (for a smooth connection with the Proxmox web GUI)

# **Switch:**
- [ ] Brand: Netgear (if going with a different brand or model make sure that it's a "managed" switch)
- [ ] Model: GS305E (I mostly recommend this one since it's the one I use and have experience with but you can choose a different one if you'd like)
- [ ] Port number: At least 5 ports (can be more if planning to add more devices)
- [ ] Ports speed: 1 Gb

# **Router/Firewall:**
With this one I didn't get any kind of specific router/firewall device. Instead, I put Opnsense on an old computer since it was the most convenient option. In order to follow this tutorial you'll need a device with Opnsense installed on it, this can either be an old computer like I did, or, you can get another router/firewall and install Opnsense onto that device.
- [ ] RAM: At least 4 GB
- [ ] CPU: 2 core 4 thread processor
- [ ] Storage: 123 GB M.2 SSD (could also be a SATA SSD if you're fine with slower speed)
- [ ] NIC: 1 Gb

# **Raspberry Pi:**
This is mainly used to connect to your main router wirelessly so that your homelab network can connect to the internet. If you are able to connect your main router with a patch cable then you don't have to do this. OpenWRT will be installed on this device and it can be the Raspberry Pi 4. The specs don't need to be too high and you can get a starter kit from CanaKit.

# **Laptop:**
- [ ] RAM: At least 16 GB
- [ ] CPU: 4 core 8 thread processor
- [ ] Storage: 512 GB M.2 SSD
- [ ] NIC: 1 Gb

# **Monitor:**
This can be an old monitor you have lying around or you can get a new one but just make sure it has the same connection port that you have on your Proxmox computer whether it's Display Port, HDMI, VGA, or other.

# **Cables:**
You'll need patch (ethernet) cables that are cat 5e or better (you might not need them to be better than cat 5e if speed isn't an issue but 5e is recommended).

# **Keyboard/Mouse:**
If you have a wired keyboard and mouse lying around you can use those but if you're able to I would recommend using a wireless keyboard and mouse so that you don't have to deal with more wires.

# **USB To Ethernet Adapter:**
If needed, (since many laptops today don't have an ethernet port built in) get a USB to Ethernet Adapter so that you are able to plug your laptop into your switch for connectivity to your lab environment