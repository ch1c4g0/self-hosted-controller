

<p><h1>Operating System,</h1></p>

<p>Documentation states that UOS runs best on Ubuntu/Debian.<br>
I chose to use Ubuntu Server 24.04LTS as it has the best reviews within the community.</p>

<p><h2>Resource Requirements</h2></p>

**<p>For large networks, I would double the units below.</p>**

1. x86-64 CPU
2. 2 vCPUs
3. 4GB of RAM
4. 25GB of free disk space

<p>Podman 4.3.1+ is also required to handle containerized services natively.</p>

<p><h1>Network Requirements,</h1></p>

1. Configure static-ip on the same subnet as your UniFi devices.
2. Allow TCP ports 8080, 443, and UDP port 3478 (for STUN)
