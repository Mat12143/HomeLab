This project contains all the configuration files that make up my Homelab

> **But wait a moment, what is a Homelab?**
> 
> A Homelab is the name given to a server (or multiple server setup) that resides locally in your home and where you host several applications and virtualized systems for testing and developing or for home and functional usage
> https://linuxhandbook.com/homelab/
# Future Plans
- [ ] Automatic OS Install
- [ ] Strong Backup solution
- [ ] Passive Cooling for the Pi
# Overview
## ⚙️ Hardware
I am currently running a ```Rasberry Pi 4B (4GB Model)```

I added a fan to cool the PI, but in the future I want to buy some heat pipes to get some passive cooling too

**Is it the best solution?**
For my present use case it is more than enough computing power for what I am currently running. Power consumption, also, is very important for me, so going with a power hungry old desktop pc, was a no go, especially when I had a Rasbperry Pi 4 taking dust
## 📦 Services
I am currently running a few Docker Containers. All the configurations are in the [docker-compose.yml](https://github.com/Mat12143/HomeLab/blob/main/docker-compose.yaml)

> All the Containers Mount Points points to the [dockerData](https://github.com/Mat12143/HomeLab/blob/main/dockerData) folder
## [Homepage](https://github.com/gethomepage/homepage)
A simple and minimal homepage with some information about the hardware status and containers health, with some cool services stats

![](https://github.com/Mat12143/HomeLab/blob/main/docs/img/homepage.png)
## [PiHole](https://github.com/pi-hole/docker-pi-hole)
Network-wide AD Blocking services through DNS

![](https://github.com/Mat12143/HomeLab/blob/main/docs/img/pihole.png)
## [UptimeKuma](https://github.com/louislam/uptime-kuma)
Self hosted alternative to UptimeRobot, to monitor my Virtual Private Servers and other services

![](https://github.com/Mat12143/HomeLab/blob/main/docs/img/uptimeKuma.png)
## [TailScale](https://tailscale.com)
I use Tailscale ZeroTier VPN to remote into my server from outside the network
