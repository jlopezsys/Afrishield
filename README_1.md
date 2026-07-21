<div align="center">

# 🛡️ AfriShield

### The blue team's browser-native operations console

**12 tools for SOC analysts & DFIR responders — in a single HTML file.**
No sign-up. No backend. Nothing ever leaves your machine.

[**▶ Live demo**](https://jlopezsys.github.io/Afrishield/) · [Report an issue](https://github.com/jlopezsys/Afrishield/issues)

</div>

---

## What is this?

AfriShield is a self-contained security operations toolkit that runs entirely in your browser. Open the page (or the single `index.html` file) and you have everything an analyst reaches for during a shift — no installation, no accounts, no data ever sent anywhere. That last part matters: because there's no backend, it's safe to paste sensitive internal data into it.

## The tools

| Tool | What it does |
|------|--------------|
| **⊞ IOC Extractor** | Pull every IP, domain, URL, hash, CVE, BTC address & registry key from any text; auto-defang for reports |
| **◎ Reputation Launcher** | One indicator → instant lookups across 16 OSINT engines (VirusTotal, Shodan, OTX, URLScan, AbuseIPDB…) |
| **⇄ Multi-Decoder** | Base64, Hex, URL, Unicode, ROT13, defang/refang — auto-detects PowerShell payloads |
| **⚙ Query Builder** | Generate KQL / SPL / Sigma from a few choices, no syntax required |
| **⌕ Hunt Library** | 30 detection queries mapped to MITRE ATT&CK, in three dialects, searchable by intent |
| **✉ Email Analyzer** | Check SPF/DKIM/DMARC, trace relay chain, flag spoofing, extract IOCs from headers |
| **◆ Alert Triage** | Score any alert for severity, SLA & escalation in five questions |
| **☑ IR Checklist** | NIST-aligned response steps for 5 incident types, with progress tracking & export |
| **📊 KPI Reporter** | Turn shift numbers into SOC metrics (FP rate, MTTD/MTTR) and export a report |
| **⛃ Evidence Guide** | What to collect by platform, ordered by volatility, with chain-of-custody |
| **◷ Timeline Builder** | Assemble a chronological incident timeline and export a full case report |

## Why it's different

- **100% local** — no server, no telemetry, no accounts. Works offline.
- **Single file** — one `index.html` you can host anywhere or run from disk.
- **Built by an analyst** — the workflows come from real SOC/DFIR daily work.
- **Free & open-source** — MIT licensed. Fork it, improve it, make it yours.

## Run it

**Option A — just open it**
Download `index.html` and double-click. That's it.

**Option B — host it (GitHub Pages)**
1. Fork this repo
2. Settings → Pages → deploy from `main`
3. Your copy is live at `https://<you>.github.io/Afrishield`

## Privacy

There is no backend. Text you paste, numbers you enter, and files you build are processed in your browser and never transmitted. The only network activity is when *you* click an external reputation link, which opens that provider directly.

## Roadmap

- More detection queries and data sources
- Additional decoders and IOC types
- Optional light theme
- Community-contributed hunt queries

Contributions welcome — open an issue or a PR.

## License

MIT © [Joel López Tébar](https://www.linkedin.com/in/joellopeztebar)

---

<div align="center">

Built for blue teams by **[Joel López Tébar](https://www.linkedin.com/in/joellopeztebar)** ·
If AfriShield helps you, a ⭐ goes a long way.

</div>
