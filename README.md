# 🌾 Market Mandi

### Strengthening Market Linkages & Price Discovery for Farmers

> A farmer-centric digital platform that helps farmers and FPOs discover better markets, compare prices, find verified buyers, and make informed selling decisions.

---

## 📌 Problem Statement

**SIH PS 26132 — Strengthening Market Linkages and Price Discovery for Farmers**

Small and marginal farmers often have limited visibility into:

- Current prices across nearby mandis
- Buyer demand and requirements
- Quality specifications
- Transportation and storage options
- Buyer reliability and payment history
- Alternative selling opportunities

This can lead to information asymmetry, weak bargaining power, distress selling, and higher transaction costs.

---

## 💡 Our Solution

**Market Mandi** acts as an intelligent market-linkage platform connecting:

**Farmers / FPOs ↔ Mandis ↔ Verified Buyers ↔ Service Providers**

The platform combines market intelligence, buyer matching, logistics support, transactions, and an AI-powered voice assistant into a simple farmer-friendly interface.

### Core Idea

> **Better Information → Better Decisions → Better Prices**

---

## 🚀 Key Features

### 👨‍🌾 Farmer / FPO
- Farmer/FPO profile
- Crop and produce details
- Create produce lots
- View buyer offers
- Track sales
- Transaction history

### 🏪 Market / Mandi Intelligence
- Current mandi prices
- Price trends and charts
- Arrival volumes
- Nearby mandi information
- Market demand
- Best selling opportunity
- Expected net realisation

### 🏭 Buyer
- Verified buyer profiles
- Post requirements/demand
- View available farmer lots
- Digital offers / bidding
- Quality requirements
- Purchase history

### 🔍 Smart Price Discovery
- Compare prices across markets
- Analyse buyer demand
- Compare transportation/storage costs
- Calculate expected net realisation
- Recommend suitable markets/buyers

### 🤖 AI / Voice Assistant
- Multilingual farmer assistance
- Voice-based search
- Mandi and price assistance
- Platform guidance
- Crop, logistics and selling support
- Personalised assistance using farmer data

> AI is used as an **interface and decision-support layer**, while market information is obtained from verified data sources.

### 🚚 Service Providers
- Transporters
- Storage facilities
- Local processors
- Weighbridge services
- Logistics coordination
- Verified service providers

### 🤝 Transaction & Support
- Lot/quality verification
- Digital offers and contracts
- Payment tracking
- Transaction records
- Grievance/dispute support

---

## 🏗️ System Architecture

```text
                         USERS
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
     FARMER/FPO          BUYER          MANDI OFFICER
        │                  │                  │
        └──────────────────┼──────────────────┘
                           ▼
                 ┌───────────────────┐
                 │   MARKET MANDI    │
                 │   WEB APPLICATION  │
                 └─────────┬─────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
     MARKET DATA       MATCHING &       TRANSACTION
     & ANALYTICS       RECOMMENDATION   MANAGEMENT
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                    ┌──────────────┐
                    │   DATABASE   │
                    └──────┬───────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
     External APIs       AI Layer      Notifications
     AGMARKNET/e-NAM     Voice/Chat     SMS/Push/etc.
