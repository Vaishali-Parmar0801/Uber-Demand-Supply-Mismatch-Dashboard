# 🚗 Uber Supply-Demand Mismatch Analysis

> Analysing 840 hourly records from Nov - Dec 2016 to identify critical supply gaps, coverage shortfalls, and actionable driver incentive strategies to increase completed rides.

---

## Dashboard Overview
[Uber-Supply-Demand-Mismatch-Dashboard]<img width="965" height="693" alt="Uber_Demand_Supply_Mismatch_Dashboard" src="https://github.com/user-attachments/assets/dc5153ed-71c9-491b-bcbd-3bb30b3286ba" />


## 📊 Project Overview

| Attribute | Detail |
|-----------|--------|
| **Tool** | Microsoft Excel |
| **Data Points** | 840 hourly records |
| **Time Period** | November - December 2016 |
| **Analysis Type** | Hourly demand vs supply profiling |
| **Output** | Incentive framework + driver scheduling recommendations |

---

## 🔢 Key Metrics

| Metric | Value |
|--------|-------|
| Total Finished Rides | 11,738 |
| Total Demand | 40,509 |
| Avg Coverage Ratio | 75.7% |
| Avg Daily Rides | 35 |
| Avg Daily Demand | 1,158 |
| Minimum Coverage (4 AM) | 53% |
| 2-Hour Supply Lag | Every day (demand 6-7 PM, supply peaks 8-9 PM) |

---

## 📁 Files in This Repository

```
📁 Uber-Supply-Demand-Analysis/
│
├── 📑 Uber_Casestudy_Presentation.pdf      # Full analysis presentation
└── 📄 README.md                            # This file
```

---

## 📐 Metric Tree

```
🎯 GOAL: Increase Completed Rides
│
└── ⭐ PRIMARY METRIC: Coverage Ratio % (Avg 75.6%)
        │
        ├── 📉 DEMAND SIDE
        │       ├── Avg 0.57 rides per hour
        │       ├── Evening Peak: 6–8 PM
        │       ├── Morning Rush: 7–9 AM
        │       └── Friday = Peak Demand Day
        │
        └── 📦 SUPPLY SIDE
                ├── Avg 23.2 online hrs per driver
                ├── Supply peaks 2 hours AFTER demand (8 PM)
                ├── 3–10 AM: Only 53% coverage
                └── 341 extra driver-hours needed per day
```

---

## 🔍 EDA & Key Findings

**F1 - Evening Demand Peak**

Evening 5-8 PM shows avg 2,839 demand vs the 1,688 daily average. This is the highest-pressure window for the platform.

**F2 - Morning Critical Shortage**

3 AM - 9 AM coverage dips as low as 53% at 4 AM. Early morning has the highest percentage of unmet demand (81.5% at 6 AM).

**F3 - Friday = Highest Weekday**

Friday avg demand is 62.8 rides - 69% higher than Sunday (37.1). Weekend demand is surprisingly lower.

**F4 - 2-Hour Supply Lag**

Drivers peak at 8-9 PM while demand peaks at 6-7 PM - a 2 hour lag that results in peak demand being under-served every single day.

**F5 - Holiday Surge Effect**

Dec 15-17 shows high demand (2,731 rides on Dec 16) with coverage dropping to 55%.

---

## 📊 Coverage Ratio by Hour

| Coverage Zone | Hours | Coverage % |
|--------------|-------|-----------|
| 🔴 Critical | 3-8 AM | 53-60% |
| 🟠 Warning | 8-9 AM | 60-70% |
| 🟢 Healthy | Rest of day | >70% |

**Critical Window:** Hours 3–10 AM need 370 extra driver-hours per day.

---

## 📅 Day-of-Week Demand

| Day | Avg Demand |
|-----|-----------|
| Friday | 63 🔴 |
| Wednesday | 54 |
| Thursday | 49 |
| Tuesday | 48 |
| Monday | 44 |
| Saturday | 43 |
| Sunday | 37 |

---

## 💰 Incentive Framework

| Assumption | Value |
|-----------|-------|
| Avg Ride Value | ₹10 |
| Driver Earnings | 80% |
| Uber Revenue Share | 20% |
| Avg Ride Duration | 20 min |
| Rides per Online Hour | 0.57 |
| Guaranteed Hour Rate | ₹9/hr |

**Total Daily Incentive Cost (Critical Hours 3-10 AM): ₹3,337/day**

**Additional Supply Required:**
- Hours 7-10 AM = 243 driver-hours
- Hours 6-8 PM = 98 driver-hours
- **Total = 341 driver-hours per day**

---

## 💡 Top 6 Recommendations

| # | Recommendation | Impact |
|---|---------------|--------|
| R1 | Morning Shift Incentive (₹9/hr, 3–10 AM) | Fills 81.5% gap at 6 AM; saves ₹8K+/day in lost rides |
| R2 | Track Absolute Gap (unmet rides) alongside Coverage % | More accurate than % alone |
| R3 | Push notifications to drivers at 4:30 PM | Addresses 2-hour supply lag before 6 PM surge |
| R4 | Friday Peak Bonus for drivers | 69% higher demand; target 10–15% more active drivers |
| R5 | Holiday Demand Pre-Alerts | Activate bonuses 48 hrs before known holidays |
| R6 | Dynamic Off-Peak Pricing (10 AM-4 PM) | Shifts demand to smooth the curve |

---

## 📈 Summary Impact

| Problem | Scale |
|---------|-------|
| Unmet Demand (avg daily) | 70% |
| Minimum Coverage (4 AM) | 53% |
| Supply Lag After Demand Peak | 2 hours |
| Daily Incentive Cost to Fix | ₹3,337 |
| Only X of 1,158 avg daily demand gets a ride | 335 rides |

---

## 🛠️ Tools Used

- **Microsoft Excel** - Hourly data analysis, demand vs supply profiling, incentive modelling, charts

---

## 👩‍💻 Author

**Vaishali Parmar**  
Data Analyst | Next Leap Program

---

*This project is part of the Next Leap Data Analytics Program*
