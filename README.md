# Paws bot ~ Gangster@Shortcut For Life

## Features

This is autobot for Paws and can run with the following features:
- **Multi-accounts Support:** Automate actions across multiple accounts. 
- **Auto Complete Task:** Automatically perform available quest
- **Configurable Settings:** Control various aspects of the script via a `config.json` file.
- **Auto connect wallets**

## Registrations 

 [Click Here => Paws Telegram](https://t.me/PAWSOG_bot/PAWS?startapp=I4LVa5Tt)



## Installation

Install Paws bot with the following commands:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GangsterGpc/Paws.git
   ```
2. **Open file directory:**
   ```bash
   cd Paws
   ```
3. **Create and activate a virtual environment:**
    ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
   **On window** 
   ```bash
   venv\Scripts\activate
   ```   
4. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```   

## Configuration
Create a `config.json` file in the root directory with the following structure:
   ```json
{
    "connect_wallets": false,
    "account_delay": [5, 10],
    "cycle_delay": [14400, 28800]
}
   ```

`connect_wallets` - `true` / `false` - if you want to connect wallets, add the addresses of TON wallets to wallets.txt . The number of wallets must match the number of accounts. 

Example of an address - `UQAIsAepLajIsWU58DxPTM7D_GQG01MSk63qJckHQ9WBj2QC`

`delay_account`: Delay between processing different accounts (in seconds) - the minimum and maximum values are taken randomly

`cycle_delay`: Delay between different cycles of operations (in seconds) - the minimum and maximum values are taken randomly

## Add Proxy List

Add your proxy list in `proxies.txt` and proxy format is like example below :
```bash
http://host:port
http://user:pass@host:port
```

## Input your telegram (query_id / user_id)

Get your telegram query_id / user_id with the following steps:
1. Login telegram via portable or web version
2. Launch the bot
3. Open developer tools 
4. Open Application tab
5. Click session storage and copy the value of query_id / user_id
6. Input your ID to ` query.txt ` by the following command:

   ```bash
   nano query.txt
   ```

## Add wallets address
Add your TON nertwork wallet address in `wallets.tst` by the following command:
   ```bash
   nano wallets.txt
   ```

## Operation Usage
1. **Update the Paws bot:**
   ```bash
   git pull 
   ```
2. **Run Bot:**   

   ```bash
   python3 bot.py
   ```


## Support To Bot
If you would like to support the development of this project, you can make a donation using the following addresses:

-  SOL : 
   ```bash
   EzygNQeDii8wRjgBoSfQGEXCMsCsNByN3v8UWNCmY2Mz
   ```
-  BTC: 
   ```bash
   bc1ph5r3gvwkyjchqka236j720qnhxmhzn565qpm226kdjrj47p89ghslq3u5p
   ```
-  ETH : 
   ```bash
   0x15E51a3bD6f76eA525659fD356223052E32741d1
   ```
-  TON : 
   ```bash
   UQDok55Rh71Ycfh50sLEjkYxhgriJB9PDFuURVFVNpw_orKf
   ```

## Contacts
For questions or support, please click and contact me.

[![GitHub](https://img.icons8.com/color/96/github--v1.png)](https://github.com/GangsterGpc)
[![YouTube](https://img.icons8.com/color/96/youtube-play.png)](https://www.youtube.com/@Shortcut_4_Life)
[![X](https://img.icons8.com/nolan/96/twitterx.png)](https://x.com/gangster_gpc)
[![Facebook](https://img.icons8.com/fluency/96/facebook.png)](https://facebook.com/shortcut4life)
[![Discod](https://img.icons8.com/color/96/discord-new-logo.png)](https://discord.com/channels/@gangster_gpc)
