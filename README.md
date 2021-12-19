# Telegram-send<br>
Basic script to send telegram messages

**Install**<br>
Copy this file in the BIN directory and give it executable rights<br>
<code>sudo cp telegram-send /usr/bin/telegram-send</code><br>
<code>sudo chmod +x /usr/bin/telegram-send</code>

**First run**<br>
<code>sudo telegram-send</code><br>
A config file will be created: <b>telegram-send.conf</b><br>
this file needs to contains the Telegram ID for this bot (https://www.trebnie.nl/ict-tips/telegram/)<br>
you can add user to this file with there Telegram ID

**Pictures**<br>
Telegram send<br>
<img src="https://trebnie.nl/_github/telegram_send.png" alt="telegram send"><br>

Telegram unknown user (case sensitive)<br>
<img src="https://trebnie.nl/_github/telegram_unknown.png" alt="telegram unknown"><br>

**Execute**<br>
<code>telegram-send -h</code> (help)<br>
<code>telegram-send -c</code> (view contactlist)<br>
<br>
You can now send a telegram:<br>
<code>telegram-send bertman "hello"</code><br>
<code>telegram-send michel "hello"</code><br>

<br>
Example scripts: https://github.com/bertman80/telegram

**Error**<br>
When you get this error, you need to run it first as sudo to create a conf file<br>
touch: cannot touch '/usr/bin/telegram-send.conf': Permission denied<br>
/usr/bin/telegram-send: line 26: /usr/bin/telegram-send.conf: Permission denied<br>
/usr/bin/telegram-send: line 27: /usr/bin/telegram-send.conf: Permission denied<br>
/usr/bin/telegram-send: line 28: /usr/bin/telegram-send.conf: Permission denied<br>
