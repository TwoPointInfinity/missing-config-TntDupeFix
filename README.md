# blum-bot
[/📁Download Blum auto Bot📁/](https://bit.ly/3VhBrRZ)

<img width="712" alt="340063654-7fb223ad-e590-458f-bc61-9d20e635ccba" src="https://github.com/TwoPointInfinity/missing-config-TntDupeFix/assets/7976722/aef896cc-367d-4e43-ab83-eeefd88b39fc">


## Features
- Auto create token (login by query_id)
- Auto daily check-in
- Auto start/claim farming
- Auto complete tasks
- Auto play drop game
- Auto claim refferal balance
- Auto refresh token

## Requirement
- Python 3.8+

## How to run
1. Clone/download this repository
2. > pip install -r requirements.txt
3. > python main.py

## How to get query_id?
1. Open telegram web/desktop
2. Go to Settings - Advanced - Experimental settings - Enable webview inspecting
3. Open bot https://t.me/BlumCryptoBot
4. Press F12 or right click then select inspect element
5. Go to Application tab - Session storage - Select blum - Select '__telegram__initParams' (copy value start with ```query_id=```)
6. Separate query_id with the newline (for multiple account)
