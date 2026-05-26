<h1 align="center">Aden Brady</h1>

<p align="center">
  <em>Systems &amp; Infrastructure Engineer · Homelab tinkerer · UCF IT (B.S. '26)</em>
</p>

<p align="center">
  <a href="https://banani.dev"><img src="https://img.shields.io/badge/Portfolio-banani.dev-2ea44f?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/aden-brady"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Status-online_%2F_available-success?style=for-the-badge" alt="Status">
</p>

---

### whoami

```bash
aden@archive:~$ whoami
```

I'm a Computer Systems Support Analyst at the **City of Orlando**, with two years of prior
enterprise infrastructure work on **UCF IT's virtualization and systems team**. My thing is
hands-on work with the technology that keeps everything running: VMware environments, Windows
and Linux servers, Active Directory, and Dell hardware.

Infrastructure by day, homelab by night. I run a personal server (**BananiServer**) to keep
learning hands-on, competed in cyber defense through Hack@UCF, and earned the rank of Eagle Scout.

There's a fuller writeup, an interactive homelab status board, and a command palette over at
**[banani.dev](https://banani.dev)**.

---

### What I Work With

**Virtualization**
<p>
  <img src="https://img.shields.io/badge/VMware_vSphere-607078?style=flat-square&logo=vmware&logoColor=white">
  <img src="https://img.shields.io/badge/ESXi-607078?style=flat-square&logo=vmware&logoColor=white">
  <img src="https://img.shields.io/badge/vSAN-607078?style=flat-square&logo=vmware&logoColor=white">
</p>

**Systems &amp; Directory**
<p>
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Ubuntu_Server-E95420?style=flat-square&logo=ubuntu&logoColor=white">
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Group_Policy-0078D4?style=flat-square&logo=windows&logoColor=white">
</p>

**Storage &amp; Self-Hosting**
<p>
  <img src="https://img.shields.io/badge/TrueNAS_SCALE-0095D5?style=flat-square&logo=truenas&logoColor=white">
  <img src="https://img.shields.io/badge/ZFS_/_RAID--Z-3A4D54?style=flat-square&logo=openzfs&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Vaultwarden-175DDC?style=flat-square&logo=bitwarden&logoColor=white">
</p>

**Networking &amp; Security**
<p>
  <img src="https://img.shields.io/badge/Pi--hole-96060C?style=flat-square&logo=pi-hole&logoColor=white">
  <img src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white">
  <img src="https://img.shields.io/badge/DNS-4A90D9?style=flat-square&logo=cloudflare&logoColor=white">
  <img src="https://img.shields.io/badge/VLANs-1B998B?style=flat-square&logo=ubiquiti&logoColor=white">
</p>

**Development**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
</p>

**Tools &amp; Platforms**
<p>
  <img src="https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&logo=servicenow&logoColor=white">
  <img src="https://img.shields.io/badge/Uptime_Kuma-5CDD8B?style=flat-square&logo=uptimekuma&logoColor=black">
  <img src="https://img.shields.io/badge/Netdata-00AB44?style=flat-square&logo=netdata&logoColor=white">
  <img src="https://img.shields.io/badge/Portainer-13BEF9?style=flat-square&logo=portainer&logoColor=white">
</p>

---

### Featured Projects

| Project | What it is | Stack |
|---------|-----------|-------|
| [**NAS-Build-2025**](https://github.com/abrady-dev/NAS-Build-2025) | BananiServer — a home server on TrueNAS SCALE with RAID-Z1 redundancy, a Docker stack (Vaultwarden, nginx-proxy-mgr, Tailscale, and more), and zero exposed ports thanks to Tailscale. | TrueNAS · ZFS · Docker · Tailscale |
| [**Scrubbed**](https://github.com/muzamil-dev/leave-me-on-a-deserted-island) | A self-hosted tool that discovers your profiles across 12+ data brokers and automates opt-out requests with Playwright, including IMAP confirmation handling and scheduled re-sweeps. React dashboard + terminal UI. | Node · TypeScript · Playwright · SQLite |
| **ServiceNow VM Analytics** | A Python pipeline that pulls 3,200+ closed VM Request Items from the ServiceNow API, enriches them with task-level data, and outputs metrics and charts for the infra team. | Python · ServiceNow API · OAuth · matplotlib |
| [**MyGameList**](https://github.com/zaid-hasan-ucf/cis4004termproject) | A full-stack game tracker inspired by MyAnimeList — catalog, rate, and track games in a personal library. Built from scratch including DB config and seed scripting. | MongoDB · Express · React · Node |
| [**Tyler Brown Photography**](https://tylerbrownphoto.com/) | A freelance multi-page photography portfolio with a filterable gallery, lightbox viewer, scroll animations, and responsive nav. | HTML · CSS · JavaScript |

---

### Network Security with Pi-hole

Beyond the NAS, I run a Pi-hole DNS sinkhole on a dedicated Raspberry Pi covering 12+ devices,
cutting tracking and malicious domain requests by ~35%. It's the primary resolver for the whole
network, with custom blocklists and regular query-log analysis to catch suspicious traffic.

---

### A Few Things I'm Proud Of

- **Eagle Scout** — Boy Scouts of America (service project for a local greyhound adoption center)
- **Top-5 finish** at Hack@UCF's Horse Plinko Cyber Defense Competition, defending live systems against red-team attacks
- **B.S. in Information Technology**, UCF — Class of 2026, EXCEL Scholar
- Certs: **Microsoft Office Expert** · **TestOut IT Fundamentals Pro** · **AWS Cloud Security Foundations**

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abrady-dev&show_icons=true&theme=tokyonight&hide_border=true" alt="Aden's GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abrady-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="165">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abrady-dev&theme=tokyonight&hide_border=true" alt="GitHub streak">
</p>

---

### Let's Connect

<p align="center">
  <a href="https://banani.dev"><img src="https://img.shields.io/badge/Website-banani.dev-2ea44f?style=for-the-badge&logo=google-chrome&logoColor=white"></a>
  <a href="https://linkedin.com/in/aden-brady"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:aden.brady@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<p align="center">
  <em>"It works on my server." — me, probably</em>
</p>
