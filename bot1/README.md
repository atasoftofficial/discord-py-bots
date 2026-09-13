# 🤖 ATASOFT™ Bot 1

> A modular Discord bot developed as part of the ATASOFT™ Multi-Bot Ecosystem.

> ATASOFT™ Multi-Bot Ekosistemi kapsamında geliştirilen modüler Discord botu.

---

## 🇬🇧 English

### 📌 About

**Bot 1** is one of the Discord bots developed under the **ATASOFT™ Discord Bots** ecosystem.

The bot is designed with a modular architecture, allowing commands, events, and utility systems to be developed and maintained independently.

### ✨ Features

- 🤖 Discord bot infrastructure
- 🧩 Modular Cog architecture
- ⚡ Asynchronous command handling
- 🛡️ Environment-based configuration
- 📋 Centralized logging
- 🔧 Reusable utility systems
- 📈 Scalable architecture

### 🛠️ Technologies

- **Python 3.10+**
- **discord.py 2.x**
- **asyncio**
- **python-dotenv**

### 📂 Structure

```text
bot1/
├── cogs/
│   ├── commands/
│   └── events/
├── utils/
├── main.py
├── requirements.txt
├── .env
└── README.md
🔐 Configuration

Create a .env file in the bot directory:

BOT_TOKEN=your_bot_token_here
CLIENT_ID=your_client_id_here

Never share or commit your bot token.

Make sure .env is included in .gitignore:

.env
▶️ Running

Install the required dependencies:

pip install -r requirements.txt

Then start the bot:

python main.py
🔒 Discord Intents

Depending on the bot's functionality, the required Gateway Intents may need to be enabled through the Discord Developer Portal.

Possible privileged intents:

Presence Intent
Server Members Intent
Message Content Intent

Only enable the intents required by the bot.

🇹🇷 Türkçe
📌 Hakkında

Bot 1, ATASOFT™ Discord Bots ekosistemi kapsamında geliştirilen Discord botlarından biridir.

Bot; komutların, eventlerin ve yardımcı sistemlerin bağımsız şekilde geliştirilebilmesini ve yönetilebilmesini sağlayan modüler bir mimari üzerine kuruludur.

✨ Özellikler
🤖 Discord bot altyapısı
🧩 Modüler Cog mimarisi
⚡ Asenkron komut işlemleri
🛡️ Ortam değişkenleri ile güvenli yapılandırma
📋 Merkezi loglama sistemi
🔧 Yeniden kullanılabilir yardımcı sistemler
📈 Ölçeklenebilir mimari
🛠️ Kullanılan Teknolojiler
Python 3.10+
discord.py 2.x
asyncio
python-dotenv
📂 Klasör Yapısı
bot1/
├── cogs/
│   ├── commands/
│   └── events/
├── utils/
├── main.py
├── requirements.txt
├── .env
└── README.md
🔐 Yapılandırma

Bot klasörü içerisinde .env dosyası oluşturun:

BOT_TOKEN=bot_token_buraya
CLIENT_ID=client_id_buraya

Bot tokenınızı kesinlikle paylaşmayın veya GitHub'a yüklemeyin.

.env dosyasının .gitignore içerisinde bulunduğundan emin olun:

.env
▶️ Çalıştırma

Gerekli bağımlılıkları yükleyin:

pip install -r requirements.txt

Ardından botu çalıştırın:

python main.py
🔒 Discord Intent Ayarları

Botun kullandığı özelliklere bağlı olarak gerekli Gateway Intent'lerin Discord Developer Portal üzerinden etkinleştirilmesi gerekebilir.

Kullanılabilecek özel intentler:

Presence Intent
Server Members Intent
Message Content Intent

Yalnızca botun ihtiyaç duyduğu intentleri etkinleştirin.

<div align="center">

⚡ ATASOFT™

Teknolojiyi insanlığın yararına geliştiriyoruz.

</div> ```
