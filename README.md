# Kite AI Automation BOT V2.0 (PYTHON)

Fully automated bot to interact with **Kite AI Ozone** tasks on the testnet!  
Sign up, complete social tasks, faucet claims, quizzes, and earn testnet rewards — fully automated. 🤖

- 🌐 Register Here: [Kite AI Ozone](https://testnet.gokite.ai?referralCode=ODMG4EWE)
- 🧠 Connect New EVM Wallet
- 💬 Connect Social Media
- ✅ Complete Available Daily Tasks

---

## ⚙️ Features

- ✅ Auto Get Account Info
- ✅ Proxy Modes  
  - Public Proxy via [Proxyscrape](https://proxyscrape.com/free-proxy-list) (Choose 1)  
  - Private Proxy (Choose 2)  
  - No Proxy (Choose 3)  
- 🔄 Auto Rotate Invalid Proxies (Yes / No)
- 💧 Auto Faucet Claim *(Requires 2captcha Key)*
- 📚 Auto Daily Quiz Completion
- 💸 Auto Stake & Unstake KITE Tokens
- 🤖 Auto Interact With Kite AI Agents (30x)
- 👥 Multi-Account Threading Support

---

## 📦 Requirements

- Python 3.9+  
- `pip` installed  
- Optional: 2captcha API key

---

## 🔧 Installation

1. **Clone This Repository**
```bash
git clone https://github.com/cryptodai3/Kite-Ai-Automation-Bot.git
cd Kite-Ai-Automation-Bot
````

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

> 💡 *If you encounter version errors (e.g., eth-account, cryptography), fix manually:*

* Check current version:

```bash
pip show eth-account
```

* Uninstall conflicting library:

```bash
pip uninstall eth-account
```

* Install correct version:

```bash
pip install eth-account==VERSION
```

---

## 🛠️ Configuration

* `nano accounts.txt` — EVM Wallets (EOAs):

```txt
your_wallet_address_1
your_wallet_address_2
```

* `nano 2captcha_key.txt` — 2Captcha API Key (for faucet claim):

```txt
your_2captcha_key
```

* `nano proxy.txt` — Add your proxies:

```txt
ip:port
http://ip:port
http://user:pass@ip:port
```

---

## 🚀 Running the Bot

```bash
python bot.py
# or
python3 bot.py
```

Follow the on-screen prompts to choose proxy mode, captcha setup, and execution method.

---
## Happy Farming! 🚀🌾

*Brought to you by [CryptoDai3](https://t.me/cryptodai3) X [YetiDAO](https://t.me/YetiDAO)*

---

## ☕ Buy Me a Coffee

* **EVM:** `0x49bb35693e9631760d2f3519e7db1dd618580a6a`
* **TON:** `UQDDYNRWZI12zMfXYBoy300ydECC5uouMUFLd_yZa6ZO4Jsm`
* **SOL:** `2PhLDFnyX8whHDMBbfGSFoLnVEsei6TYxyiqpDzPGyT1`
* **SUI:** `0xf3b008f8aac4b92195176aad27a892c565c216fd5c07bc99c70edb8394e23b59`

---

## 🔒 Safety & Support

### ⚠️ Important Disclaimer

* **Testnet Only** – This tool is designed for testnet environments only
* **No Liability** – Use at your own risk. Developers assume no responsibility
* **DYOR** – Always do your own research before using any automation tools

### 🛡️ Security Best Practices

* 🔐 Never use Main wallets
* 🚫 Never expose sensitive credentials
* 📜 Always review code before execution
* 💸 Use burner wallets with test tokens only

---

### 🙌 Support Our Work

Love this tool? Help us improve:

* ⭐ Star the repository
* 🔗 Share with your farming community
* 💎 Use our referral codes (where applicable)
* 💡 Contribute ideas and code

---
