# SOC Analyst Prep — Interactive Learning Tool

An interactive single-file HTML tool to prepare for a **SOC Analyst L1 technical assessment**.  
No installation, no dependencies — just open the file in any browser.

🇮🇹 Italian version: `soc-analyst-prep-IT.html`  
🇬🇧 English version: `soc-analyst-prep-EN.html`

---

## What's inside

| Section | Description |
|---|---|
| **How triage works** | Full triage theory: flow, questions to ask, when to escalate |
| **OSI Model** | Table with examples + 2 interactive exercises (order layers / guess the layer) |
| **CIDR Trainer** | Speed round (14 CIDR values) + full subnet calculator |
| **TCP vs UDP Trainer** | 14 realistic scenarios — click TCP or UDP |
| **SOC Triage Scenarios** | 6 realistic scenarios — manually order the response steps |
| **MITRE ATT&CK** | All 14 tactics with key techniques + assessment phrase |
| **100 Ports** | Filterable table (web, mail, remote, file, db, network, security, Windows, dangerous) |
| **Module Quiz** | 6 modules × 8 questions with explanations |
| **Final Test** | 12 random questions with 20-second countdown timer |
| **Final Checklist** | Questions they'll ask + checklist of what to do |

---

## Triage scenarios covered

1. Brute force VPN + successful login from anomalous country
2. User-reported phishing email with attachment
3. EDR C2 beacon alert on endpoint
4. Anomalous RDP access at 3 AM on production server
5. Suspected DNS tunneling (200+ queries/min to random subdomains)
6. Password spray on Active Directory (1 failure × 300 accounts)

Each scenario requires you to **manually order the correct response steps** — exactly what you'll be asked to do in a technical assessment.

---

## How to use

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/soc-analyst-prep.git

# Open in browser
open soc-analyst-prep-EN.html        # macOS
xdg-open soc-analyst-prep-EN.html   # Linux
start soc-analyst-prep-EN.html      # Windows
```

Or just **download the HTML file** and double-click it.

---

## Features

- ✅ 100% offline — zero external dependencies (except Google Fonts)
- ✅ Progress saved automatically in `localStorage`
- ✅ Dark / light theme toggle
- ✅ Mobile responsive
- ✅ OSI exercises shuffle on every reset
- ✅ Timed final test (20s per question)

---

## Topics covered

**Networking:** OSI 7 layers, TCP vs UDP, subnetting CIDR, NAT, DNS, DHCP, ARP  
**SOC Operations:** Alert triage, SIEM, EDR, escalation L1→L2→L3, phishing response, malware containment  
**Security:** Firewall types, IDS/IPS, VPN, symmetric/asymmetric encryption, hashing, MFA, AAA  
**Threats:** Malware types, phishing/spear phishing, MITM, password spray, SQL injection, DDoS, lateral movement, DNS tunneling  
**Linux:** tail, grep, chmod, chown, netstat, ps, iptables, nslookup  
**SOC & IR:** MITRE ATT&CK, MDR vs MSSP, NIST IR lifecycle, SOAR, Threat Intelligence feeds  

---

## Contributing

PRs welcome. If you want to add:
- More triage scenarios
- More quiz questions
- Translations to other languages
- Additional port entries

---

## License

MIT — free to use, share and modify.

---

*Built to help anyone break into cybersecurity. Keep learning and stay sharp.*
