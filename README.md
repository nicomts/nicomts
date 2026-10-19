<h1 align="center">Nicolás Morales</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to-NOC_%C2%B7_Sysadmin_%C2%B7_Infrastructure_%C2%B7_SOC-2EA44F?style=flat-square" alt="Open to NOC, sysadmin, infrastructure and SOC roles">
  <img src="https://img.shields.io/badge/Based_in-Concepci%C3%B3n_del_Uruguay%2C_AR-75AADB?style=flat-square" alt="Based in Concepción del Uruguay, Argentina">
  <img src="https://img.shields.io/badge/Languages-Spanish_(Native)_%C2%B7_English_(Advanced)-8A2BE2?style=flat-square" alt="Spanish (Native), English (Advanced)">
</p>

Final-year Information Systems Engineering student at UTN FRCU (Argentina).
I work with Linux, networking and infrastructure, and I'm looking for my first role in NOC, sysadmin, infrastructure or SOC, on-site in Concepción del Uruguay or remote.

I learn by building things and writing down what broke and how I fixed it.

## 🔧 What I'm working on

### [homelab](https://github.com/nicomts/homelab)

Proxmox lab on my old PC, isolated from my home network behind an OPNsense firewall: Ubuntu and Rocky Linux servers, a clients VLAN, weekly backups I've actually restored, and two MikroTik CHR branch routers joined by a WireGuard tunnel. Every phase has writeups with the design decisions, what went wrong, and how I fixed it.

![Progress](https://img.shields.io/badge/progress-phases_1--4_done-E57000?style=flat-square)
![Next](https://img.shields.io/badge/next-break--and--fix_incidents-lightgrey?style=flat-square)
![Last update](https://img.shields.io/github/last-commit/nicomts/homelab?style=flat-square&label=last%20update)

Some things I ran into:

- [A Samba share that SELinux blocked](https://github.com/nicomts/homelab/blob/main/writeups/04-samba-vs-selinux.md): traced a "permission denied" with correct Unix permissions to an SELinux label, and fixed it in the policy instead of turning SELinux off.
- [Two Linux servers, one baseline](https://github.com/nicomts/homelab/blob/main/writeups/03-linux-server-baseline.md): found that my `sshd_config` change wouldn't have disabled password logins, because an installer file set it first and `sshd` keeps the first value.
- [Backups I actually restored](https://github.com/nicomts/homelab/blob/main/writeups/05-vm-backup-and-restore.md): deleted a VM and restored it from an external disk in about 6 minutes, with the same IP and SSH host key.

### [sadservers-writeups](https://github.com/nicomts/sadservers-writeups)

Solutions to SadServers troubleshooting scenarios, explaining the reasoning, not just the commands.

![Last update](https://img.shields.io/github/last-commit/nicomts/sadservers-writeups?style=flat-square&label=last%20update)

## 🧰 Toolbox

**Virtualization & networking**

![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-E44A20?style=for-the-badge&logo=opnsense&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)

**Operating systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/Rocky_Linux-10B981?style=for-the-badge&logo=rockylinux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)

**Services & security**

![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Samba](https://img.shields.io/badge/Samba-3F6EA8?style=for-the-badge)
![SELinux](https://img.shields.io/badge/SELinux-CC0000?style=for-the-badge)

**Tools**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F03C2E?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=for-the-badge&logo=tmux&logoColor=white)

## 🔭 Next up

Infrastructure as code for the homelab (Packer, Terraform, Ansible), then Windows Server and Active Directory, then CI and GitOps on k3s.

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nmorales--li-0A66C2?style=for-the-badge)](https://linkedin.com/in/nmorales-li)
[![Email](https://img.shields.io/badge/Email-nicolasmorales.it%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nicolasmorales.it@gmail.com)
