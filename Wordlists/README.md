# 📑 Wordlists

This folder contains custom and curated wordlists for recon, fuzzing, and exploitation.

## 🧾 Categories

### 📁 Directory & File Fuzzing
- SecLists/Discovery/Web-Content
- raft-large-directories.txt
- Apache/Nginx default files

### 🧪 Parameter Discovery
- Common param names: `id`, `page`, `redirect`, `url`, `lang`, `debug`, etc.
- Tools: Arjun-generated lists, PayloadsAllTheThings/Parameters

### 🌐 Subdomain Enumeration
- [dns-Jhaddix.txt](https://github.com/notnotmike/seclists/blob/master/Discovery/DNS/dns-Jhaddix.txt)
- [bitquark-subdomains-top100000](https://github.com/bitquark/dnspop)
- All.txt from assetnote or compiled from bug bounty targets

### 📜 API & JSON Keys
- `token`, `access_token`, `auth`, `api_key`, `session`, `user_id`

### 🧩 JavaScript Variables & Endpoints
- Extracted from custom targets
- Custom generated from `gau`, `waybackurls`, and `JSParser`

---

## 🛠 How I Build My Own Wordlists

- Crawl known endpoints with `katana` or `hakrawler`
- Extract JS files → run `LinkFinder` or `JSExtract`
- Collect from Burp Suite → sort → dedupe
- Filter with `gf` and keyword matching

*Custom wordlists = higher quality results = better bugs.*
