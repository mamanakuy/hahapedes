# HAHA Wallet BOT
HAHA Wallet BOT

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Claim Daily Karma Points
  - Auto Complete Available Tasks
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/mamanakuy/hahapedes.git
   ```
   ```bash
   cd hahapedes
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

edit data di file accounts.joson :
```bash
   nano accounts.json
   ```

contoh isi file yang dibuka:
  ```bash
    [
        {
            "Email": "Your Email Address 1",
            "Password": "Your Password 1"
        },
        {
            "Email": "Your Email Address 2",
            "Password": "Your Password 2"
        }
    ]
  ```

jika ingin menggunakan proxy:
  - **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```
