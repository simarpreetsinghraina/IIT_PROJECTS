Telegram Bot – Pyrogram Based
This is a simple yet functional Telegram bot built using Pyrogram and Python-Telegram-Bot API. The bot supports a few basic commands like /start, /help, /about, /joke, /quote, and /notes. Ideal for beginners exploring Telegram bot development or small utility projects.

Features
/start: Greets the user and introduces the bot.

/help: Lists available commands and their purpose.

/about: Shares a brief about the bot and its creator.

/joke: Sends a random lighthearted joke.

/quote: Returns an inspiring or thoughtful quote.

/notes: Shares a quick note or reminder randomly selected from a list.

Tech Stack
Python 3.10+

Pyrogram

Telethon (optional, for advanced features)

TgCrypto (required for Pyrogram)

Python's built-in random and asyncio libraries

Installation
Clone this repo

bash
Copy
Edit
git clone https://github.com/your-username/your-bot-repo.git
cd your-bot-repo
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # Linux/macOS
.\venv\Scripts\activate    # Windows
Install the dependencies

bash
Copy
Edit
pip install pyrogram tgcrypto
Create a file named config.py and fill it with your credentials:

python
Copy
Edit
API_ID = "your_api_id"
API_HASH = "your_api_hash"
BOT_TOKEN = "your_bot_token"
You can get your API_ID and API_HASH from my.telegram.org.

Running the Bot
bash
Copy
Edit
python main.py
Make sure you're inside the virtual environment and your config.py is correctly set up.

File Structure
bash
Copy
Edit
project_folder/
│
├── main.py           # Bot entry point
├── config.py         # Contains API credentials
├── requirements.txt  # Dependency list (optional)
└── README.md         # This file
License
This project is for educational and personal use. Feel free to modify it for your own needs. Attribution is appreciated.

