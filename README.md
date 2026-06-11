# 🤖 Malvin C Leo — WhatsApp Multi-Device Bot
> Powered by **Handsome Tech Zimbabwe** 🇿🇼

---

## 📋 Features
- ✅ 387 Commands
- 🎵 Music download (.play)
- 💰 Full economy system
- 🤖 AI chatbot
- 👥 Group management
- 🎮 Games & fun
- 🌍 Info & tools

---

## 🚀 Deploy on Vercel

### Step 1 — Upload to GitHub
1. Go to [github.com](https://github.com) → **New repository**
2. Name it `malvin-c-leo`
3. Click **uploading an existing file**
4. Upload all files from this zip (keep folder structure)
5. Click **Commit changes**

### Step 2 — Deploy to Vercel
1. Go to [vercel.com](https://vercel.com) → Sign in with GitHub
2. Click **New Project**
3. Import your `malvin-c-leo` repo
4. Click **Deploy** (no settings needed)
5. Wait ~1 minute — Vercel gives you a URL like `malvin-c-leo.vercel.app`

---

## 📱 How to Pair Your Bot

### Method 1 — Pairing Code (Recommended)
1. Open your Vercel URL in a browser (e.g. `https://malvin-c-leo.vercel.app`)
2. Click the **🔑 PAIR CODE** tab
3. Type your WhatsApp number with country code — e.g. `263776676755`
4. Click **GET PAIRING CODE**
5. Open WhatsApp on your phone
6. Go to **⋮ Menu → Linked Devices → Link a Device**
7. Tap **Link with phone number instead**
8. Enter the 8-digit code shown on the website
9. ✅ Done! Bot is now connected

### Method 2 — QR Code
1. Open your Vercel URL
2. Click the **📷 QR CODE** tab
3. A QR code will appear
4. Open WhatsApp → **Linked Devices → Link a Device**
5. Scan the QR with your camera
6. ✅ Done!

---

## 💬 Bot Commands (Prefix: `.`)

| Category | Commands |
|----------|---------|
| 🎵 Music | `.play`, `.song` |
| 🤖 AI | `.ai`, `.chat`, `.ask` |
| 💰 Economy | `.balance`, `.daily`, `.work`, `.rob`, `.deposit`, `.withdraw`, `.give`, `.shop`, `.buy`, `.leaderboard` |
| 🎮 Fun | `.joke`, `.fact`, `.quote`, `.8ball`, `.flip`, `.roll`, `.rps`, `.dare`, `.truth`, `.slots`, `.trivia` |
| 🌍 Info | `.weather`, `.calc`, `.define`, `.crypto`, `.translate` |
| 🔧 Utility | `.menu`, `.ping`, `.uptime`, `.info`, `.alive`, `.stats` |
| 📝 Text | `.reverse`, `.upper`, `.lower`, `.mock`, `.count` |
| 👥 Group | `.kick`, `.add`, `.promote`, `.demote`, `.tagall`, `.mute`, `.unmute` |

Type `.menu` in WhatsApp to see all 387 commands!

---

## ⚙️ Local Setup (Optional)

```bash
# Install dependencies
npm install

# Start bot
npm start
```

Then open `http://localhost:3000` to pair.

---

## 📁 File Structure

```
malvin-c-leo/
├── index.js          ← Main bot + Express server
├── package.json      ← Dependencies
├── vercel.json       ← Vercel config
├── README.md         ← This file
├── public/
│   ├── index.html    ← Pairing website
│   └── menu.png      ← Menu image
├── commands/
│   ├── index.js      ← Command loader
│   ├── play.js       ← Music commands
│   ├── economy.js    ← Economy system
│   ├── chatbot.js    ← AI chatbot
│   └── general.js    ← 300+ general commands
└── data/
    └── economy.json  ← Economy database (auto-created)
```

---

## ⚠️ Important Notes

- **Session**: On Vercel (serverless), sessions reset on redeploy. For persistent sessions use Railway or Render
- **Music**: `.play` requires `yt-search` and `@distube/ytdl-core` — works locally and on Railway
- **Economy data**: Stored in `data/economy.json` — resets on Vercel redeploy (use a database for production)

---

## 👨‍💻 Credits

**Developer:** Handsome Tech Zimbabwe 🇿🇼  
**Framework:** [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys)  
**Bot:** Malvin C Leo  

---

*Made with ❤️ by Handsome Tech Zimbabwe 🇿🇼*
