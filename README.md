# 🐦 TweetSol

**TweetSol** is a Solana-integrated Twitter bot that allows users to interact with the blockchain directly through tweets. Users can send SOL, check balances, swap tokens, stake, and more—just by tweeting at @TweetSolBot.

---

## 🚀 Project Phases

### ✅ Phase 1: MVP
- Wallet linking via DM
- Sending SOL via tweet command
- Checking wallet balance
- Basic rate limiting & security
- Custodial and non-custodial wallet options

### 🛠️ Phase 2: Core Features
- Token swaps via Jupiter Aggregator
- Staking support (Marinade)
- Tweet parsing enhancements
- Web dashboard (React + Tailwind)

### 🌱 Phase 3: Growth & Gamification
- NFT milestone rewards
- Leaderboards & badges
- Referral system
- Airdrop claiming UI

### 🔗 Phase 4: Ecosystem Expansion
- White-label bots for DAOs
- NFT mint/list via tweet
- Governance voting
- Mobile companion app

---

## 🧠 Tech Stack

- **Backend:** Node.js, Express, Solana Web3.js
- **Frontend (Phase 2+):** React + TailwindCSS
- **Bot Integration:** Twitter API v2, Webhooks
- **Smart Contracts:** Solana Programs, Marinade SDK, Jupiter Aggregator
- **Storage:** PostgreSQL, Redis (optional)
- **Hosting:** Render / Vercel / Railway (TBD)

---

## 🔐 Security

- Confirmation via Twitter DM for transactions
- Rate limiting per user
- Private key management (with optional custodial setup)

---

## 👨‍💻 How to Contribute

1. Fork this repo
2. Clone it: `git clone https://github.com/your-username/tweetsol.git`
3. Install dependencies: `cd backend && npm install`
4. Set up your `.env` file (see `example.env`)
5. Run locally: `npm run dev`

---

## 📌 Todo (Phase 1 Highlights)

- [ ] Twitter Developer Account setup
- [ ] Tweet webhook and parser
- [ ] Wallet linking via DM
- [ ] Send/check SOL via tweet
- [ ] Rate limit engine

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

Follow us on Twitter: [@TweetSolBot](https://twitter.com/TweetSolBot)

