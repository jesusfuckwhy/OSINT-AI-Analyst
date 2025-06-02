# OSINT-AI-Analyst
# OSINT AI Analyst   **Next-gen open-source intelligence powered by artificial reasoning.**

## 🌐 Overview
This project builds a local AI agent capable of:
- Collecting public intelligence from online sources
- Sifting, de-duplicating, and organizing data
- Generating actionable OSINT reports with context

> Ideal for cybersecurity, disinformation tracking, and investigative journalism.

---

## 🧠 Features
- 🔍 Domain & WHOIS pattern matching
- 📊 Report generation (Markdown, PDF, STIX)
- 🧰 Integration with tools like DomainTools, VirusTotal, and Wayback
- 🕸️ Detection of disinfo/ransomware infrastructure
- 📦 Fully local inference (optional)

---

## 🚀 Getting Started
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/osint-ai.git
cd osint-ai

# Install dependencies
pip install -r requirements.txt

# Run the agent
python run_agent.py
```

---

## 🔧 How It Works
1. **Collection**: Scrapes targets from OSINT feeds, domain dumps, or passive DNS
2. **Enrichment**: Resolves WHOIS, IP, ASN, historical metadata
3. **Analysis**: Correlates patterns and generates analyst-friendly reports
4. **Report Generation**: Exports HTML, Markdown, and optionally PDF
