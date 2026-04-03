# IRC Discord Bridge - Sync Messages Between Channels 🤖🌉

![IRC Discord Bridge](https://img.shields.io/badge/Version-1.0.0-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg) ![Python](https://img.shields.io/badge/Python-3.8%2B-yellow.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Supported Channels](#supported-channels)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Overview

The **IRC Discord Bridge** is a Python bot that enables seamless message synchronization between IRC and Discord channels. This tool allows users to connect their IRC and Discord communities, ensuring that messages sent in one platform appear in the other. 

By bridging these two popular platforms, users can engage with their communities more effectively, no matter where they prefer to chat.

## Features

- Sync messages in real-time between multiple IRC and Discord channel pairs.
- Easy to set up and configure.
- Supports multiple channel connections.
- Built with Python for easy customization.
- Lightweight and efficient.

## Getting Started

### Prerequisites

To run the IRC Discord Bridge, you need:

- Python 3.8 or higher.
- Access to both an IRC server and a Discord server.
- Basic knowledge of how to set up a bot on Discord.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Isco81/irc-discord-bridge-python-bot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd irc-discord-bridge-python-bot
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

### Configuration

1. Create a configuration file named `config.json` in the project directory.

2. Add your IRC and Discord settings to the configuration file. Here is an example:

   ```json
   {
       "irc": {
           "server": "irc.example.com",
           "port": 6667,
           "channel": "#your-irc-channel",
           "nickname": "YourBotName"
       },
       "discord": {
           "token": "YOUR_DISCORD_BOT_TOKEN",
           "channel_id": "YOUR_DISCORD_CHANNEL_ID"
       }
   }
   ```

3. Replace the placeholders with your actual server and channel information.

## Usage

To start the bot, run the following command in your terminal:

```bash
python bot.py
```

Once the bot is running, it will connect to both IRC and Discord. Messages sent in either platform will be relayed to the other.

## Supported Channels

The bot currently supports:

- IRC channels (any standard IRC server).
- Discord channels (text channels only).

You can connect multiple pairs of channels by adding them to the configuration file.

## Contributing

We welcome contributions! If you would like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest releases, visit [Releases](https://github.com/Isco81/irc-discord-bridge-python-bot/releases). You can download the latest version and execute it to get started.

For more information, check the [Releases](https://github.com/Isco81/irc-discord-bridge-python-bot/releases) section of the repository.
