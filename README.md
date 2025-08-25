# 🐐 Gaot Bot v3

Personal Messenger bot built from **Personal-bot** base + selected mods from **Messager-bot**.

- Base: Personal-bot (deploy & command system)
- Mods: fb-chat-api, logger, func utilities, and Goat.js runner
- Owner: Farhan muh tasim (frnwot) — frnbuid2005@gmail.com

## Quick start

```bash
# install
npm install

# run with Personal-bot core
npm start

# run Goat.js mods
npm run start:goat
```

> This repo is prepared for "my guy" hosting. Update `config.json` and `CyberFca.json` with your credentials/appstate.

---
Got it! Here's the updated full `README.md` with the repo name updated to **Personal-bot** in the clone URLs and deploy links:

---

# 🤖 frnwot Bot — Multi-Device Messenger Chatbot

> **A powerful personal Messenger bot for multi-device chat automation.**

![GitHub Stars](https://img.shields.io/github/stars/frn/Personal-bot?style=flat-square)
![GitHub Forks](https://img.shields.io/github/forks/frn/Personal-bot?style=flat-square)
![Repo Size](https://img.shields.io/github/repo-size/frn/Personal-bot?style=flat-square)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=flat-square)

<p align="center">
  <img src="https://github.com/GazaOS-Revived/Images/blob/main/file/ic_launcher_foreground.png" width="120" />
</p>

---

### 🌟 Features

- Multi-device Messenger support  
- Auto replies, stickers, media, logo fetcher, etc.  
- Personal chatbot modes  
- MongoDB-based persistence  
- Easy deployment (GitHub, Heroku, Replit, Railway, etc.)  

---

### 📦 Deploy via GitHub Actions (Workflow)

```yaml
name: Messenger Bot CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest
    strategy:
      matrix:
        node-version: [20.x]

    steps:
      - uses: actions/checkout@v2
      - name: Use Node.js ${{ matrix.node-version }}
        uses: actions/setup-node@v2
        with:
          node-version: ${{ matrix.node-version }}

      - name: Install dependencies
        run: npm install

      - name: Start the bot
        env:
          PORT: 8080
        run: npm start
````

---

### 🚀 One-Click Deploy Options

| Platform    | Deploy                                                                                                                                                                                                          |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Heroku**  | [![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new-app?template=https://github.com/frn/Personal-bot)                                                           |
| **Replit**  | [![Deploy to Replit](https://img.shields.io/badge/REPLIT-Deploy-orange?style=for-the-badge\&logo=replit)](https://replit.com/github/frn/Personal-bot)                                                           |
| **Koyeb**   | [![Deploy to Koyeb](https://img.shields.io/badge/KOYEB-Deploy-blue?style=for-the-badge\&logo=koyeb)](https://app.koyeb.com/services/deploy?type=git&repository=https://github.com/frn/Personal-bot&branch=main) |
| **Railway** | [![Deploy to Railway](https://img.shields.io/badge/RAILWAY-Deploy-black?style=for-the-badge\&logo=railway)](https://railway.app/new)                                                                            |
| **Render**  | [![Deploy to Render](https://img.shields.io/badge/RENDER-Deploy-maroon?style=for-the-badge\&logo=render)](https://dashboard.render.com)                                                                         |

---

### 🔧 Configuration

1. Set `SESSION_ID`, `MONGODB_URL`, `BOT_NAME`, and other environment variables as needed.
2. Clone the repo:

   ```bash
   git clone https://github.com/frnwot/Goat-bot-v3
   cd Personal-bot
   npm install
   npm start
   ```

---

### 📲 Support

Need help or want to contribute?

* 💬 [Messenger Support Group](https://m.me/j/AbbgQN_Pv6yXppYl/)
* 📞 WhatsApp: [Contact Admin](https://wa.me/+8801882333052?text=Hi+Farhan%2C+I+need+help+with+the+frnwot+Bot)
* 🌐 [GitHub Profile](https://github.com/frn)

---

### 📹 Tutorial

[![YouTube](https://i.ibb.co/71mYRh4/116-1161192-podcast-subscribe-listen-button-youtube-sign-hd-png.png)](https://youtu.be/qHUMWc7CTS8)

---

### 🤝 Credits

Special thanks to:

* **Mohamed Farhan muh tasim** (Developer)

---

> 📅 **Release Date:** 15/04/2025 at 08:00
> ⭐ Don't forget to star the repo and follow for updates!

---

**May this journey continue with all of you by my side, *In Shaa Allah*.**

```

---

If you want it as a file or further tweaks, just say!
```
