# 📂 LUHUT BINSHAR - Payload Database

> **Repository ini adalah database payload untuk extension [PELURU LUHUT](https://github.com/hyla001/payload-extension).**

---

## ⚠️ Penting: Kamu TIDAK Perlu Download Repo Ini!

```
┌──────────────────────────────────────────────────────────────┐
│   ❌ JANGAN download repo ini secara langsung!               │
│                                                              │
│   ✅ Download [payload-extension] saja!                      │
│      Extension akan auto-sync payload dari repo ini.         │
└──────────────────────────────────────────────────────────────┘
```

### 🔗 Link Download Extension
👉 **[Download PELURU LUHUT Extension](https://github.com/hyla001/payload-extension)**

---

## 🔄 How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│   User Browser                                                   │
│   ─────────────                                                  │
│   📦 payload-extension (installed)                               │
│           │                                                      │
│           │ Fetch via GitHub Raw URL                             │
│           ▼                                                      │
│   📂 luhut-binshar (this repo)                                  │
│   └── payloads/                                                 │
│       ├── xss.json                                              │
│       ├── sqli.json                                             │
│       ├── ... (auto-synced)                                     │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📦 Payload Categories

| Category | Count | Description |
|----------|-------|-------------|
| 💉 **XSS** | 25+ | Cross-Site Scripting |
| 🗄️ **SQLi** | 25+ | SQL Injection |
| 🌐 **SSRF** | 15+ | Server-Side Request Forgery |
| 📁 **LFI** | 13+ | Local File Inclusion |
| 📡 **RFI** | 8+ | Remote File Inclusion |
| 💻 **CMDi** | 16+ | Command Injection |
| 🔧 **SSTI** | 13+ | Server-Side Template Injection |
| ↪️ **Open Redirect** | 10+ | URL Redirect Attacks |
| 🔐 **CSRF** | 9+ | Cross-Site Request Forgery |
| 🔓 **2FA Bypass** | 20+ | Two-Factor Auth Bypass |
| 🛡️ **WAF Bypass** | 25+ | Firewall Bypass Techniques |

---

## 📁 Structure

```
luhut-binshar/
├── index.json              # Category index
├── version.json            # Version info for sync
├── payloads/
│   ├── xss.json
│   ├── sqli.json
│   ├── ssrf.json
│   ├── lfi.json
│   ├── rfi.json
│   ├── cmdi.json
│   ├── ssti.json
│   ├── open_redirect.json
│   ├── csrf.json
│   ├── 2fa_bypass.json     # NEW
│   └── waf_bypass.json     # NEW
└── schemas/
    └── payload.schema.json
```

---

## 🤝 Contributing

Ingin menambahkan payload? Pull request welcome!

### Format Payload:
```json
{
  "id": "unique_id",
  "title": "Payload Title",
  "category": "XSS",
  "subcategory": "Reflected",
  "payload": "<script>alert(1)</script>",
  "tags": ["basic", "reflected"]
}
```

---

## ⚠️ Disclaimer

> **For authorized security testing only.**
> 
> Payload ini dibuat untuk keperluan security testing yang sah. Penggunaan untuk aktivitas ilegal sepenuhnya menjadi tanggung jawab pengguna.

---

## 📄 License

This project is licensed under the **GPL-3.0 License**.

---

## 📞 Contact

- GitHub: [@hyla001](https://github.com/hyla001)
