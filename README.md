# HNParser
Parsing Hacker News and sending results per email

Installation:
```
1. git clone
2. cd HNParser/
3. python3 -m venv venv # create virtual environment
4. . venv/bin/activate (.fish # if you're using fish)
5. pip3 install -r requirements.txt
```

Important: In order to be able to send email you will need to get an App Password from Gmail:
1. Go to Google Accounts Page
2. Turn on the 2-step verification.
3. Security > App passwords https://i.stack.imgur.com/Vvl2H.png![image](https://user-images.githubusercontent.com/105520646/232308460-a5701487-0b35431ea8fa-4da26b7ff51b.png)
4. Select "Other apps" from the app menu.
- Copy App Password and open daily_hnews.py
5. Paste App Password to YOUR_APP_PASSWORD_GMAIL
6. Paste your email adress to YOUR_EMAIL_TO_SEND_FROM
7. Paste receiver email to EMAIL_TO_RECEIVE

Usage:

python3 daily_hnews.py
