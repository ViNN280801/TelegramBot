# NIASupportBot

NIASupportBot is a Telegram bot designed to provide motivational phrases and other interactions through Telegram commands and buttons. This bot is built using Python and the `python-telegram-bot` library.

## Features

- **Start Command**: Initializes the bot and provides a custom keyboard with options.
- **Phrase Button**: Sends a random motivational phrase from a predefined list.
- **Image Button**: Placeholder for future implementation of sending images.
- **Logging**: Logs all interactions and messages to both the console and a log file.
- **User Details**: Captures and logs user details including ID, username, full name, and optional birth date or bio.

## Setup

### Prerequisites

- Python 3.7+
- Telegram Bot Token from [BotFather](https://t.me/BotFather)

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/TelegramBot.git
    cd TelegramBot
    ```

2. **Create a virtual environment and activate it:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up your bot token:**
    - Create a file named `bot_token.py` in the root directory and add your bot token:
    ```python
    BOT_TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'
    ```

## Usage

### Running the Bot

To start the bot, run the following command:

```sh
python main.py
```

### Interacting with the Bot

* Start the Bot: Send /start to the bot. This will initialize the bot and display a custom keyboard with "Phrase" and "Image" buttons.
* Request a Phrase: Click the "Phrase" button to receive a random motivational phrase.
* Request an Image: Click the "Image" button. (Currently, this feature is a placeholder and not yet implemented.)
