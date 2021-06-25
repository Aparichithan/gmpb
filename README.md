# Techno Ocean Music Telegram Bot - This is a pyrogram bot based on pytgcalls for playing songs or audio files in Telegram group voice chat
[![Group Music Probot](https://telegra.ph/file/8262082f0ab2c5d7ca2fb.png)](https://t.me/devilcodes_inc)
![GitHub repo size](https://img.shields.io/github/repo-size/edguru/devilsmusic)

## Notes
-The commands and there use is explained here-:
- `/saavn` To search song on jio saavan and play the first result 
- `/ytt` To search the song on Youtube and play the first matching result.
- `/deezer` To search song on deezer and play good quality stream.
- `/play` Reply this in response to a link or any telegram audio file it will be played 
- `/skip` to skip current song 
- `/stop or /kill` to stop the streaming of song 
- `/pause` to pause the stream 
- `/resume` to resume the playback. 
- Inline search is also supported.

- Use pyrogram string u can use @StringGenBot

-It is inspired from su music project and hamkercat's telegram voice bot.
Neither su music project , nor pytgcalls are stable

## Requirements

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7+
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

## Deployment
` Don't forget to star 🌟 us `
### Config

Copy `example.env` to `.env` and fill it with your credentials.

### Without Docker

1. Install Python requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```
   # How To Host

The easiest way to deploy this Bot

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/Aparichithan/gmpb"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>
   

### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

## Support
- [Channel](https://t.me/Techno_Ocean)
- [Group](https://t.me/Cutiepii_Support)
## Credits
- [hamker cat](https://github.com/thehamkercat/Telegram_VC_Bot)
- [Roj](https://github.com/rojserbest)
- [Marvin](https://github.com/BlackStoneReborn)
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
