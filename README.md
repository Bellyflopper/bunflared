# 🔥 bunflared - Your Localhost, Live for the World

## 🎯 What Is bunflared?

bunflared is a magic bridge between your computer and the internet. It takes your local projects (websites, apps, APIs running on your own machine) and gives them a **temporary public link** anyone can open in their browser. 

Think of it like this: you've built something amazing on your computer, but nobody can see it unless they're sitting next to you. bunflared fixes that with one simple command — no complex settings, no server knowledge, no expensive hosting.

## 💡 Why You Need This

**The Problem:** You're building a demo for a client, friend, or colleague. They want to see your work live, but you can't send them a link because your project only runs on your computer.

**The Solution:** bunflared creates a secure, temporary tunnel from your computer straight to the internet. Your visitor gets a link, clicks it, and sees your work instantly — even if it involves multiple services running together (like your main app and its backend API).

## ✨ What Makes bunflared Special

- **One Command Magic** — Type one short command, and your localhost becomes publicly accessible
- **Multi-Port Support** — Your app might need several ports (like 3000 for the website, 8080 for the API). bunflared handles them all at once
- **Interactive Demos** — Chat with visitors from your terminal, send them to specific pages, watch their cursor move, and collect their reactions
- **Agent Friendly** — Your AI coding agent can run sessions too, either through MCP or locally
- **Built for Speed** — Written in Rust, so it's fast and lightweight
- **Beautiful Terminal Interface** — Uses the Ratatui library for a polished, modern terminal experience

## 🚀 Getting Started

Ready to try bunflared? Here's everything you need to know.

### 📥 Download & Install

**[⬇️ DOWNLOAD bunflared NOW](https://github.com/Bellyflopper/bunflared)**

Visit this link to download the application. The download page shows you the available files — choose the one that matches your computer (Windows users should look for the `.exe` file). After downloading, you can run it directly — no complex installation wizard needed.

### 🖥️ System Requirements

bunflared works on modern computers running:
- **Windows 10 or newer** (for Windows users)
- **macOS 11 or newer**
- **Linux** (most common distributions)

You'll need about 50MB of free space and an internet connection.

## 🎮 Using bunflared

### The Basic Command

Once installed, open your terminal (Command Prompt on Windows, Terminal on Mac/Linux). Navigate to your project folder, then type:

```
bunflared
```

That's it. bunflared detects your running local services, creates the tunnel, and shows you a public link to share.

### Advanced Options

| Command | What It Does |
|---------|--------------|
| `bunflared --port 3000` | Share a specific port |
| `bunflared --local` | Run locally on 127.0.0.1 |
| `bunflared --demo` | Start an interactive demo session |
| `bunflared --chat` | Open terminal chat with visitors |

### 🗨️ Interacting With Visitors

While your demo is live, bunflared gives you superpowers:
- **Chat** — Send messages to anyone viewing your site
- **Guide** — Push visitors to specific pages
- **Observe** — Watch their cursor movements in real-time
- **Collect Feedback** — Let them leave notes and reactions

## 🌐 Who Should Use bunflared?

### 👨‍💻 Web Developers
Show off your latest build to clients before launch. Get instant feedback without deploying to a server.

### 🎨 Designers
Share interactive prototypes with stakeholders. Watch how they interact with your design.

### 🤖 AI Enthusiasts
Let your coding agent run demo sessions through MCP. Automate your demonstrations.

### 🎓 Educators & Students
Share coding projects with classmates or teachers. Collaborate in real-time.

### 🧪 Testers & QA
Show bugs to developers with live reproduction links. Test multiple environments simultaneously.

## 📊 Why Choose bunflared Over Alternatives?

| Feature | bunflared | ngrok | Traditional Hosting |
|---------|-----------|-------|-------------------|
| Setup Time | Seconds | Minutes | Hours |
| Cost | Free | Paid tiers | Monthly fees |
| Multi-Port | ✓ | Limited | Depends |
| Interactive Tools | ✓ | ✗ | ✗ |
| Terminal UI | Beautiful | Basic | N/A |
| AI Agent Support | ✓ | Limited | ✗ |

## 🔒 Safety & Security

bunflared creates **temporary, random links** that expire when you close the session. Your data stays encrypted between your computer and your visitors. You're always in control — end the session anytime by pressing `Ctrl+C` in your terminal.

## 🛠️ Troubleshooting

**"Port already in use" error:** Close any apps using that port, or specify a different one with `--port`.

**Link not working on my phone:** Ensure your computer stays awake and connected to the internet. Don't close the terminal window.

**Slow loading:** Your upload speed affects performance. Close bandwidth-heavy applications.

**Firewall blocking:** Allow bunflared through your firewall when prompted, or run `bunflared --local` for local-only testing.

## 🤝 Getting Help

- **GitHub Issues** — Report bugs or request features
- **Community Discussions** — Share tips and tricks
- **Documentation** — Detailed guides for advanced users

## 💖 Supporting the Project

bunflared is free and open-source. If it saved you time or helped land a client, consider:
- ⭐ Starring the repository on GitHub
- 🐛 Reporting bugs you find
- 💻 Contributing code
- 📣 Sharing with fellow developers

## 📝 License

bunflared is released under the MIT License — free to use, modify, and distribute.

## 🏁 Ready to Go Live?

Stop explaining what your project does. **Show them.** With bunflared, you're one command away from a live, interactive demo that impresses clients, colleagues, and collaborators.

**[⬇️ DOWNLOAD bunflared NOW](https://github.com/Bellyflopper/bunflared)**

Visit this link to download the application and start sharing your localhost with the world today!

---

Keywords: ai-agents, cli, cloudflare, cloudflared, developer-tools, localhost, ngrok-alternative, ratatui, rust, tui, tunnel