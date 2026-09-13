<div align="center">
  <img src="https://atasoft.xyz/atasoft.png" width="140" alt="ATASOFT Logo" />

  <h1>⚡ ATASOFT™ — Multi-Bot Ecosystem & Infrastructure</h1>

  <p>
    <b>
      A high-performance, modular collection of Discord bots and shared
      architectures developed for the ATASOFT™ ecosystem.
    </b>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Discord.py-2.x-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord.py">
    <img src="https://img.shields.io/badge/Status-Developing-FF8C00?style=for-the-badge&logo=git&logoColor=white" alt="Status">
    <img src="https://img.shields.io/badge/ATASOFT™-Multi--Bot-00D26A?style=for-the-badge&logo=codeforces&logoColor=white" alt="ATASOFT">
  </p>
</div>

---

## 🚀 About

**ATASOFT™ Discord Bots** is an open-source multi-bot ecosystem designed to develop, manage, and maintain multiple functional Discord bots under a single organized repository.

The project focuses on **modularity, performance, security, scalability, and reusable architecture**.

---

## ✨ Features

* 🤖 **Multi-Bot Management** — Run and maintain multiple independent Discord bots from a single repository.
* 🧩 **Modular Cog Architecture** — Reusable commands, Cogs, events, and utility modules.
* 🛡️ **Secure Configuration** — Sensitive credentials are isolated through environment variables.
* ⚡ **Asynchronous Performance** — Built around Python's `asyncio` architecture for efficient execution.
* 📋 **Centralized Logging** — Event and error tracking through a centralized logging system.
* 🔧 **Reusable Infrastructure** — Shared utilities and core systems can be used across multiple bots.
* 📈 **Scalable Structure** — Designed to support additional bots and services as the ecosystem grows.

---

## 📦 Requirements

Before getting started, make sure you have:

* **Python:** `3.10+`
* **Git:** Latest version recommended
* **Discord Account**
* **Discord Developer Application:** Created through the [Discord Developer Portal](https://discord.com/developers/applications)

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/atasoft/discord-py-bots.git
cd discord-py-bots
```

### 2. Create a Virtual Environment

**Windows**

```bash
python -m venv venv
```

**macOS / Linux**

```bash
python3 -m venv venv
```

### 3. Activate the Virtual Environment

**Windows — Command Prompt**

```bash
venv\Scripts\activate
```

**Windows — PowerShell**

```powershell
.\venv\Scripts\Activate.ps1
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

---

## 🔒 Configuration & Security

### Environment Variables

Create a `.env` file in the root directory:

```env
BOT_TOKEN_1=your_first_bot_token_here
BOT_TOKEN_2=your_second_bot_token_here
CLIENT_ID=your_client_id_here
```

> ⚠️ **Critical Security Warning:** Never upload your `.env` file or bot tokens to GitHub.

Make sure `.env` is included in your `.gitignore`:

```gitignore
.env
venv/
__pycache__/
*.pyc
```

### Discord Gateway Intents

Depending on the bot's functionality, enable the required **Privileged Gateway Intents** in the Discord Developer Portal:

* Presence Intent
* Server Members Intent
* Message Content Intent

Only enable the intents your bot actually requires.

---

## ▶️ Running the Bots

After completing the configuration, start the application with:

```bash
python main.py
```

---

## 📁 Project Structure

A recommended structure for the ecosystem:

```text
discord-py-bots/
│
├── bots/
│   ├── bot1/
│   │   ├── cogs/
│   │   └── main.py
│   │
│   └── bot2/
│       ├── cogs/
│       └── main.py
│
├── core/
│   ├── utils/
│   ├── logging/
│   └── config/
│
├── .env
├── .gitignore
├── main.py
├── requirements.txt
└── README.md
```

> The exact structure may vary depending on the implementation and number of bots.

---

## 🧩 Architecture

The ecosystem is designed around a shared core architecture:

```text
                    ATASOFT™
                       │
             ┌─────────┴─────────┐
             │                   │
          Core System        Bot Manager
             │                   │
      ┌──────┼──────┐       ┌────┴────┐
      │      │      │       │         │
    Utils  Logging Config   Bot 1     Bot 2
                              │         │
                            Cogs      Cogs
                              │         │
                           Commands  Commands
```

This structure allows individual bots to remain independent while sharing common infrastructure and utilities.

---

## 🛡️ Security

Security is an important part of the project.

### Never commit:

* ❌ Discord bot tokens
* ❌ API keys
* ❌ Passwords
* ❌ Private credentials
* ❌ Production `.env` files

### Recommended workflow:

```text
.env
  ↓
Environment Variables
  ↓
Application Configuration
  ↓
Discord Bot
```

If a token is accidentally exposed, **immediately revoke and regenerate it** through the Discord Developer Portal.

---

## 🧑‍💻 Development

Contributions, improvements, bug fixes, and new ideas are welcome.

When contributing:

1. Create a new branch.
2. Make your changes.
3. Test your changes locally.
4. Keep sensitive credentials out of commits.
5. Open a Pull Request.

---

## 📜 License

This project is maintained by **ATASOFT™**.

If a specific license is added to the repository, this section should be updated accordingly.

---

<div align="center">

### ⚡ ATASOFT™

**Teknolojiyi insanlığın yararına geliştiriyoruz.**

</div>
