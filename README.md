# Awesome-Cybersecurity-Links
Curated list of cybersecurity resources (Blue, Red, Purple, TI, CTFs, Tools, Blogs)


awesome-cybersecurity-links/
├── README.md
├── CONTRIBUTING.md
├── LICENSE (MIT)
├── docs/
│   ├── blue-team.md
│   ├── red-team.md
│   ├── purple-team.md
│   ├── threat-intel.md
│   ├── ctfs.md
│   ├── blogs.md
│   └── tools.md
└── .github/
    └── ISSUE_TEMPLATE.md

---

README.md

```markdown
# Awesome Cyber Security Links

A curated list of Cyber Security resources for Blue Team, Red Team, Threat Intelligence, CTFs, and more — inspired by [DXC-0/SOC-Ressources](https://github.com/DXC-0/SOC-Ressources).

> 📚 This repository is built for professionals, researchers, and learners who want a central place to bookmark valuable links and references.

---

## 🧭 Categories

- [🔵 Blue Team Resources](docs/blue-team.md)
- [🔴 Red Team Resources](docs/red-team.md)
- [🟣 Purple Team Resources](docs/purple-team.md)
- [🕵️ Threat Intelligence](docs/threat-intel.md)
- [🎯 Capture The Flag (CTF)](docs/ctfs.md)
- [🧰 Tools & Frameworks](docs/tools.md)
- [📰 Cyber Security Blogs](docs/blogs.md)

---

## 📌 Contributing

Want to contribute a new resource? Check [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📄 License

MIT License – See [LICENSE](LICENSE)
```

---

CONTRIBUTING.md

```markdown
# Contribution Guide

We welcome contributions! To add a new resource:

1. Fork this repo
2. Add your link to the appropriate category in `/docs`
3. Submit a Pull Request

Please ensure:
- The link is **relevant and useful**
- It has a **short description**
- The resource is **freely accessible**

Thank you! 🙌
```

---

docs/blue-team.md

```markdown
# 🔵 Blue Team Resources

Resources for SOC analysts, detection engineers, defenders, and incident responders.

## 📘 Detection Engineering
- [Sigma Rules](https://github.com/SigmaHQ/sigma) – Generic signature format for SIEM systems.
- [Elastic Detection Rules](https://github.com/elastic/detection-rules) – Rules for Elastic SIEM.

## 📊 SIEM & Logging
- [Wazuh](https://wazuh.com/) – Open source XDR and SIEM platform.
- [OpenSearch Security Analytics](https://opensearch.org/) – Elastic-like open-source SIEM.

## 🔍 Threat Hunting
- [ThreatHunting Project](https://github.com/ThreatHuntingProject/ThreatHunting) – Templates and guides for threat hunting.
- [Hunting ELK](https://github.com/0xrawsec/Hunting-ELK) – ELK stack for hunting.

## 🛠️ Useful Tools
- [Arkime](https://arkime.com/) – Network packet capture and analysis tool.
- [Velociraptor](https://www.velociraptor.app/) – Endpoint visibility and DFIR tool.
```

---

docs/red-team.md

```markdown
# 🔴 Red Team Resources

Resources for ethical hackers, pentesters, and adversary simulation.

## 🧠 Frameworks
- [MITRE ATT&CK](https://attack.mitre.org/) – Tactics and techniques used by threat actors.
- [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) – Small, focused test cases mapped to MITRE.

## 🛠️ Tools
- [Cobalt Strike](https://www.cobaltstrike.com/) – Commercial adversary simulation.
- [Sliver](https://github.com/BishopFox/sliver) – Open-source C2 framework.
- [Empire](https://github.com/BC-SECURITY/Empire) – Post-exploitation and C2 tool.

## 📚 Learning Labs
- [TryHackMe](https://tryhackme.com/)
- [Hack The Box](https://www.hackthebox.com/)
```

---

docs/purple-team.md

```markdown
# 🟣 Purple Team Resources

Bridging the gap between offensive and defensive security teams.

## 🔁 Adversary Simulation
- [MITRE Caldera](https://github.com/mitre/caldera) – Automated adversary emulation.
- [Stratus Red Team](https://github.com/DataDog/stratus-red-team) – Adversary simulation for cloud.

## 📦 Tool Integration
- [DetectionLab](https://github.com/clong/DetectionLab) – Lab for blue team testing.
- [Prelude Operator](https://www.prelude.org/) – Security automation platform.
```

---

docs/threat-intel.md

```markdown
# 🕵️ Threat Intelligence Resources

Resources for threat intel analysts and defenders.

## 🔎 Feeds & Aggregators
- [Abuse.ch](https://abuse.ch/) – Threat intel feeds for malware, botnets, etc.
- [AlienVault OTX](https://otx.alienvault.com/) – Open threat exchange.
- [MISP](https://github.com/MISP/MISP) – Threat intelligence sharing platform.

## 📊 Dashboards
- [ThreatFox](https://threatfox.abuse.ch/) – IOC aggregator.
```

---

docs/ctfs.md

```markdown
# 🎯 Capture The Flag (CTF)

Resources and platforms for playing, learning, and hosting CTFs.

## 🌍 Platforms
- [CTFtime](https://ctftime.org/) – Global calendar and rating.
- [PicoCTF](https://picoctf.org/) – Beginner-friendly CTF by Carnegie Mellon.
- [Root Me](https://www.root-me.org/) – Platform with challenges in multiple categories.

## 🛠️ Tools
- [pwntools](https://github.com/Gallopsled/pwntools) – CTF framework and exploit development.
```

---

docs/blogs.md

```markdown
# 📰 Cyber Security Blogs

Recommended blogs from researchers, companies, and the community.

## 🧑‍💻 Personal Blogs
- [Daniel Miessler](https://danielmiessler.com/blog/) – Security, infosec, and tech culture.
- [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/) – Traffic captures & analysis exercises.

## 🏢 Company Blogs
- [Elastic Security Blog](https://www.elastic.co/security-labs)
- [CrowdStrike Blog](https://www.crowdstrike.com/blog/)
- [Red Canary Blog](https://redcanary.com/blog/)
```

---

docs/tools.md

```markdown
# 🧰 Tools & Frameworks

A selection of useful cybersecurity tools for various domains.

## 🔍 Blue Team
- [Arkime](https://arkime.com/) – Full-packet capture.
- [Wazuh](https://wazuh.com/) – SIEM & XDR.

## 🔴 Red Team
- [Sliver](https://github.com/BishopFox/sliver)
- [Metasploit](https://metasploit.help.rapid7.com/)

## 🧠 Threat Intel
- [MISP](https://github.com/MISP/MISP)
- [Yeti](https://github.com/yeti-platform/yeti)
```

---

.github/ISSUE_TEMPLATE.md

```markdown
# Resource Suggestion Template

**Title:**

**Link:**

**Category (Blue/Red/Purple/CTF/Blog/Tool):**

**Short Description:**

**Why it should be included:**

Thank you for your suggestion! 🙌
```

---

LICENSE

Use the [MIT License](https://choosealicense.com/licenses/mit/) (copy from GitHub template).
