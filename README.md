# AidSafe

Decentralized donor governance platform for humanitarian aid using XRP Ledger escrow with community-driven fund release voting.

## 📂 GitHub Repositories

**Frontend Application**: [https://github.com/tyhh00/charity-xrp-frontend](https://github.com/tyhh00/charity-xrp-frontend)
*React-based donor dashboard and voting interface hosted on Cloudflare Pages*

**Backend API**: [https://github.com/tyhh00/xrp-charity-backend](https://github.com/tyhh00/xrp-charity-backend)
*Node.js API server for proposal management and XRPL integration hosted on Cloudflare Workers*

**Python Backend**: [https://github.com/tyhh00/python-charity-xrp](https://github.com/tyhh00/python-charity-xrp)
*Python Backend for XRPL integration*

## 💻 Live Website: [https://charity-xrp-frontend.pages.dev/]([https://github.com/tyhh00/python-charity-xrp](https://charity-xrp-frontend.pages.dev/))

## 🎥 Demo Video (30 seconds)

[Demo Video Link](https://www.youtube.com/watch?v=PLACEHOLDER_VIDEO_ID)

*[Replace with your 30-second demo video showing donation process, proposal creation, and voting workflow]*

## 🔗 XRP Ledger Integration

### How It Works

Our donor governance system leverages XRP Ledger's escrow functionality for transparent, community-controlled aid distribution:

1. **Donor Contributions**: Donors send RLUSD/XRP to charity escrow wallets, funds are immediately locked on-chain
2. **Proposal Creation**: NGOs create detailed funding proposals (e.g., "$100k for emergency medical supplies in Region X")
3. **Community Voting**: Donors vote yes/no on proposals using their wallet signatures, weighted by contribution amount
4. **Automated Release**: When proposals reach majority approval threshold, escrow funds are automatically released to designated vendors/recipients
5. **Transparency Tracking**: All donations, votes, and fund releases are publicly recorded on XRP Ledger

### Key XRPL Features Used

- **Multi-Signature Escrow**: Funds locked until community consensus is reached
- **Conditional Escrow**: Automatic fund release based on voting outcomes
- **RLUSD Stablecoin**: Stable value donations for predictable aid budgets
- **Transaction Memos**: Proposal IDs and voting records embedded in transactions
- **Fast Settlement**: 3-4 second voting confirmation and fund release
- **Low Costs**: Sub-penny transaction fees enable micro-donations and frequent voting

### Donation & Voting Flow

```
Donor → Escrow Wallet → Proposal Created → Community Vote → Funds Released
  ↓         ↓              ↓               ↓              ↓
RLUSD    Locked        "$100k for        Yes/No        Vendor
Sent     On-Chain      Medical Aid"      Voting        Payment
```

## 🔍 XRPL Testnet Transactions

**Live transaction examples on XRP Ledger Testnet:**

- **Donor Contribution**: [https://testnet.xrpl.org/transactions/PLACEHOLDER_DONATION_TX_HASH](https://testnet.xrpl.org/transactions/PLACEHOLDER_DONATION_TX_HASH)
- **Proposal Creation**: [https://testnet.xrpl.org/transactions/PLACEHOLDER_PROPOSAL_TX_HASH](https://testnet.xrpl.org/transactions/PLACEHOLDER_PROPOSAL_TX_HASH)
- **Community Vote**: [https://testnet.xrpl.org/transactions/PLACEHOLDER_VOTE_TX_HASH](https://testnet.xrpl.org/transactions/PLACEHOLDER_VOTE_TX_HASH)
- **Fund Release**: [https://testnet.xrpl.org/transactions/PLACEHOLDER_RELEASE_TX_HASH](https://testnet.xrpl.org/transactions/PLACEHOLDER_RELEASE_TX_HASH)
- **Charity Escrow Wallet**: [https://testnet.xrpl.org/accounts/PLACEHOLDER_ESCROW_WALLET_ADDRESS](https://testnet.xrpl.org/accounts/PLACEHOLDER_ESCROW_WALLET_ADDRESS)

*All transactions demonstrate real RLUSD escrow functionality and community governance*

## 🗳️ Governance Model

### Proposal Types
- **Emergency Relief**: Immediate disaster response funding
- **Long-term Projects**: Infrastructure and development initiatives  
- **Operational Costs**: NGO administrative and operational expenses
- **Equipment Purchases**: Medical supplies, food, shelter materials

### Voting Mechanics
- **Weighted Voting**: Vote power proportional to donation amount
- **Quorum Requirements**: Minimum participation threshold for valid votes
- **Approval Threshold**: Majority consensus required for fund release
- **Time Limits**: Proposals expire after set voting period

### Example Proposal
```
Title: "Emergency Medical Supplies - Haiti Earthquake Response"
Amount: $100,000 RLUSD
Purpose: Purchase and distribute medical supplies to earthquake victims
Vendor: Verified medical supply distributor (Wallet: rVendor123...)
Timeline: 72 hours for delivery
Voting Period: 48 hours
Current Status: 67% approval (Threshold: 51%)
```

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/aidsafe.git
cd aidsafe

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Add your XRPL testnet credentials

# Start the application
npm run dev
```

## 📋 Requirements Checklist

✅ **GitHub Repository**: Complete source code available in public repository  
✅ **Demo Video**: 30-second demonstration of core functionality  
✅ **XRPL Integration**: Detailed explanation of escrow-based governance system  
✅ **Block Explorer Links**: Live testnet transactions showing donations, votes, and fund releases  

---

*Replace all PLACEHOLDER text with your actual content before submission*
