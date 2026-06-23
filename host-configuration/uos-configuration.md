

<p><h1>Install dependancies</h1></p>

```
sudo apt install podman slirp4netns
```

<p><h1>Download UOS</h1></p>

<p>Go to the download page below, then use wget or curl to retrieve it.</p>

https://fw-download.ubnt.com/data/unifi-os-server/b828-linux-x64-5.1.19-e38d0b0e-b462-403d-9861-f57f25772106.19-x64

```
wget https://fw-download.ubnt.com/data/unifi-os-server/b828-linux-x64-5.1.19-e38d0b0e-b462-403d-9861-f57f25772106.19-x64
```

<p><h2>Make the installer executeable</h2></p>

```
chmod +x <path-to-installer>
```

<p><h2>Run the installer</h2></p>

```
sudo ./path-to-installer
```

<p><h1>Accessing the Web-UI</h1></p>

<p>After running the installer, if successful, a prompt will appear in your CLI.</p>

```
Unifi OS Server is running at: https://000.000.000.000:11443/
```

**<p>I'd recommend you also add your local user to the UOS group on the server so you can perform commands locally.</p**

```
usermod -aG uosserver username
```

