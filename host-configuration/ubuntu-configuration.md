
<p><h1>Installer</h1></p>

1. Select your language
2. Select Keyboard layout & Variant
3. Server selection: Ubuntu Server
4. Configure interface: Enter an IP Address for your machine (192.168.1.112/24 for me)
5. Proxy address -- SKIP
6. Mirror Address: Default
7. Storage layout: Defualt
8. File System Summary: Done --> Continue when warning pops up.
9. Profile Configuration: All your choice (U: unifi, server-name: sec01-us01)
10. Upgrade to ubuntu-pro: No
11. SSH Config: Install SSH Server
12. Install SNAPS?: No
13. Allow updates to complete
14. Reboot.

<p>Login to the machine, update, reboot</p>

```
sudo su
apt update && apt upgrade
reboot
```

