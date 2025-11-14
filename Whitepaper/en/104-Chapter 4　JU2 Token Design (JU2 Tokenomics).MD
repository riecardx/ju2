
# Chapter 4　JU2 Token Design (JU2 Tokenomics)



### 4.1 Token Overview



| **Item** | **Description** |
|----|----|
| Token Name | JU2 Token |
| Token Symbol | JU2 |
| Total Supply | 1 billion (1,000,000,000 JU2) |
| Decimals | 18 |
| Token Standard | ERC-20 (compatible with BNB Chain, Arbitrum, Ethereum, Polygon, and other EVM chains) |
| Initial Issuance Method | Smart contract generation + phased release |
| Contract Security | Released after audits by third-party security institutions (such as CertiK / PeckShield) |



JU2 is the core governance and incentive token of the JU2 decentralized ecosystem,  

used to drive platform governance, incentivize contributors, and align long-term community and project value.



### 4.2 Token Allocation



JU2 has a total supply of **1 billion (1,000,000,000 JU2)**.  

The allocation structure is as follows:



| **Allocation Category** | **Percentage** | **Amount (JU2)** | **Description** |
|----|----|----|----|
| Team | 15% | 150,000,000 | Incentives for core development and long-term construction; part permanently locked for co-governance voting |
| Investors | 30% | 300,000,000 | Private and strategic fundraising rounds with long-term vesting |
| DAO Treasury | 20% | 200,000,000 | Community governance, ecosystem fund, strategic partnerships, public goods |
| Community Incentives | 30% | 300,000,000 | Airdrops, mining, user rewards, community activities |
| Market & Liquidity | 5% | 50,000,000 | Market making, listing liquidity, and promotional activities |



### 4.3 Vesting, Unlock & Buyback Policy



JU2 implements a smart-contract-driven multi-layer vesting and release mechanism  

to balance long-term incentives, market liquidity, and community governance.  

All lock-up and unlock data will be publicly available on-chain to prevent human interference.



**(1) Team Vesting Mechanism**



Team allocation totals **15% (150,000,000 JU2)** and follows a dual-track vesting scheme:



- **50% permanently locked**, used only for governance proposals and DAO co-governance voting in later stages;



- **50% locked for 12 months** after the initial airdrop, and linearly released over 36 months (3 years) from month 13;



- Unreleased portions will be automatically reclaimed if team members leave or violate governance rules.



**Purpose:**  

Ensure long-term team participation and co-governance, preventing short-term token dumping.



**(2) Investor Vesting Mechanism**



Investor allocation totals **30% (300,000,000 JU2)**:



- Locked for **6 months** after the initial airdrop;



- From the 7th month, linearly released over **12 months (1 year)**;



- All investor lock-ups are managed by smart contracts and supervised by multi-signature wallets;



- Vesting progress and wallet addresses will be publicly visible on-chain.



**Purpose:**  

Ensure market stability and prevent speculative capital from triggering price shocks.



**(3) DAO Treasury Vesting Mechanism**



- DAO Treasury tokens are managed by a community multi-signature wallet;



- Initially locked for **6 months** to ensure governance stability;



- After unlocking, usage directions are determined by DAO voting, including:



  - Ecosystem project funding



  - Buyback proposal execution



  - DAO reserve and emergency fund



**Purpose:**  

Ensure DAO funds are used for long-term public benefit and ecosystem expansion.



**(4) Community Incentives Release Mechanism**



- After achieving set milestones, the **initial airdrop is released 100% with no lock-up**;



- Used for liquidity mining, user incentives, task rewards, and promotional activities;



- All airdrop distributions are reviewed by the DAO and recorded on-chain.



**Purpose:**  

Enhance community participation and brand reach through transparent airdrop mechanisms.



**(5) Market & Liquidity**



- No lock-up; all tokens can be used immediately;



- Used for market making, exchange listing liquidity, and marketing expenditures;



- The DAO retains authority to adjust usage based on market conditions.



**Purpose:**  

Ensure sufficient liquidity and market exposure in early stages.



**(6) Buyback Policy**



The JU2 platform implements an ongoing buyback and capital recycling mechanism, supervised by the DAO:



- Each month, **50% of platform revenue** (fees, staking yields, etc.) plus treasury funds will be used to buy back JU2;



- Monthly buyback amount must be **no less than 0.75%** of the previous month's circulating supply;



- Buyback results and financial reports are published on the **10th of each month**, publicly visible on-chain.



**Distribution of bought-back tokens:**



- **50% goes to the DAO Treasury** for future governance rewards;



- **50% locked for 12 months**, then released to support DAO liquidity operations.



**Purpose:**  

Establish a sustainable buyback mechanism to strengthen JU2’s long-term value and market confidence.



### 4.4 JU2 Token Utility & Use Cases



JU2 is the core driving force of the ecosystem, powering platform trading, governance, and incentive mechanisms.



**4.4.1 Trading Fee Discount**



- Users holding JU2 in their trading accounts receive **50% fee discounts**;



- The system prioritizes using JU2 to deduct fees, with the remainder settled in stablecoins;



- Discount rules are evaluated and adjusted quarterly by the DAO;



- Fee deduction records are publicly visible on-chain for fairness and transparency.



**Purpose:**  

Increase JU2 circulation and holder activity through real usage scenarios.



**4.4.2 Governance Rights**



JU2 is the governance token for the platform DAO, granting holders the ability to:



- Submit and vote on DAO proposals;



- Decide fund usage, protocol upgrades, and ecosystem incentives;



- Review buyback fund allocation and security fund usage.



**Voting Power Model:**



- Based on the user's **average daily JU2 holdings of the previous natural quarter**;



- Additionally, the average holdings of each of the past **12 quarters (3 years)** contribute **0.05$\times$ per quarter**;



- Final Votes = Current Quarter Daily Average + (Historical Holdings $\times$ 0.05 $\times$ Number of Quarters)



**Example:**  

If Account A holds 10,000 JU2 for 6 consecutive quarters:  

10,000 + 10,000 $\times$ 0.05 $\times$ 6 = **13,000 votes**



**Purpose:**  

Encourage long-term holding and governance participation while reducing short-term speculative influence.



**4.4.3 Liquidity Mining**



- DAO allocates an amount of JU2 **not exceeding the previous month's buyback total** as liquidity incentives;



- Rewards are distributed based on two weight factors:



  - 50% trading volume weight



  - 50% holding time weight



- Incentives are automatically settled via smart contracts and distributed weekly.



**Purpose:**  

Enhance trading depth and real liquidity through scientifically designed incentives.



**4.4.4 DAO Incentives & Ecosystem Growth**



JU2 held in the DAO Treasury is used for ecosystem development and community building, including:



- **Project incubation (Launchpad)**: funding quality projects and forming token partnerships;



- **Development & security audits**: rewarding technical contributors and security teams;



- **Community incentives**: supporting promotion, content creation, and education initiatives.



**Purpose:**  

Form a healthy, self-sustaining ecosystem through DAO-driven funding and governance.



**4.4.5 Revenue Sharing**



- JU2 offers revenue sharing through **Staking** or **Lockdrop** mechanisms;



- **25% of platform trading fees** are distributed quarterly to stakers;



- Rewards may be paid in **USDT / ETH / JU2**;



- Distribution rules are reviewed and updated quarterly by the DAO;



- Only accounts staking continuously for **90+ days** qualify.



**Purpose:**  

Return platform profits to long-term participants, creating a value loop among traders, holders, and governors.

