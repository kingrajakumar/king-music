

## Commands 🛠

- `/play <song name>` - play song you requested
- `/song <song name>` - download songs you want quickly

#### Admins Only 👷‍♂️
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play

## Heroku Deployment 💜
The easy way to host this bot, deploy to Heroku, Change the app country to Europe (it will help to make the bot stable).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kingrajakumar/king-music)

## ᴅᴇᴘʟᴏʏ ᴏɴ ᴠᴘꜱ ꜱᴇʀᴠᴇʀ 📡

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/HEXOROP/eSportMusicX # Clone your repo.
cd eSportMusicX
pip3 install -U -r requirements.txt
cp example.env .env #Use vim to edit ENVs
vim .env #Fill up your ENVs ( Steps press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file.)
p
