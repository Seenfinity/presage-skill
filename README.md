# ⚔️ Presage Skill for OpenClaw

> Trade prediction markets on Solana using AI-powered analysis

[![ClawHub](https://img.shields.io/badge/Available%20on-ClawHub-blue?style=flat-square)](https://clawhub.ai/Seenfinity/presage)
[![GitHub Repo](https://img.shields.io/badge/GitHub-seenfinity%2Fpresage--skill-blue?style=flat-square)](https://github.com/Seenfinity/presage-skill)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)

---

## What is Presage?

[Presage](https://presage.market) is an AI-powered prediction market terminal on Solana. Trade YES/NO outcomes on real-world events — sports, politics, tech, crypto, and more.

This skill integrates Presage with OpenClaw, allowing your AI agent to:
- 📊 Analyze markets and find trading opportunities
- 📈 Get portfolio balances and positions
- 🔍 Identify mispriced markets
- 📉 Make data-driven trading decisions

---

## Installation

### From ClawHub (recommended)

```bash
clawhub install presage
```

### Manual

```bash
cd /path/to/your/workspace/skills
git clone https://github.com/Seenfinity/presage-skill.git presage
```

---

## Configuration

The skill requires a Presage API key:

1. Get your API key from [presage.market](https://presage.market/api)
2. Add it to your OpenClaw environment or config

The skill will automatically connect to the Presage API and provide market analysis tools.

---

## Features

### Market Analysis
- Fetch live market data (prices, volumes, open interest)
- Analyze market trends and liquidity
- Identify trading opportunities

### Portfolio Management
- Check account balance
- View open positions
- Track P&L

### Smart Trading
- Find mispriced markets (spread analysis)
- Compare odds across markets
- Risk assessment tools

---

## Usage

Once installed, the skill provides these tools:

```
analyzeMarkets    → Get overview of all active markets
analyzeMarket(id) → Deep dive into specific market
getPortfolio      → Your balance and positions
findOpportunities → Scan for mispriced markets
```

---

## Example

```
> What markets have high volume today?
→ [Analysis of top markets by volume]

> Check my portfolio
→ [Your USDC balance and positions]

> Find undervalued markets
→ [Markets where YES/NO prices seem misaligned]
```

---

## Requirements

- OpenClaw (or any compatible agent platform)
- Node.js 18+
- Presage API key

---

## Tech Stack

- **Runtime**: OpenClaw agent
- **API**: Presage REST API
- **Language**: JavaScript

---

## Contributing

1. Fork the repo
2. Create a feature branch
3. Submit a PR

---

## License

MIT © 2026 Seenfinity

---

## Links

- 🌐 [Presage Market](https://presage.market)
- 🦞 [ClawHub Skill](https://clawhub.ai/Seenfinity/presage)
- 📂 [GitHub Repo](https://github.com/Seenfinity/presage-skill)
- 💬 [Colosseum Agent](https://colosseum.com/agent-hackathon/projects/presage)
