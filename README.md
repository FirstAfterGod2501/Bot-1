# Bot

## Prerequisites
* [Git](https://git-scm.com/downloads)
* [Python 3](https://www.python.org/downloads)

## Install
```
git clone https://github.com/linksplatform/Bot.git
cd Bot
pip3 install -r requirements.txt
```

## Configure

1. Set bot group id in [config.py](https://github.com/linksplatform/Bot/blob/e10f51c7e3711c43708ce5659c7de9e76cab6702/python/config.py#L3-L4).
2. Add tokens into `python/tokens.py` file
* BotToken (an access token of your VK group). This token should have two access settings `community management` and `community messages`. This token is required.
* UserToken (an access token to your VK user via KateMobile). This token is used to delete messages in the chats where your user is administrator. This token is optional.

## Run

```Shell
cd python
python3 __main__.py
```

## Do not upload tokens.py with your real tokens please

To tell git to ignore this file:

```
git update-index --assume-unchanged python/tokens.py
```

## See the bot in action

To see the bot in action you can [join](https://vk.me/join/AJQ1d9E/bxbPjY87MeKsXgMa) the chat with this bot.
