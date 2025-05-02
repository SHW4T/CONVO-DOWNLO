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
2. Install dependencies
3. Configure `TOKEN`, `TARGET_CHANNEL`, and `AUTHORIZED_USERS` in the script
4. (Optional) Add Hugging Face API token for enhanced NLP

## Demo Video 🎥  
[Watch demonstration](https://www.linkedin.com/posts/shwat_programming-python-telegrambots-activity-7324068497485901825-MZ77?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFheUKYBKwZZDEvvdUkR3gMmMJ6eP8me_zg)  
*(Replace with your actual video link)*

## License 📄  
MIT License - See [LICENSE](LICENSE) file

