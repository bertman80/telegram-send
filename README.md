# telegram_send
basic script to send telegram messages

**Install**

copy this file in the BIN directory and give it executable rights
sudo cp telegram_send /usr/bin/telegram-send
sudo chmod +x /usr/bin/telegram-send

**First run**

sudo telegram_send
a config file will be created: telegram_send.conf
this file needs to contains the Telegram ID for this bot (https://www.trebnie.nl/ict-tips/telegram/)
you can add user to this file with there Telegram ID

**Execute**

you can now send a telegram:
telegram_send bertman "hello"
telegram_send michel "hello"
