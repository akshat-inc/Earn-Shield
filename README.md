# EarnShield 🚀

### Intelligent Income Protection for Delivery Workers

---

## 📌 Overview

EarnShield is an insurance platform designed for gig economy grocery delivery workers (Zepto, Blinkit, etc.).

It provides financial protection against **income loss caused by external environmental and operational disruptions** such as heavy rainfall, extreme temperatures, poor air quality ,store closure due to  strikes and app downtime

Unlike traditional insurance, EarnShield leverages **automated parametric triggers and AI-driven risk assessment** to deliver **instant, transparent, and hassle-free payouts** — with no manual claims process.

💡 Our goal is to ensure that gig workers never lose their livelihood due to factors beyond their control.
---

❗ **Problem Statement**

Delivery workers rely entirely on daily orders for their income. However, multiple external factors beyond their control significantly impact their earnings:

🌧️ Heavy rain reduces order demand and causes waterlogging
<br>
🌡️ Extreme heat reduces working efficiency and working hours
<br>
🌫️ Poor AQI discourages outdoor activity and affects health
<br>
🏪 Store closures or strikes halt operations completely
<br>
🚦 Traffic congestion increases delivery time and reduces order completion
<br>
📱 Platform or app downtime stops orders entirely

**Impact:**

* Reduced number of deliveries
* Lower daily earnings
* Increased idle time
* No financial safety net

👉 There is currently **no system that protects gig workers from income volatility caused by environmental and operational disruptions.**

## 👤 Target Persona

### Platform:

* Zepto / Blinkit (Quick commerce delivery)

### User:

* Delivery Partner (Gig Worker)

### Daily Workflow:

1. Logs into delivery app
2. Accepts orders
3. Picks up items
4. Delivers to customers
5. Earns per completed delivery

### Key Challenges:

* Weather unpredictability
* No fixed salary
* Income instability
* operational disruptions
---

## 💡 Proposed Solution

EarnShield AI introduces a **parametric micro-insurance model** where:

* Workers pay a **small weekly premium**
* The system continuously monitors environmental data
* When predefined conditions are met, **automatic payouts are triggered**

✅ No claim filing required
✅ No manual verification delays
✅ Transparent and instant support

---

## 💰 Weekly Premium Model

Premiums are dynamically calculated using AI based on risk factors.

### Risk-Based Pricing:

| Risk Level  | Conditions                  | Premium  |
| ----------- | --------------------------- | -------- |
| Low Risk    | Normal weather              | ₹20/week |
| Medium Risk | Moderate variability        | ₹40/week |
| High Risk   | Frequent extreme conditions | ₹60/week |

### AI-Based Logic:

The system considers:

* Historical weather data
* Seasonal trends
* Geographic risk zones
* Worker activity patterns

👉 Premium adjusts weekly based on predicted risk.

---

## ⚡ Parametric Trigger System (Core Feature)

Payouts are automatically triggered when environmental thresholds are exceeded.

### Trigger Conditions:

| Condition         | Threshold   | Payout |
| ----------------- | ----------- | ------ |
| Rainfall          | > 50 mm/day | ₹200   |
| Temperature       | > 45°C      | ₹150   |
| Air Quality Index | > 300       | ₹180   |

### Key Characteristics:

* Fully automated
* No human intervention
* Instant disbursement

⚠️ **Important:**
This system covers **income loss only**, not:

* Health insurance
* Accidents
* Vehicle damage

---

## 🤖 AI/ML Integration

###  Intelligent Premium Calculation

* Uses predictive models to estimate future risk
* Continuously learns from historical patterns
* Adjusts premiums dynamically

---

 ## <u> ⚠️ Fraud Detection Adversarial Defense & Anti-Spoofing Strategy</u><br>
<h3><u>Market Crash Scenario</u></h3><br>
500 fake delivery partners. GPS spoofing. Coordinated fraud draining payouts.<br>

Our system is designed to detect, isolate, and neutralize such attacks while protecting genuine workers.<br>

🎯 Objective<br>
- Detect fraud rings and spoofed identities<br>
- Prevent mass payout exploitation<br>
- Ensure fair payouts to legitimate workers<br>

🧠 Defense Architecture (Multi-Layered)<br>

📍 1. Location Intelligence<br>
- Cross-verify GPS + IP + historical work zones<br>
- Detect impossible movement patterns (instant city jumps)<br>
- Apply geofencing to restrict valid claim zones<br>

📊 2. Activity Validation<br>
- Verify real work signals:<br>
- Deliveries completed<br>
- Login duration<br>
- Order interactions<br>

Reject claims with no or inconsistent activity<br>

🔗 3. Fraud Ring Detection<br>
Identify coordinated patterns:<br>
- Multiple users claiming at the same time<br>
- Same or nearby spoofed locations<br>
- Detect clustered claim spikes in a region<br>
- Flag shared device or synchronized behavior<br>

⚠️ 4. Anomaly Detection<br>
Monitor:<br>
- Sudden surge in claims<br>
- High-frequency claim behavior<br>
- New users joining during disruptions<br>
- Assign risk/anomaly scores to each claim<br>

🧮 5. Confidence Scoring Engine<br>
Each claim is evaluated on:<br>
- Location consistency<br>
- Activity authenticity<br>
- Behavioral history<br>
- Device trust<br>
✅ High score → Auto-approved<br>

⚠️ Medium score → Partial payout / review<br>

❌ Low score → Rejected<br>

🛑 6. Real-Time Risk Controls<br>
- Apply zone-based payout limits<br>
- Delay or review claims in high-risk clusters<br>
- Cap number of payouts per region/time window<br>

⚖️ Fairness Mechanism<br>
- No blanket rejection of entire areas<br>
- Partial payouts for uncertain but possible genuine cases<br>
- Prioritize users with consistent work history<br>

🏆 Strategy Summary<br>
- Move beyond GPS → use multi-signal validation<br>
- Detect fraud using behavior + patterns + clusters<br>
- Balance security with fairness<br>

💡 Key Insight<br>
“In a market crash, trust is built on behavioral consistency — not a single data point.”<br>
 
#### 🚨 Example Fraud Scenario:<br>

* User claims rain payout
* System checks:

  * No rain in that location ❌
    → Claim rejected

---

###  Predictive Risk Engine

* Forecasts high-risk days in advance
* Sends alerts to users
* Helps workers plan work schedules

---

## 🏗️ System Architecture 

1. User subscribes to weekly plan
2. Backend fetches real-time weather data
3. AI model evaluates risk & conditions
4. Trigger engine checks thresholds
5. If triggered → automatic payout
6. Fraud detection layer validates event

---

## 🛠️ Tech Stack

### Frontend:

* React.js / Flutter (Mobile-first design)

### Backend:

* Node.js (Event-driven architecture)

### Database:

* MongoDB

### AI/ML:

* Python (Risk prediction & fraud detection)

### APIs:

* Weather API (real-time data)
* Location/GPS services
note : This is the current outline of tech stack. We might add or adjust technologies as the project progresses.<br>

---

## 📱 Platform Choice

### Mobile Application

### Reason:

* Delivery workers operate via smartphones
* Real-time alerts and tracking required
* Easy accessibility during work

---

## 🔐 Security & Transparency

* Secure data handling
* Transparent trigger conditions
* No hidden claim processes
* Trust-based system

---

## 🚀 Key Features Summary

* ✅ Parametric insurance model
* ✅ AI-driven premium calculation
* ✅ Automated payouts
* ✅ Real-time weather integration
* ✅ Advanced fraud detection
* ✅ Mobile-first accessibility

---

## 🌱 Future Scope

* Integration with delivery platforms (API-level)
*Personalized insurance plans

*Real-time earning dashboards

*Multi-city scaling

*Integration with government schemes

🎯 Conclusion

EarnShield AI empowers delivery workers by providing financial stability and protection against unpredictable environmental risks.

It bridges the gap between gig work and financial security through technology, automation, and intelligent risk management.

👨‍💻 Team

Built for DEVTrails 2026 Phase 1

Focus: Innovation, Impact, and Scalability
