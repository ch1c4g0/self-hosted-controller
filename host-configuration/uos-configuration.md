

<p><h1>Install dependancies</h1></p>

```
sudo apt install podman slirp4netns crun uidmap dbus-user-sessions
```

<p><h1>Download UOS</h1></p>

<p>Go to the download page below, then use wget or curl to retrieve it.</p>

https://fw-download.ubnt.com/data/unifi-os-server/b828-linux-x64-5.1.19-e38d0b0e-b462-403d-9861-f57f25772106.19-x64

```
wget https://fw-download.ubnt.com/data/unifi-os-server/b828-linux-x64-5.1.19-e38d0b0e-b462-403d-9861-f57f25772106.19-x64
```

<p><h2>Make the installer executeable</h2></p>

```
chmod +x <path-to-file>
```

<p><h2>Run the installer</h2></p>

```
sudo ./path-to-installer
```

<p>I ended up having to resize my disk as there wasn't enough free space after installing dependancies.</p>
