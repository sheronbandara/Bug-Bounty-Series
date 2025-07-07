# 🔎 Recon Notes

This folder contains detailed notes on reconnaissance — the first and most crucial phase of bug bounty hunting.

## 🔧 Categories of Recon

### 1. 🔍 Subdomain Enumeration

**Passive Tools:**
- [Subfinder](https://github.com/projectdiscovery/subfinder)
- [Assetfinder](https://github.com/tomnomnom/assetfinder)
- [crt.sh](https://crt.sh/)
- [Certspotter](https://github.com/SSLMate/certspotter)
- [Amass (Passive mode)](https://github.com/owasp-amass)

**Active Tools:**
- [Amass](https://github.com/owasp-amass)
- [dnsx](https://github.com/projectdiscovery/dnsx)
- [massdns](https://github.com/blechschmidt/massdns)
- [Sublist3r](https://github.com/aboul3la/Sublist3r)

### 2. 🌐 URL & Endpoint Discovery

- [waybackurls](https://github.com/tomnomnom/waybackurls)
- [gau (GetAllURLs)](https://github.com/lc/gau)
- [hakrawler](https://github.com/hakluke/hakrawler)
- [katana](https://github.com/projectdiscovery/katana)
- [paramspider](https://github.com/devanshbatham/paramspider)
- [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder)

### 3. 🧪 Parameter & Input Discovery

- [Arjun](https://github.com/s0md3v/Arjun) – Detect GET & POST parameters
- [gf](https://github.com/tomnomnom/gf) – Pattern-based filtering
- Custom parameter lists from Burp/JS analysis

### 4. 📦 File & Directory Bruteforcing

- [ffuf](https://github.com/ffuf/ffuf)
- [dirsearch](https://github.com/maurosoria/dirsearch)
- [feroxbuster](https://github.com/epi052/feroxbuster)

### 5. 🛠 JavaScript Recon

- [LinkFinder](https://github.com/GerbenJavado/LinkFinder)
- [JSParser](https://github.com/nahamsec/JSParser)
- Manual analysis in DevTools > Sources

### 6. 📸 Visual Recon

- [gowitness](https://github.com/sensepost/gowitness)
- [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness)
- [aquatone](https://github.com/michenriksen/aquatone)

---

## 📌 Tips & Best Practices

- Automate but always validate manually.
- Combine passive and active recon for full coverage.
- Use your own custom wordlists built from target's content.
- Continuously monitor targets using tools like `notify` or `github-search`.

Stay tuned for real recon case studies from my own bounty experience!
