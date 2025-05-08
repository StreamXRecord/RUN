
# How To Run




## Run it on VPS debian (make sure the region its SG)

Go to the project directory

```bash
  cd bot-directory-name
```

Install dependencies

```bash
  apt install ffmpeg
```

Install enviroment

```bash
  sudo apt install python3.12 python3.12-venv
```

make enviroment

```bash
  python3 -m venv venv
```

go to enviroment

```bash
  source venv/bin/activated
```

install requirements.txt
```bash
pip3 install -r requirements.txt
```

change configs.json with ur evinroment variable

```bash
nano configs.json
```
input your enviroment
```json
{
    "apiHash": "358aabf65e3ddf4ce3c2796121d147", //get from https://my.telegram.org
    "apiId": 2071669, ////get from https://my.telegram.org
    "botToken": "8049465670:AHdq3KpnIbC5Qjbx0cv9RXQw2YSwterIA", //get from @BotFather in
    "admin": [3422242] // get from @getmyid_bot
}
```
Tutorial get apiId and apiHash
[![youtube](https://img.shields.io/badge/youtube-red?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=tzYTLjdr7rI)

Tutorial get bot token from @botToken
[![youtube](https://img.shields.io/badge/youtube-red?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/EOke01hZgZ0?si=Q7efRa2DXmL4YQzI)

## Running Bot

Run  app.py
```bash
  nohup python3 -u app.py > app.log 2>&1 &
```

And then run the bot

Run bot.py
```bash
  nohup python3 -u bot.py > bot.log 2>&1 &
```
