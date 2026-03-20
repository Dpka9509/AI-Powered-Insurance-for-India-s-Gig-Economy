# AI-Powered Parametric Insurance for Gig Workers

---

## Problem Statement

Gig workers (Zomato, Swiggy, Amazon, Zepto, etc.) form the backbone of India’s digital economy. However, they face **unpredictable income loss (20–30%)** due to external disruptions such as:

* Heavy rain / floods
* Extreme heat
* Severe pollution
* Curfews / zone restrictions

Currently, there is **no system that protects their lost earnings**.

**Constraints:**

* No health, accident, or vehicle insurance
* Focus only on **income loss protection**
* Must follow a **weekly pricing model**

---

## Solution Overview

**GigSure AI** is an AI-powered parametric insurance platform designed to protect gig workers from income loss caused by external disruptions.

The system:

* Predicts risk using AI
* Detects disruptions automatically
* Triggers claims without user input
* Processes instant payouts

This creates a **zero-touch insurance experience**.

---

## Target Persona

* Food delivery partners (Zomato, Swiggy)
* E-commerce delivery workers (Amazon, Flipkart)
* Grocery delivery partners (Zepto, Blinkit)

---

## Solution Architecture

### Deployment Models

**1. Independent Platform (Web Application)**

* Users register directly
* Purchase weekly insurance plans
* Receive payouts through the platform

**2. Platform Integration (B2B API Model)** *(Recommended)*

The system integrates with platforms like Zomato or Swiggy:

Zomato App → Insurance API → AI Engine → Trigger Detection → Claim Engine → Payment System

* Workers opt-in within the delivery platform
* Insurance operates in the background
* Claims are processed automatically

---

## Workflow

1. User registers or opts-in
2. AI calculates risk score
3. Weekly premium is assigned
4. System monitors external data sources
5. Disruption detected → trigger activated
6. AI verifies event and user activity
7. Claim auto-approved
8. Instant payout processed

---

## Key Features

### AI-Based Risk Assessment

* Uses weather, AQI, and location data
* Predicts potential income loss

---

### Weekly Premium Model

| Risk Level | Weekly Premium | Coverage |
| ---------- | -------------- | -------- |
| Low        | ₹19            | ₹300     |
| Medium     | ₹39            | ₹600     |
| High       | ₹79            | ₹1200    |

Premium is dynamically adjusted based on risk factors.

---

### Parametric Claim Triggers

| Trigger           | Condition            |
| ----------------- | -------------------- |
| Rain              | > 50mm               |
| Heatwave          | > 45°C               |
| Pollution         | AQI > 300            |
| Curfew            | Zone restriction     |
| Platform downtime | No delivery activity |

Claims are triggered automatically without manual filing.

---

### Fraud Detection

* GPS validation
* Anomaly detection
* Duplicate claim prevention

---

### Instant Payout System

* Automated claim approval
* Payment through simulated gateways (UPI / Razorpay)

---

### Dashboard

**Worker View:**

* Active coverage
* Earnings protected
* Risk alerts

**Admin View:**

* Claim analytics
* Fraud monitoring
* Risk forecasting

---

## AI/ML Integration

### Risk Prediction

* Inputs: weather, AQI, location
* Output: risk score and expected income loss

---

### Dynamic Pricing

Premium = Base + Risk Factor + Zone Multiplier

---

### Fraud Detection

* Model: Isolation Forest
* Detects abnormal behavior patterns

---

## Integrations

* Weather API
* AQI API
* Traffic data (mock)
* Payment gateway (simulation)

---

## Tech Stack

* Frontend: React.js
* Backend: Node.js + Express
* Database: MongoDB
* AI/ML: Python (FastAPI / TensorFlow)

---

## Development Plan

**Phase 1:** Ideation and system design
**Phase 2:** Core features (authentication, policy, triggers, claims)
**Phase 3:** Fraud detection, dashboard, payment integration

---

## What Makes This Solution Strong

* Fully automated claim system
* AI-driven pricing and risk analysis
* Scalable B2B integration model
* Designed specifically for gig economy workflows

---

## Future Scope

* Hyperlocal risk heatmaps
* Predictive alerts for workers
* Mobile application
* Expansion to other gig sectors

---

## Conclusion

GigSure AI introduces a proactive, automated insurance model that ensures gig workers are financially protected against uncontrollable disruptions, without requiring manual claims or complex processes.

---

**Team: The Debuggers**
