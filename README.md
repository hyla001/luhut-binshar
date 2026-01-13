# 🛡️ LUHUT BINSHAR

**Security Testing Payload Repository**

Koleksi payload untuk penetration testing yang terorganisir dan mudah digunakan.

## 📦 Categories

| Category | Description | Count |
|----------|-------------|-------|
| XSS | Cross-Site Scripting | 25+ |
| SQLi | SQL Injection | 25+ |
| SSRF | Server-Side Request Forgery | 15+ |
| LFI | Local File Inclusion | 13+ |
| RFI | Remote File Inclusion | 8+ |
| CMDi | Command Injection | 16+ |
| SSTI | Server-Side Template Injection | 13+ |
| Open Redirect | URL Redirect | 10+ |
| CSRF | Cross-Site Request Forgery | 9+ |

## 🔧 Structure

```
luhut-binshar/
├── index.json          # Category index
├── version.json        # Version info
├── payloads/
│   ├── xss.json
│   ├── sqli.json
│   ├── ssrf.json
│   ├── lfi.json
│   ├── rfi.json
│   ├── cmdi.json
│   ├── ssti.json
│   ├── open_redirect.json
│   └── csrf.json
└── schemas/
    └── payload.schema.json
```

## 📥 Installation

### Browser Extension
1. Download extension dari [Releases](releases)
2. Chrome: `chrome://extensions` → Enable Developer Mode → Load Unpacked
3. Firefox: `about:debugging` → Load Temporary Add-on

### Direct Download
```bash
git clone https://github.com/YOUR_USERNAME/luhut-binshar.git
```

## ⚠️ Disclaimer

**For authorized security testing only.** Use responsibly and only on systems you have permission to test.

## 📄 License

MIT License
