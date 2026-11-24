# Telegram Hello Bot

A minimal, beginner-friendly Python Telegram bot generated with **BotForge** that responds to incoming messages with `"Hello!"` and logs them in your terminal.

## Project Structure

* **`bot.py`** — The main Python source code for the Telegram bot.
* **`.env`** — Stores your private Telegram bot token securely.
* **`requirements.txt`** — Lists the required Python packages.
* **`.gitignore`** — Prevents sensitive files like `.env` from being committed to Git.

## Prerequisites

* **Python 3.8+** installed on your machine
* A **Telegram Bot Token** from [@BotFather](https://t.me)

## Setup & Installation

1. **Extract the downloaded project files** into a dedicated folder and open your terminal inside that directory.

2. **(Optional) Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Verify your `.env` file:**
   Ensure your `.env` file in the root folder contains your valid BotFather token:
   ```env
   TELEGRAM_BOT_TOKEN=your_bot_token_here
   ```

## Running the Bot

Start the bot by running:
```bash
python bot.py
```

* Keep the terminal window open while the bot is running.
* Open Telegram, search for your bot's username, and send `/start` or any message.
* The bot will print the incoming message in your terminal and reply with **Hello!**.

## Security Note

Never share your `.env` file or commit your bot token to a public repository. If your token is ever exposed, regenerate it immediately via **@BotFather** using the `/revoke` command.
