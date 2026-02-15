# Village Price Power — Requirements Specification

## 1. Overview

Village Price Power is an AI-powered collective auction platform that enables small and marginal farmers to digitally pool produce, receive AI-predicted fair price guidance, and sell through a transparent sealed-bid auction system.

The platform improves farmer price realization, prevents trader collusion, and enables data-driven selling decisions.

---

## 2. Objectives

### Primary Objectives

- Enable farmers to aggregate produce digitally at village level
- Provide AI-powered fair price prediction
- Conduct sealed-bid auctions to ensure fair competition
- Provide explainable price recommendations
- Improve farmer price realization by 5–15%

### Secondary Objectives

- Reduce distress selling
- Increase buyer competition
- Provide transparent pricing
- Enable data-driven decision making

---

## 3. Stakeholders

| Stakeholder | Description |
|------------|-------------|
| Farmers | Upload produce and participate in auctions |
| Buyers | Submit sealed bids for produce lots |
| Admin | Manage platform operations |
| AI Engine | Predict fair price bands |
| System | Conduct auction and provide recommendations |

---

## 4. User Roles

### 4.1 Farmer

Capabilities:

- Register/Login
- Create or join produce lot
- View AI fair price prediction
- View auction bids and result
- Accept or reject winning bid

---

### 4.2 Buyer

Capabilities:

- Register/Login
- Browse available produce lots
- Submit sealed bid
- View auction results

---

### 4.3 Admin

Capabilities:

- Monitor platform activity
- Manage users
- Monitor auctions
- View analytics dashboard

---

## 5. Functional Requirements

### FR1: Farmer Registration

System shall allow farmer to:

- Register using phone number
- Provide location
- Provide crop details

---

### FR2: Lot Creation and Aggregation

System shall allow:

- Farmer to create lot
- Farmers to join existing lot
- System to calculate total quantity

Lot contains:

- Commodity
- Total quantity
- Location
- Farmers list

---

### FR3: AI Fair Price Prediction

System shall:

- Fetch historical mandi data
- Use prediction model
- Output:

Example:
