# discord-bot-meme

![Header](https://raw.githubusercontent.com/codedex-io/projects/main/projects/build-a-discord-bot-with-python/header.png)

# Discord Meme Bot

A simple and fun bot developed in Python that fetches random memes from Reddit directly to your Discord server. This project was created as part of my programming and automation studies.

## Features

- **`$meme` command:** The bot queries an external API and sends a random meme image to the chat.
- **Secure:** Uses environment variables to protect the Bot Token.

## The Final Result will look like this:


<p align="center">
  <img src="https://raw.githubusercontent.com/marianinhaUFMT/discord-bot-meme/refs/heads/main/docs/discordbot.gif" alt="Discord Bot Demo">
</p>


---

## Technologies Used

- [Python](https://www.python.org/)
- [Discord.py](https://discordpy.readthedocs.io/) (Interaction with Discord API)
- [Requests](https://pypi.org/project/requests/) (To fetch memes from the web)
- [Meme API](https://github.com/D3vd/Meme_Api) (Checkout how it works)
- [Dotenv](https://pypi.org/project/python-dotenv/) (For credential security)

## How to run the project on your machine

### Requirements
- Python 3 installed.
- pip (package installer) installed.
- A Discord account.
- A Discord server with "Manage Server" permissions.

### Step 1: Clone the repository
Open your terminal and type:
```bash
git clone [https://github.com/marianinhaUFMT/discord-bot-meme.git](https://github.com/marianinhaUFMT/discord-bot-meme.git)
cd discord-bot-meme
````

### Step 2: Install dependencies

On Linux/Mac:

```bash
python3 -m pip install -U discord.py
python3 -m pip install requests
pip install python-dotenv
```

On Windows:

```bash
py -3 -m pip install -U discord.py
py -3 -m pip install requests
pip install python-dotenv
```

### Step 3: Configure Security (The Secret)

Create a file named `.env` in the project folder and add your Discord token:
*(Note: The .env file is not pushed to GitHub for security)*

```ini
DISCORD_TOKEN=YOUR_TOKEN_HERE
```

### Step 4: Turn on the Bot\!

```bash
python bot.py
```

## License

This project is free to use for study purposes.

<p align="center"> Made by <a href="https://github.com/marianinhaUFMT">marianinha</a> </p>
