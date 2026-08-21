<p align="center">
  <img src="assets/banner.png" alt="A pink full moon framed by cherry blossom branches at night" width="100%">
</p>

### Nada — blockchain engineer

Building at **[XRPL Commons](https://xrpl-commons.org)** · Paris

I work on the part of on-chain systems where being *approximately* right is expensive: risk models, execution engines, and the interfaces that make both legible to a human under time pressure.

---

#### Selected work

**🌒 [Umbra](https://github.com/nadaamd/umbra)** — an autonomous financial circuit breaker for DeFi
A quantitative risk index (**CBRI**) built from tick-level Uniswap v3 data, and an on-chain evacuation that fires *before* liquidity evaporates. Backtested on the **48,066 real swaps** of the March 2023 USDC depeg ($5.57B of volume): the breaker exits **17h before the bottom**, with USDC still at $1.0000 — **$126.9k saved on a $1M position**, versus 657 bps of slippage for waiting until confirmation.
Python (model + backtest) · TypeScript (QuoterV2/SwapRouter02 execution) · The Graph · 0G attestations · 29 tests
→ [live demo](https://umbra-ten-iota.vercel.app) · [risk terminal](https://umbra-ten-iota.vercel.app/terminal) · [research paper](https://github.com/nadaamd/umbra/tree/main/paper) · *ETH Global Lisbon 2026*

**🟢 [MOLEHUNT](https://github.com/nadaamd/Mole-Hunt-Trading-Game)** — on-chain social deduction, played through a trading terminal
Every round, one wallet is secretly the insider. Everyone trades the same token; you have to read *who is acting on information they shouldn't have* — and accuse them before the timer runs out. Confidential state handled on **COTI v2**.
Next.js 16 · React 19 · Solidity + OpenZeppelin · ethers v6 · a design system built from scratch (emerald-on-black, OKLCH tokens, CSS/SVG animation, no animation library)
→ [live demo](https://mole-hunt.vercel.app)

**🏥 [MediFi](https://github.com/nadaamd/XRPL-Hackathon)** — medical bills paid in installments, hospitals settled instantly
Patients repay interest-free over time, hospitals are paid in full on day one by a liquidity-provider layer, and borrowing eligibility is gated by zero-knowledge proofs. Built on **XRPL**.

**🏎️ [Oracle Racer](https://github.com/nadaamd/Oracle_Racer)** — crypto assets race each other on live prices
A multiplayer on-chain race settled entirely by **RedStone pull oracles**, with only 2 price reads per race.
→ [live demo](https://oracle-racer-ten.vercel.app)

**🚚 [Tournée Futée](https://github.com/nadaamd/Projet-PSI)** — delivery-route optimisation in C#
Little's algorithm (branch-and-bound TSP) over a custom graph and matrix layer, with SQL persistence and a unit-test suite. Where I learned that the algorithm is the easy part.

---

#### Stack

| | |
|---|---|
| **On-chain** | Solidity · ethers.js · viem · Uniswap v3 · XRPL · COTI v2 (confidential compute) · RedStone · The Graph |
| **Quant / data** | Python · pandas · NumPy · backtesting · slippage & liquidity modelling |
| **Product** | TypeScript · Next.js (App Router) · React · Tailwind · design systems |
| **Also** | C# · pytest · node:test · Vercel |

---

#### Currently

Deepening confidential on-chain computation — garbled circuits on COTI — and contributing to [`leash`](https://github.com/leash-ai/leash), a private AI-agent performance competition, where the interesting problem is settling a duel without either side revealing its score.

Talking about it on [X / @nada_amd9](https://x.com/nada_amd9).
