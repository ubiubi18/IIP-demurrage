# IIP-limited supply
Introducing Limited Supply & 2% Demurrage Tax for iDNA


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
   
 *Clarify the Zero Wallet's Role**:
   
   The zero wallet, as proposed, acts as a reservoir for the one-time minted iDNA during the hard fork. This mechanism is crucial for several reasons:
   
   - *Buffering the Supply**: By introducing a significant amount of iDNA into the zero wallet, we ensure that the immediate impact of the demurrage tax on the circulating supply is mitigated. This acts as a buffer, allowing the ecosystem to adjust to the new tax mechanism gradually.
   
   - *Transparency and Predictability**: Having a known quantity of iDNA in the zero wallet provides transparency. Stakeholders can predict the effects of the demurrage tax on the total supply over time, given that the zero wallet is also subjected to the 2% tax.
   
   - *Economic Stability**: The one-time minting into the zero wallet ensures that there isn't a sudden scarcity of iDNA, which could lead to unpredictable economic behaviors. By gradually releasing iDNA through the demurrage mechanism, we ensure a more stable economic environment within the Idena ecosystem.

4. **Impact on Network Participation**:

   The introduction of a 2% demurrage tax is expected to have several positive impacts on network participation:

   - *Incentivizing Active Participation**: With the tax applied to all iDNA balances, holders are incentivized to stake their coins. Staking not only allows them to offset the tax through rewards but also actively contributes to the network's security and consensus mechanism.
   
   - *Discouraging Hoarding**: Large holders or "whales" who might hoard iDNA without actively participating in the network's growth or security will now have a financial incentive to either stake their coins or use them within the ecosystem. This can lead to a more dynamic and active Idena economy.
   
   - *Boosting Decentralization**: By encouraging more users to stake and participate, the network becomes more decentralized. A broader distribution of staked coins means that consensus and network decisions are more distributed, reducing central points of control or influence.
   
   - *Enhancing Network Security**: More stakers mean more nodes validating and securing the network. This increased participation can lead to a more robust and secure Idena network, resistant to potential attacks or malicious activities.


5. **Fraud Proofs and Challenges**: Existing mechanisms for fraud proofs and challenges remain unchanged.

6. **Rationale**:
The demurrage tax ensures a continuous reward for miners, promoting active participation and network security. The one-time minting into the zero wallet ensures that the current value distribution remains relatively stable, preventing sudden shocks to the system.

1. *Limited Supply Appeal**: The concept of a limited supply has been a significant attraction in the cryptocurrency space, as evidenced by the success and adoption of Bitcoin. A capped supply often resonates with the crypto community's ethos against inflationary traditional currencies. By setting a fixed supply for iDNA, we align with this popular sentiment, potentially attracting more investors and users to the Idena ecosystem.

2. *Fairer Distribution Mechanism**: Traditional mining mechanisms, as seen in Bitcoin, have increasingly favored highly specialized miners, leading to centralization concerns. These miners benefit disproportionately from the minting mechanism, while the average user sees their holdings' purchasing power diminish. Introducing a demurrage tax ensures a more equitable distribution of rewards, benefiting a broader range of participants.

3. *Incentivizing Active Participation*: Large holders who hoard iDNA without actively participating in securing the network don't contribute to Idena's growth or security. The demurrage tax encourages these holders to stake their coins, ensuring they play an active role in the network's health. This not only boosts network security but also ensures that the tax they pay benefits them indirectly by supporting the ecosystem they've invested in.

4. *Transparency and Distribution*: Currently, there's a lack of clarity regarding iDNA's distribution – it's challenging to ascertain how many individuals or entities control the majority of coins. The demurrage tax, by incentivizing staking and active participation, can provide more transparency in this area, promoting a more decentralized and equitable distribution of iDNA.

6. *Continuous Reward for Miners*: The demurrage tax ensures a continuous reward for miners, promoting active participation and network security. 

7. *Stability in Value Distribution*: The one-time minting into the zero wallet ensures that the current value distribution remains relatively stable, preventing sudden shocks to the system
   
7.  **Potential Risks:**

Adoption Hurdles: Any significant change in a cryptocurrency's economic model can lead to initial resistance or confusion among the community. There's a risk that some stakeholders might not understand or agree with the demurrage concept, potentially leading to debates or disagreements.

Short-Term Price Fluctuations: The announcement and subsequent implementation of such a proposal could lead to short-term price volatility as the market reacts and adjusts to the new economic model.

Technical Implementation Risks: Introducing a new tax mechanism requires changes to the underlying protocol. There's always a risk of bugs or unforeseen technical challenges when implementing such changes, which could impact network stability.



8. **Backwards Compatibility**:
This proposal requires a hard fork. All nodes and clients will need to upgrade to the new protocol version to stay in consensus.

9. **Test Cases**:
Test cases will need to be written to ensure the correct deduction of the demurrage tax and its redistribution to miners.

**Example Impact of 2% Demurrage Tax on iDNA Wallets**

1. *Wallet with 100 iDNA**:
    - *Current APY when staked**: 187.9%
    - *Current APY when unstaked**: 0% (assuming no rewards for unstaked coins)

    *With 2% Demurrage Tax**:
    - *Staked**: The wallet will lose 2 iDNA annually due to the tax. However, with the APY of 187.9%, the wallet would earn 187.9 iDNA in rewards. The net gain would be 185.9 iDNA, making the effective APY 185.9%.
    - *Unstaked**: The wallet will lose 2 iDNA annually due to the tax, with no rewards to offset this loss. The net loss would be 2 iDNA annually.

2. *Wallet with 100,000 iDNA**:
    - *Current APY when staked**: 86%
    - *Current APY when unstaked**: 0% (assuming no rewards for unstaked coins)

    *With 2% Demurrage Tax**:
    - *Staked**: The wallet will lose 2,000 iDNA annually due to the tax. With the APY of 86%, the wallet would earn 86,000 iDNA in rewards. The net gain would be 84,000 iDNA, making the effective APY 84%.
    - *Unstaked**: The wallet will lose 2,000 iDNA annually due to the tax, with no rewards to offset this loss. The net loss would be 2,000 iDNA annually.

---

10. **Conclusion**:
The 2% demurrage tax has a more significant impact on larger wallets in absolute terms, but when considering the rewards from staking, the net effect on APY is relatively small. However, for unstaked coins, the tax represents a pure loss, incentivizing holders to stake their coins and actively participate in the network. This ensures that even large holders contribute to the network's security and health, rather than merely hoarding coins.

11 **Implementation**:
Details of the implementation will be provided once the proposal is accepted and before it's finalized.

12 **References**:
- https://docs.idena.io/docs/iip/



.

...

