# telegram_send<br>
basic script to send telegram messages

**Install**<br>
copy this file in the BIN directory and give it executable rights<br>
sudo cp telegram_send /usr/bin/telegram-send<br>
sudo chmod +x /usr/bin/telegram-send

**First run**<br>
sudo telegram_send<br>
a config file will be created: telegram_send.conf<br>
this file needs to contains the Telegram ID for this bot (https://www.trebnie.nl/ict-tips/telegram/)<br>
you can add user to this file with there Telegram ID

**Execute**<br>
you can now send a telegram:<br>
telegram_send bertman "hello"<br>
telegram_send michel "hello"
