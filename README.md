# VPS_OpenWrt
![GitHub Stars](https://img.shields.io/github/stars/VPN-V2Ray/VPS_OpenWrt.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/VPN-V2Ray/VPS_OpenWrt.svg?style=flat&logo=appveyor&label=Forks&logo=github)
![GitHub last commit](https://img.shields.io/github/last-commit/VPN-V2Ray/VPS_OpenWrt?label=Latest%20Commit&logo=github)

This repo helps to deploy OpenWrt onto your VPS.<br>
Hereby thank `ptpt52` for his amazing job: https://github.com/x-wrt<br>


**Prerequisite**
 - **`Ubuntu`** or **`Debian`** (CentOS/ArchBase Not tested)
 - **`wget`** installed<br>

   `apt update && apt install -y wget` 

**Steps**

1.  Upload OpenWrt firmware(WinSCP or prefer), rename it to `op.img.gz` 
2.  Run: `bash -c "$(wget -O- https://git.io/openwrtvps)"`
 
**Support Platform :**
- Google Cloud
- Azure
- Vultr
- Virmach
- Racknerd
- Hostdare
- Ali Cloud (Domestic)
- ...

**`NOT` Support Platform :**
- ...
