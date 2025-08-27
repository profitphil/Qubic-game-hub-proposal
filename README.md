# Qubic-quest-game-proposal

Proposal to build a candy-crush–style game for Qubic

## Introduction

**Qubic Quest** is a Candy Crush–style puzzle game built on the Qubic blockchain with an integrated smart contract that automatically **distributes revenues** to players (rewards), shareholders (dividends), and charity—and includes **token-burning** mechanisms to reduce Qubic supply. The **8-week** development project will deliver **web (desktop)** and **mobile (iOS/Android)** versions, creating a sustainable gaming ecosystem that showcases Qubic’s high-performance blockchain capabilities to mainstream audiences.

* **Developer:** Venus *(QWallet, Qexplorer, CFB meme generator)*
* **Funding Request:** **\$8,500 USD** *(3.54B Qu @ 0.0000024)*
* **Destination Wallet:** `SZWOFOPFTSWIGBTEKGFREWGSNSSAPMKBYJZBISLKEFEUVEZQTBHTATXAFSHC`

# Rewards & Revenue Distribution — Smart Contract Proposal

## 📚 Table of Contents

0. [Introduction](#introduction)
1. [Key Features](#1-key-features)
2. [Solutions Offered by Qubic Quest](#2-solutions-offered-by-qubic-quest)
3. [How Qubic Quest Benefits Qubic](#3-how-qubic-quest-benefits-qubic)
4. [Revenue & Reward Pools](#4-revenue--reward-pools)

   * [4.1 Player Reward Pool (PRP)](#41-player-reward-pool-prp)
   * [4.2 Operator Fee (OF)](#42-operator-fee-of)
   * [4.3 Treasury / Reserve](#43-treasury--reserve)
   * [4.4 Shareholder Dividend Pool (SDP)](#44-shareholder-dividend-pool-sdp)
   * [4.5 Charity](#45-charity)
   * [4.6 Qubic Burn](#46-qubic-burn)
5. [Revenue Sources](#5-revenue-sources)
6. [Distribution Logic — Worked Example](#6-distribution-logic--worked-example)
7. [Shareholder Compensation](#7-shareholder-compensation)
8. [Player Sustainability](#8-player-sustainability)
9. [Roadmap & Milestones](#9-roadmap--milestones)

   * [9.1 Milestone 1 — Backend & API + SC Foundation](#91-milestone-1--backend--api--sc-foundation)
   * [9.2 Milestone 2 — Web Application (MVP)](#92-milestone-2--web-application-mvp)
   * [9.3 Milestone 3 — Mobile Applications](#93-milestone-3--mobile-applications)
   * [9.4 Milestone 4 — Desktop Build & Final Integration](#94-milestone-4--desktop-build--final-integration)
10. [Payment Terms](#10-payment-terms)
11. [Team](#11-team-composition)

---

## 1. Key Features

* **On-Chain Rewards:** Smart contract (SC) automatically splits revenue into Player Rewards, Operator Fee, Shareholder Dividends, Treasury/Reserve, Charity, and Burn (deflation).
* **Fair & Transparent:** All earnings, reward rules, and distributions are executed on-chain with public balances and histories.
* **Sustainable Loops:** Ranked entry fees + PRP funding support seasonal ladders, missions, and streaks without runaway emissions.
* **Deflationary Utility:** A fixed share of revenues is burned each cycle, reducing circulating Qubic supply.
* **Shareholder Dividends:** SDP pays pro-rata distributions to SC shareholders on a weekly cadence.
* **Charity Support:** Dedicated percentage of inflows is routed to approved charities via SC logic.
* **Multi-Platform Launch:** Web (desktop) and mobile (iOS/Android) builds to reach mainstream users.
* **Integrity & Safety:** Anti-bot measures, rate limiting, and proof-of-play checks to keep rewards fair.

---

## 2. Solutions Offered by Qubic Quest

* **Utility for Qubic Tokens** Converts gameplay, cosmetics, and ranked entries into real token sinks and on-chain activity.
* **Inflation Concerns** Mitigates supply growth through a built-in burn allocation on every epoch.
* **Player Retention & Engagement** Missions, streaks, and seasonal ladders keep users returning while aligning rewards to effort.
* **Trust & Transparency** Revenue splits, pool balances, and dividend payouts are enforced by the SC on-chain.
* **Ecosystem Funding & Stability** Operator Fee and Treasury/Reserve enable ongoing development, infra, security, and events.
* **Social Impact** A fixed charity allocation ties gameplay to tangible, real-world contributions.

---

## 3. How Qubic Quest Benefits Qubic

* **Expands the User Base:** Web + mobile funnels attract mainstream players and onboard them into the Qubic ecosystem.
* **Showcases Performance:** Demonstrates Qubic’s low-latency, high-throughput smart-contract execution in a popular game format.
* **Builds Token Utility:** Multiple spending surfaces (ranked entries, cosmetics, streak recovery) create persistent demand.
* **Reduces Supply:** Automated burn mechanics provide consistent deflationary pressure.
* **Shareholder Revenues:** Offers rewards and passive income for shareholders.
* **Strengthens Credibility:** Transparent SC accounting and charitable distributions improve ecosystem trust.

---
## Example UI

![Qubic Quest](qubic-quest.gif)

---
## 4. Revenue & Reward Pools

### 4.1 Player Reward Pool (PRP)

* **Allocation:** **50%** of net inflows.
* **Purpose:** Funds all in-game rewards that drive engagement and retention.
* **Covers:** Session rewards, streak bonuses, missions, seasonal ladders.
* **Outcome:** Keeps players motivated, increases DAU, and builds loyalty.

### 4.2 Operator Fee (OF)

* **Allocation:** **15%** of all inflows.
* **Purpose:** Guaranteed revenue to operate and improve the product.
* **Covers:** Infrastructure, development, support, security, ongoing updates.

### 4.3 Treasury / Reserve

* **Allocation:** **15%**.
* **Purpose:** Strategic buffer for events, marketing, liquidity, and contingency.

### 4.4 Shareholder Dividend Pool (SDP)

* **Allocation:** **10%**.
* **Purpose:** Passive income to SC shareholders; aligns long-term growth.
* **Payout Cadence:** Weekly distributions governed by the SC.

### 4.5 Charity

* **Allocation:** **5%**.
* **Purpose:** Direct donations to real-world causes; reinforces community ethos.

### 4.6 Qubic Burn

* **Allocation:** **5%**.
* **Purpose:** Deflationary pressure by burning Qubic to combat inflation.

---

## 5. Revenue Sources

* **Transaction Fees:** Small fee on each rewarded play (or only on **ranked mode** entries).
* **Cosmetics / Gacha:** Skins, frames, boosters (non-pay-to-win).
* **Streak Recovery:** Micro-fee to preserve streaks after a miss.
* **Ranked Entry Fees:** Players stake tokens to compete for seasonal prize pools.
* **Advertising (optional):** Programmatic ads with payouts routed by SC rules.

---

## 6. Distribution Logic — Worked Example

**Example:** 100 tokens net inflow

* **50 tokens → PRP (Player Reward Pool)**
* **15 tokens → Operator Fee**
* **15 tokens → Treasury / Reserve**
* **10 tokens → Shareholder Dividend Pool**
* **5 tokens  → Charity**
* **5 tokens  → Qubic Burn**

---

## 7. Shareholder Compensation

* **Pro-Rata Dividends:** Each shareholder receives SDP proportional to their SC share.
* **Scheduled Payouts:** Weekly, executed trustlessly by the SC.
* **Growth Incentives:** Optional auto-compound toggle to reinvest dividends into PRP or Treasury.
* **Transparency:** On-chain accounting; public dashboards for pool balances and distributions.

---

## 8. Player Sustainability

* **Fair Emissions:** Rewards scale with difficulty/engagement and are **capped to prevent abuse**.
* **Seasonal Ladders:** Funded by entry fees + a defined slice of PRP → sustainable competitive loop.
* **Cosmetic Sinks:** Absorb inflation and keep tokens circulating.
* **Integrity:** Anti-botting, rate limits, and proof-of-play hooks at API/SC layers.

**✅ Net Result**

* **Players:** Fun + consistent rewards.
* **Operator:** Predictable revenue to run and grow the game.
* **Shareholders:** Sustainable, recurring dividends that grow with adoption.

---

## 9. Roadmap & Milestones

### 9.1 Milestone 1 — Backend & API + SC Foundation

* **Scope**

  * Design & implement **Reward System SC** (Qubic C++).
  * Implement pool splits (**PRP / OF / SDP / Treasury**) with parameterization & admin controls.
  * Core hooks: register player, submit result, compute rewards, distribute payouts.
  * Backend services (NestJS / FastAPI) bridging game ↔ SC.
  * Database for player state, sessions, leaderboards.
  * API endpoints: rewards, streaks, missions, ranked play.
  * Security & anti-abuse: rate-limits, proof-of-play basics, audit logging.
* **Deliverables**

  * Deployed SC in test environment.
  * Working backend integrated with SC.
  * API documentation (OpenAPI) + Postman collection.
* **Timeline:** **1–2 weeks**

---

### 9.2 Milestone 2 — Web Application (MVP)

* **Scope**

  * **React** web app: solo rewarded play + ranked play.
  * In-app SC reward claiming.
  * Player dashboard: rewards, streaks, missions, leaderboards.
  * Operator/Shareholder dashboard: pools, payouts, reports.
* **Deliverables**

  * Playable **web MVP** with end-to-end SC integration.
* **Timeline:** **3–4 weeks**

---

### 9.3 Milestone 3 — Mobile Applications

* **Scope**

  * **React Native** for Android/iOS from a shared codebase.
  * Push notifications (daily streaks, season updates).
  * Mobile-first UI/UX optimizations.
  * Store submission: Google Play & Apple TestFlight.
* **Deliverables**

  * **Mobile builds** ready for testing/release.
* **Timeline:** **5–7 weeks**

---

### 9.4 Milestone 4 — Desktop Build & Final Integration

* **Scope**

  * Electron packaging for **Windows/Mac**.
  * Final integration tests across Web, Mobile, Desktop.
  * Cosmetic store & monetization hooks (optional for MVP).
  * Documentation + admin handover.
* **Deliverables**

  * **Unified cross-platform release** with full SC reward loop.
* **Timeline:** **≈8 weeks**

---

## 10. Payment Terms

* **Total Request:** **\$8,500 USD**

**Breakdown**

* **SC Development:** 160 hrs × \$25/hr = **\$4,000**
* **Frontend + UI Development:** 160 hrs × \$25/hr = **\$4,000**
* **Webserver setup/development & App Store fees:** **\$500**

**Disbursement Schedule**

* **M1 — 20%**
* **M2 — 30%**
* **M3 — 20%**
* **M4 — 30%**

## 11. Team Composition

- **Profitphil:** Team Lead
- **Venus:** Lead developer
