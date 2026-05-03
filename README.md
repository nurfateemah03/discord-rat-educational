# Discord Remote Access Tool - Educational Project

A Python-based Discord Remote Administration Tool built for educational purposes to demonstrate how remote command execution and bot-based communication works.

> ⚠️ This project is strictly for educational use. Do not use on systems you do not own or have explicit permission to access.

## Features
- Execute PowerShell commands remotely via Discord
- Creates a private channel on startup named after the host machine's IP
- Only responds to commands sent in that channel

## Setup
1. Clone the repo
2. Install dependencies:
   pip install discord.py requests
3. Create a `.env` file in the project root:
   DISCORD_TOKEN=your_discord_token_here
4. Run the bot:
   python bot.py

## Requirements
- Python 3.8+
- Windows (uses PowerShell)
- A Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications)

## Disclaimer
This project was created for learning purposes only. The author is not responsible for any misuse.
