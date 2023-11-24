# Telegram Subscription Bot

Welcome to the Telegram Subscription Bot! This Python-based bot checks user subscriptions to specified channels. If a user is subscribed, the bot invites them to a private channel and periodically sends selected posts over time. If a user unsubscribes from a channel, the bot removes them from the private group.

## Prerequisites

Before running the bot, ensure you have the required dependencies installed. Use the following command:

```bash
pip install -r requirements.txt
```

## Configuration

1. Create a `.env` file in the project root with the following fields:

```env
TELEGRAM_TOKEN=your_telegram_token
PRIVATE_CHANNEL_ID=your_private_channel_id
CHECK_INTERVAL=your_check_interval_in_seconds
```

- `TELEGRAM_TOKEN`: Your Telegram bot token.
- `PRIVATE_CHANNEL_ID`: The ID of the private channel where the bot sends invitations and posts.
- `CHECK_INTERVAL`: The interval at which the bot checks for subscriptions (in seconds).

## Running the Bot

Run the bot using the following command:

```bash
python3 main.py
```

## Usage

1. Users subscribe to specified channels.
2. The bot periodically checks for subscriptions.
3. If a user is subscribed, the bot invites them to the private channel.
4. Over time, the bot sends to user selected posts.
5. If a user unsubscribes, the bot removes them from the private channel.

## Important Notes

- Make sure to handle sensitive information, such as the bot token, securely.
- The bot periodically checks for subscriptions based on the specified interval.

## Contribution

Contributions are welcome! If you have suggestions or want to improve the bot, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy subscription botting! 🤖🔗
