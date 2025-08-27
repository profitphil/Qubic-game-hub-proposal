# Qubic-quest-game-proposal
Proposal to build a candy crush like game for Qubic 

# Rewards & Revenue Distribution — Smart Contract Proposal

## 📚 Table of Contents

1. [Revenue & Reward Pools](#1-revenue--reward-pools)

   * [1.1 Player Reward Pool (PRP)](#11-player-reward-pool-prp)
   * [1.2 Operator Fee (OF)](#12-operator-fee-of)
   * [1.3 Shareholder Dividend Pool (SDP)](#13-shareholder-dividend-pool-sdp)
   * [1.4 Treasury / Reserve](#14-treasury--reserve)
2. [Revenue Sources](#2-revenue-sources)
3. [Distribution Logic — Worked Example](#3-distribution-logic--worked-example)
4. [Shareholder Compensation](#4-shareholder-compensation)
5. [Operator Benefits](#5-operator-benefits)
6. [Player Sustainability](#6-player-sustainability)
7. [Roadmap & Milestones](#7-roadmap--milestones)

---

## 1. Revenue & Reward Pools

### 1.1 Player Reward Pool (PRP)

* **Purpose:** Funds all in-game rewards that drive engagement and retention.
* **Allocation:** *Configurable; example **50%** of net inflows.*
* **Covers:** Session rewards, streak bonuses, missions, seasonal ladders.
* **Outcome:** Keeps players motivated, increases daily active users, and improves loyalty.

### 1.2 Operator Fee (OF)

* **Purpose:** Guaranteed revenue to operate and improve the product.
* **Allocation:** *Fixed **10–15%** of all inflows (before other splits).*
* **Covers:** Infrastructure, development, support, security and ongoing updates.

### 1.3 Shareholder Dividend Pool (SDP)

* **Purpose:** Passive income to Smart-Contract (SC) shareholders that aligns long-term growth.
* **Allocation:** *Configurable; example **30–40%** of net inflows held for distribution.*
* **Payout Cadence:** Weekly or seasonal distributions governed by the SC.

### 1.4 Treasury / Reserve

* **Purpose:** Strategic buffer for events, marketing, liquidity and contingency.
* **Allocation:** *Optional **5–10%*** maintained by the SC treasury.

---

## 2. Revenue Sources

* **Transaction Fees:** Small fee on each rewarded play (or only on **ranked mode** entries).
* **Cosmetics / Gacha:** Skins, frames, boosters and other non-pay-to-win purchases.
* **Streak Recovery:** Micro-fee to preserve streaks after a miss.
* **Ranked Entry Fees:** Players stake tokens to compete for seasonal prize pools.
* **Advertising (optional):** Programmatic ads routed through the SC for transparent payout rules.

---

## 3. Distribution Logic — Worked Example

**Example:** 100 tokens net inflow

* **50 tokens → PRP (Player Reward Pool)**
* **15 tokens → Operator Fee**
* **30 tokens → Shareholder Dividend Pool**
* **5 tokens  → Treasury / Reserve**

> All percentages are parameters in the SC and may be adjusted by governance to meet growth and sustainability targets.

---

## 4. Shareholder Compensation

* **Pro-Rata Dividends:** Each shareholder receives a percentage of SDP proportional to their SC share.
* **Scheduled Payouts:** Weekly or monthly cycles, executed trustlessly by the SC.
* **Growth Incentives:** Optional reinvestment toggle to **auto-compound** dividends back into PRP or Treasury.
* **Transparency:** On-chain accounting with public dashboards for pool balances and historical distributions.

---

## 5. Operator Benefits

* **Guaranteed Income:** A fixed **Operator Fee** on all inflows.
* **Secondary Upside:** If the operator also holds SC shares, they participate in **dividends** (fee + dividend “double-dip”).
* **Aligned Incentives:** More active players → larger pools → stronger dividends → healthier ecosystem.

---

## 6. Player Sustainability

* **Fair Emissions:** Rewards scale with difficulty/engagement and are **capped to prevent abuse**.
* **Seasonal Ladders:** Funded by entry fees + a defined slice of PRP → sustainable competitive loop.
* **Cosmetic Sinks:** Deflationary pressure that absorbs inflation and keeps tokens circulating.
* **Integrity:** Security, anti-botting, rate limits and proof-of-play hooks at the API/SC layers.

**✅ Net Result**

* **Players:** fun + consistent rewards.
* **Operator:** predictable revenue to run and grow the game.
* **Shareholders:** sustainable, recurring dividends that grow with adoption.

---

## 7. Roadmap & Milestones

### Milestone 1 — Backend & API Layer + Smart-Contract Foundation

* **Scope**

  * Design & implement **Reward System SC** (Qubic C++).
  * Implement pool splits (**PRP / OF / SDP / Treasury**) with parameterization & admin controls.
  * Core hooks: register player, submit result, compute rewards, distribute payouts.
  * Backend services (NestJS / FastAPI) interfacing game → SC.
  * Database for player state, sessions, leaderboards.
  * API endpoints: rewards, streaks, missions, ranked play.
  * Security & anti-abuse: rate-limits, proof-of-play basics, audit logging.
* **Deliverables**

  * Deployed SC in test environment.
  * Working backend integrated with SC.
  * API documentation (OpenAPI) + Postman collection.
* **Timeline:** **1–2 weeks**

---

### Milestone 2 — Web Application (MVP Frontend)

* **Scope**

  * **React** web app: solo rewarded play + ranked play.
  * SC reward claiming integrated in-app.
  * Player dashboard: rewards, streaks, missions, leaderboards.
  * Operator/Shareholder dashboard: pools, payouts, reports.
* **Deliverables**

  * Playable **web MVP** with end-to-end SC integration.
* **Timeline:** **3–4 weeks**

---

### Milestone 3 — Mobile Applications

* **Scope**

  * **React Native** Android/iOS from a shared codebase.
  * Push notifications (daily streaks, season updates).
  * Mobile-first UI/UX optimizations.
  * Store submission: Google Play & Apple TestFlight.
* **Deliverables**

  * **Mobile builds** ready for testing/release.
* **Timeline:** **5–7 weeks**

---

### Milestone 4 — Desktop Build & Final Integration

* **Scope**

  * Electron packaging for **Windows/Mac**.
  * Final integration tests across Web, Mobile, Desktop.
  * Cosmetic store & monetization hooks (optional for MVP).
  * Documentation + admin handover.
* **Deliverables**

  * **Unified cross-platform release** with full SC reward loop.
* **Timeline:** **≈8 weeks**

---

*This specification mirrors the structure and tone of the existing proposal documentation and is formatted for inclusion alongside technical and business sections in your README.*
