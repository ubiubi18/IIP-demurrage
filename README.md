# IIP-limited supply
introduce limited supply to idena while keeping reward cryptonomics intact 


**IIP-X: Introducing Limited Supply and Demurrage Tax on iDNA Balances**

**Title**: Limited Supply and Demurrage Tax on iDNA Balances for Sustainable Mining Rewards

**Owner**: ubiubi18

**Type**: Standard

**Status**: Draft

**Summary**:
This proposal stops the unlimited coin minting of idna and introduces a limited supply cap. It introduces at the same time a 2% annual demurrage tax on all iDNA balances, irrespective of their state (liquid, staked, locked, or vested). The collected tax will be redistributed entirely to idena identities as session rewards amd as mining rewards. To ensure minimal disruption to the current value distribution, a one-time minting of iDNA will be done during the hard fork into the zero wallet.

**Motivation**:
The primary motivation behind this proposal is to create a sustainable reward mechanism for mining identities while ensuring a limited supply of iDNA. The demurrage tax acts as an incentive for active participation in the network and ensures a continuous flow of rewards to miners.

**Specification**:

1. **Demurrage Tax**: A 2% annual tax will be applied to all iDNA balances. This tax will be calculated and deducted during the flip session of each epoch. The deducted amount will be sent to the reward pool for redistribution to eligible identities.

2. **Total Supply**: The total supply of iDNA will be set at 939,510,000 iDNA. This ensures that the 2% demurrage tax results in 18,790,200 iDNA annually, which will be redistributed to miners.

3. **One-time Minting**: To ensure minimal disruption to the current value distribution, a one-time minting of a significant amount of iDNA will be done during the hard fork. This minted amount will be added to the zero wallet.

4. **Zero Wallet Taxation**: The zero wallet will also be subjected to the 2% demurrage tax, ensuring fairness and uniformity across all wallets.

5. **Fraud Proofs and Challenges**: Existing mechanisms for fraud proofs and challenges remain unchanged.

**Rationale**:
The demurrage tax ensures a continuous reward for miners, promoting active participation and network security. The one-time minting into the zero wallet ensures that the current value distribution remains relatively stable, preventing sudden shocks to the system.

1. *Limited Supply Appeal**: The concept of a limited supply has been a significant attraction in the cryptocurrency space, as evidenced by the success and adoption of Bitcoin. A capped supply often resonates with the crypto community's ethos against inflationary traditional currencies. By setting a fixed supply for iDNA, we align with this popular sentiment, potentially attracting more investors and users to the Idena ecosystem.

2. *Fairer Distribution Mechanism**: Traditional mining mechanisms, as seen in Bitcoin, have increasingly favored highly specialized miners, leading to centralization concerns. These miners benefit disproportionately from the minting mechanism, while the average user sees their holdings' purchasing power diminish. Introducing a demurrage tax ensures a more equitable distribution of rewards, benefiting a broader range of participants.

3. *Incentivizing Active Participation*: Large holders who hoard iDNA without actively participating in securing the network don't contribute to Idena's growth or security. The demurrage tax encourages these holders to stake their coins, ensuring they play an active role in the network's health. This not only boosts network security but also ensures that the tax they pay benefits them indirectly by supporting the ecosystem they've invested in.

4. *Transparency and Distribution*: Currently, there's a lack of clarity regarding iDNA's distribution – it's challenging to ascertain how many individuals or entities control the majority of coins. The demurrage tax, by incentivizing staking and active participation, can provide more transparency in this area, promoting a more decentralized and equitable distribution of iDNA.

6. *Continuous Reward for Miners*: The demurrage tax ensures a continuous reward for miners, promoting active participation and network security. 

7. *Stability in Value Distribution*: The one-time minting into the zero wallet ensures that the current value distribution remains relatively stable, preventing sudden shocks to the system
   

**Backwards Compatibility**:
This proposal requires a hard fork. All nodes and clients will need to upgrade to the new protocol version to stay in consensus.

**Test Cases**:
Test cases will need to be written to ensure the correct deduction of the demurrage tax and its redistribution to miners.



**Implementation**:
Details of the implementation will be provided once the proposal is accepted and before it's finalized.

**References**:
- [IIP-5: Mining rewards based on Quadratic staking](https://docs.idena.io/docs/iip/iip-5)



.

...

