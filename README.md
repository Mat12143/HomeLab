This project contains all the configuration files that make up my Homelab

> **But wait a moment, what is a Homelab?**
>
> A Homelab is the name given to a server (or multiple server setup) that resides locally in your home and where you host several applications and virtualized systems for testing and developing or for home and functional usage
> https://linuxhandbook.com/homelab/

# Future Plans

- [ ] Automatic OS Install
- [ ] Strong Backup solution
- [ ] Replace the HDD with a SSD

# Overview

## Hardware

I am currently running a `Laptop with an Intel i5-8250U, 8GB of Ram, 500GB HDD`

**Is it the best solution?**
For my present use case it is more than enough computing power for what I am currently running. Power consumption, also, is very important for me, so going with a power hungry old desktop pc, was a no go, especially when I had a "Old" Laptop laying around taking dust

## 📦 Services

I am currently running a few Docker Containers. All the configurations are in the [compose.yml](https://github.com/Mat12143/HomeLab/blob/main/compose.yaml)

## [Homepage](https://github.com/gethomepage/homepage)

A simple and minimal homepage with some information about the hardware status and containers health, with some cool services stats

![](https://github.com/Mat12143/HomeLab/blob/main/docs/img/homepage.png)

## [PiHole](https://github.com/pi-hole/docker-pi-hole)

Network-wide AD Blocking services through DNS

![](https://github.com/Mat12143/HomeLab/blob/main/docs/img/pihole.png)

## Backrestic

A Web UI for the restic backup solution

![](https://github.com/Mat12143/HomeLab/blob/main/docs/img/uptimeKuma.png)

## [TailScale](https://tailscale.com)

I use Tailscale ZeroTier VPN to remote into my server from outside the network
