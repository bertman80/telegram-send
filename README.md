# telegram-send<br>
basic script to send telegram messages

**Install**<br>
copy this file in the BIN directory and give it executable rights<br>
sudo cp telegram-send /usr/bin/telegram-send<br>
sudo chmod +x /usr/bin/telegram-send

**First run**<br>
sudo telegram_send<br>
a config file will be created: telegram-send.conf<br>
this file needs to contains the Telegram ID for this bot (https://www.trebnie.nl/ict-tips/telegram/)<br>
you can add user to this file with there Telegram ID

**Execute**<br>
telegram-send -h (help)<br>
telegram-send -c (view contactlist)<br>
<br>
you can now send a telegram:<br>
telegram-send bertman "hello"<br>
telegram-send michel "hello"

**Error**<br>
When you get this error, you need to run it first as sudo to create a conf file<br>
touch: cannot touch '/usr/bin/telegram-send.conf': Permission denied<br>
/usr/bin/telegram-send: line 26: /usr/bin/telegram-send.conf: Permission denied<br>
/usr/bin/telegram-send: line 27: /usr/bin/telegram-send.conf: Permission denied<br>
/usr/bin/telegram-send: line 28: /usr/bin/telegram-send.conf: Permission denied<br>
