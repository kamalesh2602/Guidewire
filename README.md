🚀 SnapInsure
“Instant Income Protection for Gig Workers — Powered by AI & Live Risk Graphs”
🎯 One-Line Pitch

SnapInsure is a zero-claim, AI-powered parametric insurance system that uses a live graph neural network to detect disruptions and automatically compensate gig workers in real time.

🌍 The Problem

Gig workers (Zomato, Swiggy, Zepto) depend on daily earnings.

But their income is affected by:

🌧 Heavy rain / floods

🚧 Road blocks / traffic

📢 Strikes / curfews

❌ If they can’t work → they earn nothing
❌ No reliable insurance exists
❌ Claim systems are slow and fraud-prone

👤 Story: Meet Ravi (Understanding the System)

Ravi is a Swiggy delivery partner in Chennai.

Works 10 AM – 10 PM

Earns more during peak hours (lunch & dinner)

Depends on daily income

🚨 Scenario 1: Heavy Rain (RED ZONE)

Weather API detects extreme rainfall

Ravi’s delivery zone becomes 🔴 RED

What happens?

No safe route exists

Area becomes non-operational

✅ SnapInsure detects this automatically
✅ Ravi doesn’t need to claim anything

💰 Payout:
Payout = Avg Peak Income × Peak Hours Lost
      + Avg Normal Income × Normal Hours Lost

👉 Ravi is paid for the time he could not work

⚠️ Scenario 2: Road Block (YELLOW ZONE)

Google Maps detects road closure

Social media (NLP) confirms a strike

System checks:

Is there another route?

👉 YES → but longer route exists

Zone becomes 🟡 YELLOW

What happens?

Ravi can still deliver

But takes extra time (loss of efficiency)

💰 Smart Compensation (Innovation 🔥)

We calculate time loss due to detour

Time Loss = New Route Time – Optimal Route Time

Then:

Payout = (Avg Hourly Income) × Time Loss

👉 Ravi gets compensated for extra effort & delay

✅ Scenario 3: Normal Conditions (GREEN)

No disruption

Optimal route exists

🟢 No payout needed

🧠 Core Innovation: Live Risk Graph + GNN

We model the city as a Graph Neural Network (GNN):

Structure:

Nodes → City regions

Edges → Roads

🎨 Node States:

🟢 Green → Normal

🟡 Yellow → Partial disruption

🔴 Red → Fully blocked

⚙️ How It Works (Step-by-Step Thinking)
Step 1: Data Input

🌦 Weather API → Rain, flood

🗺 Maps API → Traffic, road closure

🌐 Social scraping + NLP → Strikes, curfews

Step 2: Node Risk Update

If heavy rain → Node turns 🔴

If traffic/partial block → Node turns 🟡

Risk propagates to nearby nodes

Step 3: Route Intelligence

For a delivery:

Find optimal path (shortest path)

If blocked → search alternate path

Decision Logic:

✔ Optimal path exists → 🟢

⚠ Alternate path exists → 🟡

❌ No feasible path → 🔴

Step 4: Time Loss Calculation

Compare optimal vs alternate route

Estimate delay

Step 5: Automatic Payout Trigger
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/248b12fc-25b9-478b-93ec-36f37fefee90" />

## 🏗 System Architecture


Based on:

Time lost

Zone type

Peak vs normal hours

👉 Entire process = Fully automated

💰 Smart Earnings Model (Peak vs Normal)

Each worker’s income is split into:

🍔 Peak Hours (Lunch / Dinner)

☀️ Normal Hours

From platform data:

Avg Peak Income/hour
Avg Normal Income/hour
💡 Payout Logic Summary
🔴 RED (No Work Possible)
Full compensation:
Peak + Normal earnings for lost hours
🟡 YELLOW (Work Possible but Delayed)
Compensation for time loss:
Avg hourly income × delay time
🟢 GREEN
No payout
🛡 Fraud Prevention (Zero-Claim System)

Since there are no claims, fraud is minimized.

Still, we validate:

✔ Multi-layer Checks:

📍 GPS = IP location

🌆 City matches registered location

⏱ Travel time is realistic

🚫 No sudden location jumps

Decision:

All checks pass → ✅ payout

Any mismatch → ❌ blocked

📡 Parametric Triggers

SnapInsure uses objective triggers (no human intervention):

🌧 Rain above threshold

🚧 Road closure / congestion

📢 Strike detection via NLP

🧭 Route infeasibility

👉 Ensures:

Instant payouts

No disputes

High transparency

💳 Weekly Premium Model

Designed for gig economy cash flow

Weekly Premium =
Base Price
+ Zone Risk Factor
+ Weather Probability
- Safe Zone Discount
Why Weekly?

Matches worker earning cycle

More affordable

Dynamic adjustment

🤖 AI/ML Integration
1. Risk Prediction

Predict disruption probability

Improve node classification

2. Dynamic Premium Pricing

Adjust based on:

Zone risk

Weather history

3. Fraud Detection

Anomaly detection

Behavior tracking

4. Income Prediction

Predict expected hourly earnings

📱 Why Web Platform (MVP)?

No app install needed

Easy for judges to test

Faster development

Cross-platform

👉 Future: Mobile app

🧩 Tech Stack

Frontend: React (Vite) + Tailwind
Backend: FastAPI
Database: MongoDB
AI/ML: Scikit-learn
Graph Logic: NetworkX (or custom)
APIs: Weather + Maps (mock)
Payments: Razorpay (test mode)

🏗 Development Plan
Phase 1 (MVP)

Graph-based zone system

Route feasibility engine

Basic payout logic

Phase 2

AI integration

Real APIs

Advanced fraud detection

Phase 3

Multi-city scaling

Personalized insurance

🚀 What Makes SnapInsure Unique?

🔥 Live Graph Neural Network-based insurance
🔥 Zero-claim → fully automated payouts
🔥 Compensates both:

No work (RED)

Delayed work (YELLOW)

🔥 Peak-hour aware payouts
🔥 Built specifically for gig economy

🏁 Final Impact

SnapInsure doesn’t just insure workers — it guarantees their income in uncertain conditions.
