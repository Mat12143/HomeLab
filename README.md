This project contains all the configuration files that make up my HomeLab

# Future Plans

- [ ] Automatic OS Install
- [ ] Strong Backup solution
- [ ] Replace the HDD with a SSD

# Overview

## 💻 Hardware

I am currently running a `Laptop with an Intel i5-8250U, 8GB of Ram, 500GB HDD` running `Debian 12`

**Is it the best solution?**
For my present use case it is more than enough computing power for what I am currently running. Power consumption, also, is very important for me, so going with a power hungry old desktop pc, was a no go, especially when I had a "Old" Laptop laying around taking dust

## 📦 Services

I am currently running a few Docker Containers. All the configurations are in the [compose.yml](https://github.com/Mat12143/HomeLab/blob/main/compose.yaml)

### Containers
- 🛜 **AdGuard Home**: for DNS Network wide AD-Blocking
- 📃 **Silverbullet.md**: for taking my notes in markdown
- 🔔 **Diun**: for sending me a notification when a new container version releases
- 🏠 **Homepage**: a simple HomeLab homepage
- ↔️ **Caddy**: reverse proxy + SSL cert manager
