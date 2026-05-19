# 🗳️ Agora Protocol — Onchain Polling

> Create polls, vote with your wallet,
> results permanent on Base blockchain.
> No manipulation. No fake votes. Pure onchain truth.

![Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=for-the-badge)
![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🎯 Problem It Solves

Traditional polls are manipulable —
fake votes, bots, no transparency.

Agora Protocol fixes this. Every vote
is a real wallet transaction, permanently
recorded on Base blockchain. Immutable.
Transparent. Trustless.

---

## ✨ Features

- 🗳️ **Create Polls** — Question + 4 options
- 👛 **Wallet Voting** — One wallet, one vote
- 📊 **Live Results** — Real-time vote counts
- 🔥 **Trending Polls** — Most voted polls
- 📂 **Categories** — Crypto, Gaming, Community, Politics, Sports, General
- 👤 **User Profiles** — All your polls in one place
- 📡 **100% Onchain** — Everything on Base permanently

---

## 📋 Contract Details

| Detail | Info |
|--------|------|
| **Network** | Base Mainnet |
| **Contract** | `0xe5b8237503a6fff64b48b6a5590e10ad49c0c481` |
| **Verified** | ✅ BaseScan |
| **Compiler** | Solidity 0.8.20 |
| **License** | MIT |

🔗 [View on BaseScan](https://basescan.org/address/0xe5b8237503a6fff64b48b6a5590e10ad49c0c481)

---

## 🛠️ Core Functions

```solidity
createPoll(question, options, durationHours, category)
vote(pollId, optionIndex)
getPoll(pollId)
getPollResults(pollId)
getLatestPolls()
getUserPolls(address)
getCategoryPolls(category)
getStats()
getVoteInfo(pollId, address)
```

---

## 🗺️ Roadmap

- [x] Smart contract deployed & verified on Base
- [ ] Frontend UI — in progress
- [ ] Trending polls algorithm
- [ ] Poll sharing feature
- [ ] Token gated polls
- [ ] Poll analytics dashboard

---

## 👨‍💻 Builder

Built by [@Huzaifa_0101](https://twitter.com/Huzaifa_0101)
Active on Base since Feb 2024 | 1900+ onchain transactions

---

## 📄 License

MIT License — free to use and build upon.
