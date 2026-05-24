# 🦉 Tutorial Hermes Agent — Install di Termux + OpenRouter API

**Bahasa Indonesia** | **Step-by-Step** | **Untuk Pemula**

## 📖 Buka Tutorial

**🌐 Web (bisa di HP):** https://sadz-hubz.github.io/tutorial-hermes-agent/

**📄 PDF Download:** [tutorial-hermes-v2.pdf](tutorial-hermes-v2.pdf)

## 📋 Isi Tutorial

1. Apa itu Hermes Agent?
2. Apa itu Termux?
3. Install Termux
4. Persiapan Packages
5. Install Hermes Agent
6. Dapatkan API Key OpenRouter
7. Free Models (tanpa bayar!)
8. Konfigurasi Hermes + OpenRouter
9. Bikin Bot Telegram
10. Testing
11. Troubleshooting
12. Quick Start (copy-paste)

## ⚡ Quick Start

```bash
pkg update && pkg upgrade -y
pkg install -y nodejs python git curl wget nano openssl-tool
npm install -g @nousresearch/hermes-agent
hermes init
hermes config set model.provider openrouter
hermes config set model.base_url https://openrouter.ai/api/v1
hermes config set model.api_key sk-or-v1-KEY_KAMU
hermes config set model.default openrouter/auto
hermes chat
```

## 🎬 Mau buat video?

Buka `index.html` di browser → screen record → jadi video tutorial!

---

*Dibuat oleh OWL 🦉 | 24 Mei 2026*
