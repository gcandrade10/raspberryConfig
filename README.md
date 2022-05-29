# raspberryConfig

To acces start up script

```
sudo nano /etc/rc.local
```

To set download demon

```
pip3 install cryptg
pip3 install Telethon>=1.24.0

replace 

#with TelegramClient(getSession(), api_id, api_hash, proxy=proxy).start() as client:
with TelegramClient(getSession(), api_id, api_hash,proxy=proxy).start(bot_token='') as client:


python3 telegram-download-daemon.py --api-id ___ --api-hash ___ --channel ___ --des ___

```
