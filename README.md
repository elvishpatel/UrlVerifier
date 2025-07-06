# 🔍 URL Verifier

**URL Verifier** is a simple, frontend-only tool that helps users check whether a given URL is safe or suspicious using various public APIs and in-browser analysis — all without any backend.

---

## 🌐 Live Demo

🔗 Try it here : https://url-verifier-by-elvish.netlify.app/

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

1. You paste a URL (e.g., `https://ortopediaspro.cl/galicia/`)
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
| `https://ortopediaspro.cl/galicia/` | ❌ Dangerous (Multiple Threats Detected) |

---

##  🔐 Notes
No user data is stored or sent to any server.

This tool uses public APIs to check threats.

⚠️ It’s meant for educational and personal use — not guaranteed to catch all threats.

---

## 🧠 Keywords Scanned
verify account, click here, login now, your prize, urgent, free gift, reset password, update required, claim reward, bank alert, you’ve been hacked, and 40+ more

---

##  👨‍💻 Creator
Elvish Patel

---

## 📄 License
This project is open-source and licensed under the MIT License.

---

## ✨ Tip
Always double-check suspicious URLs — don’t blindly click random links in emails, messages, or social media posts. This tool is one extra layer of protection.
