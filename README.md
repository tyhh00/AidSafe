# AidSafe

Decentralized donor governance platform for humanitarian aid using XRP Ledger escrow with community-driven fund release voting.

## 🎥 Demo Video

[![AidSafe Demo](https://img.youtube.com/vi/PLACEHOLDER_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=PLACEHOLDER_VIDEO_ID)

*[Replace with your actual demo video showing donation process, proposal creation, and voting workflow]*

## 📱 Screenshots

### Donor Dashboard
![Donor Dashboard](./screenshots/donor-dashboard.png)
*Main interface for donors to contribute funds and view active proposals*

### Proposal Creation
![Proposal Interface](./screenshots/proposal-creation.png)
*NGO interface for creating funding proposals with detailed allocation requests*

### Voting Interface
![Voting System](./screenshots/voting-interface.png)
*Donor voting interface showing proposal details and voting options*

### Escrow Status Dashboard
![Escrow Dashboard](./screenshots/escrow-dashboard.png)
*Real-time view of locked funds and proposal approval status*

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

## 🎬 Technical Walkthrough Video

[![Technical Deep Dive](https://img.youtube.com/vi/PLACEHOLDER_TECH_VIDEO_ID/0.jpg)](https://loom.com/share/PLACEHOLDER_LOOM_ID)

**This video covers:**
- Complete donation and voting workflow demo
- GitHub repository structure explanation
- Live demonstration of escrow creation and release
- Detailed explanation of multi-signature voting system
- How we satisfied all competition requirements
- Code walkthrough of governance smart contract logic

*Duration: [X] minutes with clear audio commentary*

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

## 🚀 Github Repos

[![Front End]([https://img.youtube.com/vi/PLACEHOLDER_TECH_VIDEO_ID/0.jpg](https://github.com/tyhh00/charity-xrp-frontend))]
