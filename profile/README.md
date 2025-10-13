<div align="center">

# 🚀 DV.net Merchant

### Free, open‑source crypto payments processing

<br>
<img src="assets/01.main-banner.png" alt="DV.net Banner" width="100%">
<br>
<br>

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Go Version](https://img.shields.io/badge/Go-1.24.4+-00ADD8?logo=go)](go.mod)
[![Version](https://img.shields.io/badge/Version-0.9.7-green.svg)](CHANGELOG.md)
[![Documentation](https://img.shields.io/badge/Docs-docs.dv.net-orange)](https://docs.dv.net)

[🇬🇧 English](https://github.com/dv-net/.github/blob/main/profile/README.md) • [🇷🇺 Русский](https://github.com/dv-net/.github/blob/main/profile/ru/README.md) • [🇨🇳 中国人](https://github.com/dv-net/.github/blob/main/profile/zh/README.md)

[Website](https://dv.net) • [Docs](https://docs.dv.net) • [API](https://docs.dv.net/en/operations/post-v1-external-wallet.html) • [Support](https://dv.net/#support)

</div>

<br>

---

<br>

## 💡 About the project

**DV.net** is a completely free crypto payment processor to receive and send crypto on your website. <br>
You pay **network fees only** — no middlemen and no hidden charges.

<br>

### ⚡ Why DV.net?

<div>

> #### 🔓 **Open Source**  [ Auditable security by anyone ]


> #### 💰 **Zero Fees** ( Only the network fee )

> #### 🔐 **Non‑custodial** [ You keep full control of keys ]

> #### ⚙️ **Self‑hosted** [ Or use the managed cloud ]

</div>

<br>

## ✨ Features

<div>

### 🎯 Core
- ✅ **Zero platform fees** — you pay the network only
- ✅ **Open Source** — verifiable codebase
- ✅ **Non‑custodial** — your keys, your coins
- ✅ **No KYC/KYB** — skip bureaucracy

### 🔧 Technical
- ✅ **Payout API** to send crypto
- ✅ **CEX support** (Binance, HTX, OKX, etc.)
- ✅ **Self‑hosted** or Cloud
- ✅ **TRON delegation**

</div>

<br>

## 💎 Supported cryptocurrencies

<div align="center">

<img src="assets/icons/coins/IconBtcBitcoin.png" style="width: 24px; vertical-align: middle;"> **Bitcoin** &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/coins/IconTrxTron.png" style="width: 24px; vertical-align: middle;"> **TRON** &nbsp;&nbsp;&nbsp;&nbsp; 
<img src="assets/icons/coins/IconEthEthereum.png" style="width: 24px; vertical-align: middle;"> **Ethereum** &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/coins/IconBsc.png" style="width: 24px; vertical-align: middle;"> **BNB Chain** &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/coins/IconLtcLitecoin.png" style="width: 24px; vertical-align: middle;"> **Litecoin** &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/coins/IconDogeDogecoin.png" style="width: 24px; vertical-align: middle;"> **Dogecoin** &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/coins/IconArbArbitrum.png" style="width: 24px; vertical-align: middle;"> **Arbitrum** &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/coins/IconPolPolygon.png" style="width: 24px; vertical-align: middle;"> **Polygon** &nbsp;&nbsp;&nbsp;&nbsp;

**And other popular cryptocurrencies...**

</div>

<br>

### 🏦 Supported exchanges (CEX)
<div align="center">
<img src="assets/icons/exchanges/binance.png" style="width:24px; vertical-align:middle;" alt="Binance"> <strong>Binance</strong> &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/exchanges/htx.png" style="width:24px; vertical-align:middle;" alt="HTX"> <strong>HTX</strong> &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/exchanges/okx.png" style="width:24px; vertical-align:middle;" alt="OKX"> <strong>OKX</strong> &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/exchanges/kukoin.png" style="width:24px; vertical-align:middle;" alt="KuCoin"> <strong>KuCoin</strong> &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/exchanges/bybit.png" style="width:24px; vertical-align:middle;" alt="Bybit"> <strong>Bybit</strong> &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/exchanges/bitget.png" style="width:24px; vertical-align:middle;" alt="Bitget"> <strong>Bitget</strong> &nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/icons/exchanges/gate.png" style="width:24px; vertical-align:middle;" alt="Gate"> <strong>Gate</strong> &nbsp;&nbsp;&nbsp;&nbsp;
</div>

<br>

## 🎬 Live demo

Try the product with real transactions:

<div align="center">

### [🎮 Demo Admin](https://demo.dv.net/dv-admin/dashboard) • [💳 Demo Checkout](https://demo.dv.net/pay/wallet/7d029e2e-840b-46f8-b898-2694306d119d?amount=15)

</div>

<br>

## 🚀 Installation options

### 🖥️ Self‑Hosted
**Full control over your data**

**OS:** Linux (Ubuntu 22.04+, Debian 12, CentOS 9)  
**Requirements:** 4 CPU, 4 GB RAM, 30 GB NVMe SSD

```bash
sudo bash -c "$(curl -fsSL https://dv.net/install.sh)"
```

**✅ Production‑ready**  
**✅ Maximum security**  
**✅ No monthly fees**

[📖 Learn more](https://docs.dv.net) • [⚙️ Setup](https://docs.dv.net/en/installation/installation.html)

---

### 🖥️ Cloud

**Fastest way to start**

**Time to go live:** 5 minutes  
**Support:** 24/7

[🚀 **Start now**](https://cloud.dv.net/dv-admin/auth/sign-up)

**✅ No installation**  
**✅ Managed solution**  
**✅ Support included**

[📖 Documentation](https://docs.dv.net)

---

### 🐳 Docker

**For developers**

**Time to run:** 2 minutes  
**Result:** `localhost:80`

```bash
git clone --recursive https://github.com/dv-net/dv-bundle.git
cd dv-bundle && cp .env.example .env
docker compose up -d
```

**✅ Local development**  
**✅ Local testing**  
**✅ Demos**

[💻 GitHub](https://github.com/dv-net/dv-bundle)


---

### 🖥️ Self‑Hosted installation

Full control over data and infrastructure. Recommended for production.

**System requirements:**
- **OS:** CentOS 9, Debian 12, Ubuntu 22.04, Ubuntu 24.04
- **CPU:** 4 cores
- **RAM:** 4 GB
- **Disk:** 30 GB NVMe SSD
- **Network:** Open ports 80, 443

**One‑liner install:**

```bash
sudo bash -c "$(curl -fsSL https://dv.net/install.sh)"
```

The installer will:
- Check system requirements
- Install dependencies
- Configure the database
- Start all services

> **⚠️ Important:** If firewall is enabled, open ports `80` and `443`:
> ```bash
> sudo ufw allow 80/tcp
> sudo ufw allow 443/tcp
> ```

**After installation:**

1. Open in the browser:
    - `https://your-domain.com` (if a domain is configured)
    - `http://your-ip-address` (if using IP)

2. You’ll see the setup wizard welcome screen

3. Create the admin user

4. Log in to the dashboard

5. Connect your exchange (Binance, HTX, OKX, etc.)

6. Start accepting crypto!

**Benefits:**
- ✅ Full data ownership
- ✅ Maximum security
- ✅ Customizable
- ✅ Independent from cloud providers
- ✅ No monthly fees

**Great for:**
- 🎯 Enterprises with strict security
- 🎯 Teams with own infrastructure
- 🎯 Projects with privacy requirements

**More setup options:**

Full installation docs: [docs.dv.net](https://docs.dv.net)

<br>

## 📚 Documentation

<div align="center">

### 📖 [Full documentation](https://docs.dv.net)
Guides for installation, configuration and usage

### 🔌 [API Reference](https://docs.dv.net/en/operations/post-v1-external-wallet.html)
Integration and API usage docs

### 💬 [Support 24/7](https://dv.net/#support)
Telegram, WhatsApp, WeChat, Email — we're always online

</div>

<br>

## 🔐 Security

### How we protect your funds

1. **🔒 Non‑custodial** — wallets live on your side only, we have no access
2. **⚡ Immediate settlement** — funds go straight to your exchange or wallet
3. **🏠 Self‑hosted** — full control on your own server
4. **🔍 Open Source** — anyone can audit the code

<br>

## 🛠 Development

For developers who want to contribute:

```bash
# Clone the repository
git clone https://github.com/dv-net/dv-merchant.git
cd dv-merchant

# Download dependencies
go mod download

# Run tests
make test

# Lint code
make lint

# Build
make build
```

See more in [dv-merchant](https://github.com/dv-net/dv-merchant) for developers.

<br>

## 🤝 Support the project

<div align="center">

> ### ⭐ Star on GitHub
> Give us a star if this project helps you

> ### 🐛 Report a bug
> Help us get better

> ### 💡 Suggest an idea
> Your ideas matter

> ### 🔧 Contribute
> Pull requests are welcome

</div>

<br>

## 📞 Contacts

<div align="center">

**Telegram:** [@dv_net_support_bot](https://t.me/dv_net_support_bot) • **Email:** [support@dv.net](https://dv.net/#support)

**Website:** [dv.net](https://dv.net) • **Documentation:** [docs.dv.net](https://docs.dv.net)

</div>

<br>

## 📄 License

This project is released under the [MIT](LICENSE) license.

<div align="center">

**© 2025 DV.net** • [DV Technologies Ltd.](https://dv.net)

*Built with ❤️ for the crypto community*

</div>
