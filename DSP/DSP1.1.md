# [DSP1.1] Proposal for launching Yield Farming X Layer

[← Home](../README.md)

```shell
Proposal ID: DSP1.1  
End Date: 2024/08/09
Proposer: Dackie Team
```

## Prerequisite

1. [Token Statistic API](https://analytics-api.dackieswap.xyz/api/dackie-statistics)
2. [Token Emission API](https://analytics-api.dackieswap.xyz/api/dackie-emission)
3. [Tokenomics](https://docs.dackieswap.xyz/dackie-and-quack/tokenomics/quack-tokenomics)

## Summary:

We propose launching a **Yield Farming program with QUACK token rewards on X Layer chains. This initiative aims to
attract more liquidity to X Layer**, leveraging Layer Zero technology for seamless bridging of QUACK tokens.

## Objectives and Benefits:

* **Increased Liquidity:** Attract more liquidity providers to X Layer chain, enhancing trading volume and ecosystem
  robustness. Foster the growth of the DackieSwap ecosystem on X Layer chains.
* **Community Growth:** Engage the X Layer community in the DackieSwap ecosystem.

## Yield Farming Structure:

* **Reward Token:** QUACK tokens will be used as rewards for yield farming.
* **Reward Emission:**
    * Following QUACK Tokenomics
  ```shell
  QUACK Esmission Q3 2024: 350,000,000 per month
  ```
  > Current total higher than tokenomics because QueenDACKIE pools launched this month, will be adjusted again end of
  August)

* **Farming Pools:**

  | Chain           | Pools          | Type  | X  | Reward              | New Reward      |
  |-----------------|----------------|-------|----|---------------------|-----------------|
  | Base            | All Pools      | -     | -  | ~~**371,678,806**~~ | **315,000,000** |
  | X Layer         | OKB - DACKIE   | 0.25% | 2x | 0                   | 15,000,000      |
  | X Layer         | DACKIE - QUACK | 1%    | 1x | 0                   | 7,500,000       |
  | X Layer         | OKB - USDT     | 0.25% | 1x | 0                   | 7,500,000       |
  | X Layer         | OKB - USDC     | 0.25% | 1x | 0                   | 7,500,000       |
  | **Total**       |                |       |    |                     | **35,000,000**      |**35,000,000**
  | **Grant Total** |                |       |    | ~~**371,678,806**~~     | **350,000,000** |

* **Bridging Technology:** QUACK tokens will be bridged to/from X Layer using Layer Zero technology.

## Implementation Plan:

* **Development:**
    * Set up farming smart contracts on X Layer: 1 day after proposal passed.
* **Launch:**
    * Announce the yield farming launch date and provide details on how to participate.
* **Governance:**
    * Regularly review and optimize yield farming rewards and pools.
    * Ensure reward emission following yield farming structure.
    * Use community feedback to improve the farming experience.

## Conclusion:

Launching the Yield Farming program with QUACK token rewards on X Layer chains will significantly enhance liquidity and
engage the X Layer community in the DackieSwap ecosystem. Your support and participation are essential for the success
of this initiative.

**For:** Approve the proposal to launch Yield Farming with QUACK token rewards on X Layer chains.  
**Against:** Reject the proposal to launch Yield Farming with QUACK token rewards on X Layer chains.

---
We welcome all your feedback and look forward to your support in making this initiative a success.

**Contact Information:**  
For any questions or further discussion, please reach out to [Dackie Discord](https://discord.gg/dackieofficial),
Category: **#dsp-discussion**. Topic: **DSP1.1**
