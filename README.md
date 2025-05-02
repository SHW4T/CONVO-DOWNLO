# Telegram Media Bot 🤖🎬  
*A multifunctional Telegram bot for media conversion, Instagram reel downloads, and AI-powered chat*

## Features ✨
- **Video to MP3 Conversion**  
  Reply to any video with `/convert` to get audio file
- **Instagram Reel Downloader**  
  Send `/reel <URL>` to download videos without watermark
- **AI Chat Assistant**  
  Conversational NLP using Hugging Face's Blenderbot model
- **Admin Tools**  
  - User analytics (`/users`)
  - Link tracking (`/links`)
  - Broadcast messaging (`/broadcast`)

## Tech Stack 💻
- **Python 3.10+**
- `python-telegram-bot` v20+
- `instaloader` for Instagram scraping
- `pydub` for audio conversion
- Hugging Face Inference API
- Asynchronous I/O with `asyncio`

## Setup 🔧
1. Get Telegram bot token from [@BotFather](https://t.me/BotFather)
2. Install dependencies:  
