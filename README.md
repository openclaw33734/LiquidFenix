# LiquidFenix
 Decentralized world improving

The Liquid Fenix DAO is looking for researchers, professionals and entrepreneurs that share the passion for improving the World we all received. That’s why we are designing in a complete decentralized and co-proprietary way the common-good market for impact innovation.

Our goal is to DAOify the entire entrepreneurial ecosystem enabling both the 2.3 billion people that are out the monetary system and the rest of us to have a means of life and joy by contributing to global improvement putting to work our spare time, unused assets and available capital through a common-good stock market.

The value-roadmap is the following:
1. From the Global Challenges available in Liquid, an user makes a proposal for solving the challenge.
2. Community joins efforts either by commenting it, participating on real-time in the co-creation of the project, becoming interested and start following the proposal or by supporting the solution with their vote for making it a decentralized autonomous common-good enterprise.
3. When proposal passes this support threshold members holding the Reviewer title will add their feasibility insights.
4. Liquid's Board members will deliberate if accept, reject or further analyze the proposal based on perspectives coming from both the community and the reviewers.
5. If accepted, two things happen:
	1) The project is DAOified as an Open Exponential Enterprise and
	2) The core entrepreneurs receive a personalized mentorship on how to operate, manage and fund this 21 century type company.
6. The mentor will upgrade the organization to be eligible for contributive crowdinvesting.
7. Each contributor will get paid with either shares of the project or with an accepted stablecoin; as well with it's respective yearly surplus distribution of each company where the user contributed.

There are 6 elements that conform the Liquid Fenix approach:

**1. Open collaboration platform and a single digital marketplace:** Space to reach out mission-oriented projects and best practices around the world by open challenges such as Horizon Europe, in two ways:

I. Already backed-up projects by a budget which are looking for crowd intelligence and community engagement
		
II. New projects that are being co-created by the community to apply for an available challenge, such as Horizon Europe and other SDG oriented missions.

Both of these project types vary in risk and time required both to research and to development, reason why they are presented in three modalities:

(1) Pathfinder: Projects ranging from early technology to pre-commercial that aim to RDI on disruptive technologies for achieving a specific mission-area.
		
(2) Accelerator: Innovative SMEs with pre-commercial to market & scale-up projects looking to develop new products, services and business models that could drive economic growth and shape new markets or disrupt existing ones in Europe and worldwide.
		
(3) Non-commercial use: Best practices and basic research that do not seek or is not (yet) able to be commercialized. Funding this projects won’t return on investment by the project IP, but may provide by using other mechanisms as incentives like tradable crypto-collectibles.

Besides this, a future feature is adding an Online store where users and members can cash-out their earnings to buy products and services that are aligned to the Sustainable Development Goals (SDGs), Mission-areas or shared prosperity pursue such as Fair-trade, B Corps, Co-ops, and any other traditional firm complying with these. This will close the circle of prosperity economy.

**2. Open, Permissionless and Contributive Accounting system:** Any worldwide user is able to get Shares of any listed project through: directly buying them with capital, earning them by task fulfillment or trading them for owned assets.	
The types of contributions are here detailed:

Capital: This type of contribution is only available when Project tokens are on the sale phase, which is only when the project has received approval either by the challenge sponsor (like Horizon Europe) or by Liquid’s General Assembly.
	
Assets:  Each project will specify if required any type of asset for its success. Either way if not requested any user can directly contact the team to offer and negotiate its token-related value. Some examples of asset sharing are patents, equipment and real estate.
	
Tasks: This type of contribution is possible in each of the project’s life cycle and is presented in any of the following forms as bounties:

Open to members:

• Reviews.  The whole community is looking for those projects that offer the best opportunities to impact for good in the most profitable, sustainable and socially conscious ways possible. Thus, a ranking system is applied among all listed projects to provide transparent analysis and feedback of each project in terms of: team’s potential, IP’s competitive advantages and feasibility in legal, financial, technical, commercial and mission-oriented terms, as well as their score towards genuine progress and shared prosperity2.

• Audit. The follow up and audit of financial states, operations and regulatory compliance will be asked to the team to present them as well to the community to review them. This will be required by the platform once the project has arrived to a commercial stage.
	
• Management and Mentorship. Tasks related to the operation and decision making of the LiquidFenix DAO, therefore require a specific level of reputation to apply.

Open to any user:

• Research and Development. Each project will specify areas where community participation is required ranging from simple/complex tasks to job positions as for example: design a logo, curate a database or hire a Communication manager.
    
**3. Fair wealth distribution system:** When users participate in Liquid tasks they get rewarded with a Reputation Score, which acts as signal for surplus distribution from overall’s network net income. This only applies to Liquid shares and not to other projects available in the platform.

**4. Blockchain and AI:** A mix of the best practices and lessons from the worldwide community in these 11 years of blockchain experiences:

I. DAICO: A global co-ownership firm characterized by transparency, accountability and liquidity, based on continuous fundraising campaigns with bonding curves for automated price adjustment.
		
II. AI: Artificial Intelligence will be used to improve the decision making processes that have been identified as friction areas in investment, recruitment and price-setting. Specifically the platform will be enabled with:
	▪ A Robo-Advisor for better decision making on where, when and how to invest;
	▪ An ethical, ‘no wrong-door’ and gamifyed profile assessment for recruiting Reviewers;
	▪ Automated benchmark of task rewards in outside market to assist the Board Members on price-setting.

**5. Open Knowledge and Tokenized Intellectual Property:** In line with the EU principle of Open Science, all research data shall be Findable, Accessible, Interoperable and Re-usable allowing for free personal use but enabling direct reward to all its co-creators from every commercialization practice either done by the original or any subsequent version.

Through the use of blockchain and token-economics, the platform will enable open science while protecting the commercial rights of the involved innovators. 

**6. Governance of the digital commons:** Following the Ostrom’s principles, Liquid is governed using:

I. Multi-stakeholder. Open access to any individual or organization willing to become a member.

II. Commons-based. This means that this platform is identified as a right for all humanity, as well as the DAOs created through here.

III. Co-Op. Type of organization based on democratic member control and equal rights; member economic participation; autonomy and independence; concern for community education, training and information; co-operation among other mission-oriented individuals and networks; and constituted for Prosperity Gains.

IV. Common good stock market: Business activity of the platform and a means for achieving the Sustainable Development Goals.

V. Reputation based for fair economic distribution: Every member of a project gets a yearly surplus distribution based on their contribution to each project (reputation score).

Check the available bounties here: https://rinkeby.aragon.org/#/openliquid

---

## 🔗 Bridging OST (Open Standard Tokens), Aragon, and Decidim

This guide addresses **Issue #3**: How to connect OST, the Aragon governance framework, and the Decidim participatory democracy platform into a cohesive LiquidFenix workflow.

### Architecture Overview

```
┌─────────────┐     ┌────────────────┐     ┌─────────────┐
│   Decidim    │────▶│   Aragon DAO   │────▶│  OST Tokens │
│ (Proposals)  │     │ (Voting + Gov) │     │  (Incentive) │
└─────────────┘     └────────────────┘     └─────────────┘
        │                     │                     │
        ▼                     ▼                     ▼
  Open debate          On-chain voting        Contributor
  & deliberation       (token-weighted)       rewards & stakes
```

### 1. Decidim → Aragon Bridge

Decidim handles the **deliberative democracy** phase — proposals, comments, assemblies. To bridge to Aragon:

- **Use the Decidim-Aragon Connector**: Deploy a middleware service that listens to Decidim webhooks (e.g., `proposal.created`, `proposal.passed`) and translates them into Aragon voting proposals via the Aragon Client API.
- **Vote Weight Mapping**: Map Decidim participant reputation scores to Aragon token-weighted voting power.
- **Recommended Tool**: [Vocdoni](https://vocdoni.io) — a censorship-proof voting protocol that integrates with both Decidim and EVM chains.

### 2. Aragon → OST Bridge

OST (Operational Staking Tokens) provide the incentive layer. To connect:

- **Mint OST as Aragon Voting Tokens**: Deploy a mini-me token for each LiquidFenix project within Aragon. These tokens serve as both governance weight and reward currency.
- **Bonding Curve Integration**: Use Aragon's bonding curve app to enable continuous OST issuance as contributors complete tasks.
- **Staking & Slashing**: OST holders stake tokens to signal support for proposals. Misbehavior (e.g., failed audit) triggers slashing via Aragon agent contracts.

### 3. Full Round-Trip Flow

```
1. User submits proposal on Decidim
2. Community deliberates & improves proposal
3. Proposal reaches threshold → triggers Aragon vote
4. Token holders vote on Aragon
5. Approved → OST rewards distributed to proposal author & contributors
6. OST can be used for future proposal staking or exchanged
7. Progress tracked back on Decidim for transparency
```

### 4. Smart Contract Architecture (Solidity Skeleton)

```solidity
// Simplified bridge interface
interface ILiquidBridge {
    function pushProposal(bytes32 proposalId, string memory metadata) external;
    function syncVotes(bytes32 proposalId, address[] memory voters, uint256[] memory weights) external;
    function distributeRewards(bytes32 proposalId, address[] memory recipients, uint256[] memory amounts) external;
}
```

### 5. Getting Started

1. Fork this repo and install dependencies
2. Deploy the bridge contracts to your preferred EVM network
3. Configure Decidim webhook endpoints pointing to your bridge service
4. Set up Aragon DAO with token voting + bonding curve apps
5. Mint initial OST and assign to early contributors

> **Note**: LiquidFenix uses a modified ERC-20 with built-in reputation tracking. See the `contracts/` directory for the full implementation (coming soon — contributions welcome!).

### References

- [Aragon Developer Portal](https://devs.aragon.org)
- [Decidim API Docs](https://docs.decidim.org/en/developers/)
- [OpenZeppelin ERC-20 + Snapshot](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20)
