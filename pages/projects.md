---
layout: page
title: "Projects"
permalink: /projects/
---

### Home Lab “KingTech”
Proxmox + VLANs + ZFS; isolated test networks; hardening notes.

### Security+ Notes
Condensed exam notes, ports, and PBQ practice outlines.

### SQL Service Desk
Ticket dataset & queries: SLA/MTTR/backlog trends.

Below are selected projects across cybersecurity, networking, data, web, and cloud. Each card links to a **Demo** and the **Repo**.

<!-- Project grid -->
<div class="projects-grid">

  <!-- KingTech Virtual Lab -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/images/projects/kingtech-lab.jpg" alt="KingTech Virtual Lab" />
    <h3>Proxmox Virtual Lab</h3>
    <p>Homelab built with Proxmox, VLANs, pfSense, and remote access (Tailscale) for enterprise-style testing.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/-Proxmox-E57000?style=for-the-badge&logo=Proxmox&logoColor=white" />
      <img src="https://img.shields.io/badge/-pfSense-212121?style=for-the-badge&logo=pfsense&logoColor=white" />
      <img src="https://img.shields.io/badge/-Tailscale-000000?style=for-the-badge&logo=tailscale&logoColor=white" />
      <img src="https://img.shields.io/badge/-VLANs-5B5B5B?style=for-the-badge" />
    </div>
    <p class="links">
      <a href="https://kingtechs.github.io/Kingtechs/" target="_blank">Demo</a> · 
      <a href="https://github.com/Kingtechs/Kingtechs" target="_blank">Repo</a>
    </p>
  </div>

  <!-- School Tech Metrics Dashboard -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/images/projects/tech-metrics.jpg" alt="School Tech Metrics Dashboard" />
    <h3>School Tech Metrics Dashboard</h3>
    <p>SQL → Power BI pipeline that tracks device uptime, network health, and incident trends. Focus on data cleaning and DAX.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
      <img src="https://img.shields.io/badge/-SQL-336791?style=for-the-badge" />
      <img src="https://img.shields.io/badge/-ETL-444444?style=for-the-badge" />
    </div>
    <p class="links">
      <a href="https://github.com/Kingtechs/Data-Dashboard" target="_blank">Repo</a>
    </p>
  </div>

  <!-- SOC Automation Lab -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/images/projects/soc-automation.jpg" alt="SOC Automation Lab" />
    <h3>SOC Automation Lab</h3>
    <p>Alert triage and enrichment flows with Shuffle SOAR + TheHive for case management and response playbooks.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/-Shuffle%20SOAR-1C1C1C?style=for-the-badge" />
      <img src="https://img.shields.io/badge/-TheHive-FFB000?style=for-the-badge" />
      <img src="https://img.shields.io/badge/-IR%20Playbooks-5B5B5B?style=for-the-badge" />
    </div>
    <p class="links">
      <a href="https://github.com/Kingtechs" target="_blank">Repo</a>
    </p>
  </div>

  <!-- Web Portfolio (.NET + JS) -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/images/projects/web-portfolio.jpg" alt="Web Portfolio" />
    <h3>Web Portfolio (.NET + JS)</h3>
    <p>Responsive GitHub Pages site with custom sections, badges, and dark theme; experimenting with ASP.NET and C# basics.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/-.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/-GitHub%20Pages-181717?style=for-the-badge&logo=github&logoColor=white" />
    </div>
    <p class="links">
      <a href="https://kingtechs.github.io/Kingtechs/" target="_blank">Demo</a> · 
      <a href="https://github.com/Kingtechs/Kingtechs" target="_blank">Repo</a>
    </p>
  </div>

  <!-- Cloud Lab Expansion -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/images/projects/cloud-lab.jpg" alt="Cloud Lab" />
    <h3>Cloud Lab Expansion</h3>
    <p>AWS/Azure experiments for secure VM deployment, storage, and networking; connects back to homelab via Tailscale.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
      <img src="https://img.shields.io/badge/-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
      <img src="https://img.shields.io/badge/-IaC%20(Planned)-5B5B5B?style=for-the-badge" />
    </div>
    <p class="links">
      <a href="https://github.com/Kingtechs" target="_blank">Repo</a>
    </p>
  </div>

  <!-- Packet Tracer Labs -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/images/projects/packet-tracer.jpg" alt="Packet Tracer Labs" />
    <h3>Packet Tracer Labs</h3>
    <p>Routing, VLANs, DHCP, NAT, and site-to-site scenarios; documentation includes diagrams and configs.</p>
    <div class="badges">
      <img src="https://img.shields.io/badge/-Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" />
      <img src="https://img.shields.io/badge/-Nmap-4682B4?style=for-the-badge" />
      <img src="https://img.shields.io/badge/-Wireshark-007ACC?style=for-the-badge&logo=wireshark&logoColor=white" />
    </div>
    <p class="links">
      <a href="https://github.com/Kingtechs" target="_blank">Repo</a>
    </p>
  </div>

</div>

<!-- Tip for images -->
> 💡 Put screenshots in `assets/images/projects/` and reference them as  
> `{{ site.baseurl }}/assets/images/projects/<file>.jpg` so paths work on your project site.

