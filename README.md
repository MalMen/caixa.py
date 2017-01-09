![caixa.py](http://i.imgur.com/XOeQUG9.png)
# Welcome to caixa.py

This is a very simple script that gives you the latest transactions for your CaixaDirecta Account.
- Gives you your current account balance.
- Gives you a list of your last transactions
- Sends an alerts using [Pushbullet](https://www.pushbullet.com) or [Nexmo SMS](https://www.nexmo.com)

Before using
------------
1. install [phantomjs](http://phantomjs.org/download.html)
2. configure the config.py file with the alerts details ([Pushbullet](https://www.pushbullet.com) API or [Nexmo SMS](https://www.nexmo.com) API)

Basic usage
------------
Simply put your account details as arguments when calling the script:
```bash
python caixa.py -u [username] -p [password]
```

To do list
----------
- [x] Add sms alert
- [ ] Scan more then 1 account
- [ ] Generate an Excel table with all the transactions

