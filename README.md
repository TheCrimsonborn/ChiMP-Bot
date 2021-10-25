# ChiMP

### A Music Player Bot for Discord Servers

```
Requirements:

Binaries

- Python 3.8 or greater 
- ffmpeg
- Git 

Python packages:
- python3 -m pip install -r requirements.txt

Ubuntu Server
```
#### Basic Installation

```
sudo apt-get update -y && sudo apt-get upgrade -y

sudo apt-get dist-upgrade -y

sudo apt-get autoremove -y

sudo apt install software-properties-common -y

sudo add-apt-repository ppa:deadsnakes/ppa

sudo apt install python3.10 -y

sudo apt-get install ffmpeg -y

sudo apt-get install git -y

sudo apt-get install screen -y

sudo apt-get install python3-pip -y

python3 -m pip install --upgrade pip setuptools wheel

python3 -m pip install --upgrade pip

```

#### How to Create a Discord Bot Account

Use [this tutorial](https://www.freecodecamp.org/news/create-a-discord-bot-with-python/) for creating bot account.

#### How to Create a Discord Bot Account
If you want play Spotify musics, you need Spotify's CliendID & Client Secret

This article will help you. [Development Guides of Spotify](https://developer.spotify.com/documentation/general/guides/authorization/app-settings/)

#### Bot Setup

```
git clone 

cd chimp bot

python3 -m pip install -r requirements.txt

edit the "client_id", "client_secret", "spotify_client_id", "spotify_client_secret" with 'nano' or 'vim' or you FTP connection 

screen -AmdS chimp python3 chimp.py
```
