# 🔍 URL Verifier

**URL Verifier** is a simple, frontend-only tool that helps users check whether a given URL is safe or suspicious using various public APIs and in-browser analysis — all without any backend.

---

## 🌐 Live Demo

[🔗 Try it here](#) https://url-verifier-by-elvish.netlify.app/

---

## ✨ Features

- 🔒 SSL security grade checker via SSL Labs
- 🛡 Google Safe Browsing API integration
- 🧠 Scam keyword detection (over 50+ phrases)
- 🧬 Real-time analysis via `urlscan.io`
- ⚠️ Highlights phishing, malware, and low-trust websites
- ✅ Frontend-only (No backend/server required)
- 📱 Responsive & modern glassmorphic UI

---

## 🛠 Tech Used

| Tech | Description |
|------|-------------|
| HTML/CSS | Glassmorphism UI |
| JavaScript | Core logic for validation and analysis |
| APIs Used | SSL Labs, Google Safe Browsing, urlscan.io |

---

## 🚀 How It Works

1. You paste a URL (e.g., `https://free-gift-example.com`)
2. The app checks:
   - If it’s **HTTPS-enabled**
   - Its **SSL Grade** using SSL Labs
   - Whether it’s flagged by **Google Safe Browsing**
   - Its behavior using **urlscan.io**
   - Scam phrases in the actual HTML content (e.g., “verify your account”, “claim your reward”)
3. You get a **final verdict**: ✅ Safe, ⚠️ Risky, or ❌ Dangerous

---

## 📸 Screenshot


![2](https://github.com/user-attachments/assets/44f036c0-f41b-415f-a75f-257309401a87)

---

## 💡 Example Outputs

| URL | Verdict |
|-----|---------|
| `https:/google.com` | ✅ Looks Safe |
| `http://[free-prize123.ru](https://ortopediaspro.cl/galicia/` | ❌ Dangerous (Multiple Threats Detected) |

---

## ⚙️ How to Use Locally

1. Clone the repo:

```bash
git clone https://github.com/elvish-patel/url-verifier.git
cd url-verifier
