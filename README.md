# Evoevo Auto Bot Scripts 🚀

This collection of Python scripts empowers you to interact seamlessly with the Evoevo platform, a blockchain-based system for Ethereum wallet automation. The core script, `main.py`, offers automation and multi-account support for core Evoevo activities.

🔗 Register: [Evoevo](https://evoevo.ai/invite?inviteCode=VDXYDSN7)

## ✨ Features Overview

### General Features

- **Multi-Account Support**: Reads private keys from `pvkey.txt` to perform actions across multiple accounts.
- **Central Menu System**: Interactive menu for easy script selection via `main.py`.
- **Colorful CLI**: Uses `colorama` for visually appealing output with colored text and borders.
- **Asynchronous Execution**: Built with `asyncio` for efficient blockchain interactions.
- **Error Handling**: Comprehensive error catching for blockchain transactions and RPC issues.
- **Bilingual Support**: Supports both English and Vietnamese output based on user selection.
- **Proxy Support**: Supports HTTP, HTTPS, and SOCKS5 proxies for network requests.

### Included Scripts

✨ **Account Management** (`scripts/account.py`)

- ✅ Profile information retrieval
- ✅ Favorites management
- ✅ Balance checking (points & cash)
- ✅ Referral tracking
- ✅ Rewards distribution tracking
- ✅ Invite code redemption

✨ **Agent Management** (`scripts/agent.py`)

- ✅ Agent creation
- ✅ Agent configuration management
- ✅ Agent summary and status
- ✅ Multi-agent support

✨ **Auto Referral** (`scripts/autoreff.py`)

- ✅ Automatic creation of new Ethereum wallets
- ✅ Automatic redemption of invite codes
- ✅ Displays wallet information and personal codes
- ✅ Supports multi-threading
- ✅ Supports proxy (HTTP, HTTPS, SOCKS5)

✨ **Register & Bind** (`scripts/bind.py`)

- ✅ Wallet registration
- ✅ Onchain transaction binding
- ✅ Multi-wallet support
- ✅ Proxy support

✨ **Blindbox Management** (`scripts/blindboxes.py`)

- ✅ Check blindbox status
- ✅ Open blindboxes
- ✅ Display blindbox rewards
- ✅ Multi-wallet support

✨ **Topics & Oracle** (`scripts/topics.py`)

- ✅ Topics management
- ✅ Oracle interactions
- ✅ Opinion submission
- ✅ Multi-wallet support

✨ **Withdraw Funds** (`scripts/withdraw.py`)

- ✅ Check balance (cash & points)
- ✅ Automatic withdrawal
- ✅ Transaction hash display
- ✅ Multi-wallet support

## 🛠️ Prerequisites

Before running the scripts, ensure you have the following installed:

- Python 3.8+
- `pip` (Python package manager)
- **Dependencies**: Install via `pip install -r requirements.txt` (ensure `eth-account`, `aiohttp`, `aiohttp-socks`, `colorama`, and `inquirer` are included).
- **pvkey.txt**: Add private keys (one per line) for wallet automation.
- **proxies.txt** (optional): Add proxy addresses for network requests, if needed.

## 📦 Installation

1. **Clone this repository:**
   ```sh
   git clone https://github.com/thog9/Evoevo-ai.git
   cd Evoevo-ai
   ```
2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Prepare Input Files:**
   - Open `pvkey.txt` in the root directory and add your private keys (one per line):
   ```sh
   nano pvkey.txt 
   ```
   Format:
   ```
   0x1234567890abcdef...
   0xabcdef1234567890...
   ```
   - Create `proxies.txt` for specific operations (optional):
   ```sh
   nano proxies.txt
   ```
   Format: `ip:port:user:pass` (one per line)
   Example:
   ```
   http://username:password@proxy.com:8080
   socks5://username:password@proxy.com:1080
   ```
4. **Run:**
   ```sh
   python main.py
   ```
   - Choose a language (Vietnamese/English).
   - Select the script you want to run.

**Language Selection:**
- Choose between Vietnamese (Tiếng Việt) and English
- All scripts support bilingual output

## 📁 Project Structure

```
Evoevo/
├── main.py              # Central menu system
├── pvkey.txt            # Private keys file
├── proxies.txt          # Proxies file (optional)
├── requirements.txt     # Python dependencies
├── README.md            # This file
└── scripts/             # Individual scripts
    ├── account.py       # Account management
    ├── agent.py         # Agent management
    ├── autoreff.py      # Auto referral
    ├── bind.py          # Register & bind
    ├── blindboxes.py    # Blindbox management
    ├── topics.py        # Topics & oracle
    └── withdraw.py      # Withdraw funds
```

## 📨 Contact

Connect with us for support or updates:

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099) 

----

## ☕ Support Us

Love these scripts? Fuel our work with a coffee!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)

🔗 WEBSITE: [BUY SCRIPTS](https://thogtoolhub.com/)
