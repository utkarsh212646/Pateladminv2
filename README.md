# Patel Admin

<p align='center'>
  <img src="https://img.shields.io/github/fork/jagug/pateladminv2?style=flat-square" alt="AboutOwner">
  <img src="https://img.shields.io/github/stars/jagug/pateladminv2?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/issues/jagug/pateladminv2?style=flat-square" alt="Issues">
  <img src="https://img.shields.io/github/license/jagug/pateladminv2?style=flat-square" alt="LICENSE">
  <img src="https://img.shields.io/github/contributors/jagug/pateladminv2?style=flat-square" alt="Contributors">
  <img src="https://img.shields.io/github/repo-size/jagug/pateladminv2?style=flat-square" alt="Repo Size">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/jagug/pateladminv2&amp;title=Profile%20Views" alt="Views">
</p>

<p align='center'>
  <a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat-square&logo=python&color=blue" /> </a>
  <a href="https://hub.docker.com/r/divideprojects/alita_robot" alt="Docker!"> <img src="https://aleen42.github.io/badges/src/docker.svg" /> </a>
  <a href="https://deepsource.io/gh/DivideProjects/Alita_Robot/?ref=repository-badge"><img src="https://static.deepsource.io/deepsource-badge-light-mini.svg" alt="DeepSource"></a>
  <a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /> </a>
</p>

Patel Admin is a Telegram Group managment bot made using **[Pyrogram](https://github.com/pyrogram/pyrogram) _async version_** and **[Python](https://python.org)**, which makes it modern and faster than most of the exisitng Telegram Chat Managers.

**Patel's bot features over other bots:**
- Modern
- Fast
- Fully asynchronous
- Fully open-source
- Frequently updated
- Multi Language Support

Can be found on Telegram as [@pateladminbot](https://t.me/pateladminbot)
</br>

Patel's bot is currently available in 1 Language as of now:
- **US English**

More languages can be managed in the _locales_ folder.

We are still working on adding new languages.

## Requirements
- You need to have a *Mongo Database* (Cluster Preferred)
- Linux/Windows machine (Ubuntu/Debain-based OS Preferred or Windows 10/Server2016 and later)


## How to setup

First Step!
- Star **⭐** the repository!!

It really motivates me to continue this project further.

### Deploy to Heroku
- Get your `API_ID` and `API_HASH` from [here](https://my.telegram.org/)
- Get your Bot Token from [@BotFather](https://t.me/BotFather)

**Note:** As it is banned with an unknown reason in heroku, follow the below steps carefully!
- First Fork this repo :)
- secondly, create an empty app in the Heroku, with a custom app name; and select Europe region for faster speed.
- Now go to the deploy tab of your app and under deployment method select GitHub and connect it.
- after that, type the forked repo name and select it now select main branch and enable auto deploy, at last click on deploy now button!
- Lastly, you must fill up all the vars in heroku as directed in app.json file and now turn on the worker dyno to run it :)

### Traditional

- Install Python v3.7 or later from [Python's Website](https://python.org)
- Install virtualenv using `python3 -m pip -U install virtualenv`.
- **Fork** or Clone the project using `git clone https://github.com/jagug/pateladminv2.git`
- Create Virtualenv using: `virtualenv venv`
- Install the requirements using `python3 -m pip install -r requirements.txt`
- Fill in all the variables in *Development* class, not *Config* class. **Sudo, Dev, Whitelist** users are optional!!
- Change to virtualenv shell by using:
  `. venv/bin/activate` (Linux)
  `venv\Scripts\activate` (Windows)
- Run the bot using `python3 -m alita`

### Docker

- Clone the repo and enter into it
- Install [Docker](https://www.docker.com/)
- Fill in the `sample.env` file and rename it to `main.env`.
- Build the docker image using: `docker build -t alita_robot:latest .` (The dot '.' at last is necessary!)
- Run the command `docker run --env-file main.env alita_robot`


If all works well, bot should send message to the **MESSAGE_DUMP** Group!


## Contributing to the project

- Make sure your PR works and doesn't break anything.
- You must join the support group.
- Make sure it passes test using `make test`.


## Special Thanks to
- [AlphaBots](https://t.me/TheAlphaBotz)
### Copyright & License

* Copyright (C) 2020-2021 by [jagug](https://github.com/jagug) ❤️️
* Licensed under the terms of the [GNU AFFERO GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://github.com/jagug/Pateladminv2/blob/master/LICENSE)

## Powered By

[![Alpha bots](https://img.shields.io/badge/alpha-bots-green?style=for-the-badge&logo=appveyor)](https://t.me/TheAlphaBotz)
