> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/roddyfred)

![img1](./.github/image/hero.png)

# Use Node.Js 18 or greater

## Functionality

| Functional                                                    | Supported |
| ------------------------------------------------------------- | :-------: |
| Claiming daily reward                                         |    ✅     |
| Claiming Farming reward                                       |    ✅     |
| Starting Farming                                              |    ✅     |
| Playing games                                                 |    ✅     |
| Multithreading                                                |    ✅     |
| Binding a proxy to a session                                  |    ✅     |
| Auto-purchase of items if you have coins (multitap, attempts) |    ✅     |
| Binding a proxy to a session/query_id                         |    ✅     |
| Random sleep time between clicks                              |    ✅     |

## [How to add query id](https://github.com/Freddywhest/RockyRabbitBot/blob/main/AddQueryId.md)

## [Settings](https://github.com/FreddyWhest/ToMarketBot/blob/main/.env-example)

| Settings                    | Description                                                               |
| --------------------------- | ------------------------------------------------------------------------- |
| **API_ID / API_HASH**       | Platform data from which to launch a Telegram session (stock - Android)   |
| **AUTO_PLAY_GAME**          | Whether the bot play the games (True / False)                             |
| **AUTO_CLAIM_DAILY_REWARD** | Whether the bot should claim the daily rewards (True / False)             |
| **AUTO_FARM**               | Whether the bot should start and claim farming (True / False)             |
| **SLEEP_BETWEEN_TAP**       | Delay between taps in seconds (eg. 70)                                    |
| **USE_QUERY_ID**            | Whether to use query ids instead of sessions (True / False)               |
| **USE_PROXY_FROM_FILE**     | Whether to use proxy from the `bot/config/proxies.js` file (True / False) |

## Installation

You can download [**Repository**](https://github.com/FreddyWhest/ToMarketBot) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/FreddyWhest/ToMarketBot.git
~ >>> cd ToMarketBot

#Linux and MocOS
~/ToMarketBot >>> chmod +x check_node.sh
~/ToMarketBot >>> ./check_node.sh

OR

~/ToMarketBot >>> npm install
~/ToMarketBot >>> cp .env-example .env
~/ToMarketBot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/ToMarketBot >>> node index.js

#Windows
1. Double click on INSTALL.bat in ToMarketBot directory to install the dependencies
2. Double click on START.bat in ToMarketBot directory to start the bot

OR

~/ToMarketBot >>> npm install
~/ToMarketBot >>> cp .env-example .env
~/ToMarketBot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/ToMarketBot >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/ToMarketBot >>> node index.js --action=1

OR

~/ToMarketBot >>> node index.js --action=2

#1 - Create session
#2 - Run clicker
```
