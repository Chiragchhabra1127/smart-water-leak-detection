# 💧 Smart Water Leak Detection & Alert System (SustainAI)

An AI-enabled solution to stop silent water wastage at **MGSU, Bikaner**.

**Domain:** Water | **Program:** 1M1B Green Skills & Applied AI for Climate Action Internship
**Author:** Chirag Chhabra, MGSU Bikaner

## Problem
Drinking-water coolers on campus leak continuously, unnoticed — wasting a scarce resource in Bikaner's water-stressed desert climate.

## Solution
A low-cost flow-monitoring system with AI anomaly detection:
1. **Flow Sensor** – measures litres/minute at each cooler's inlet
2. **ESP32 Microcontroller** – sends readings over campus Wi-Fi
3. **AI Anomaly Detection** – learns normal flow pattern, flags real leaks
4. **Alert System** – instant SMS to maintenance with location & litres lost

## Impact
- ≈1,200 L/month water recovered
- Leak-to-repair time cut from 3–5 days to <24 hours

## Tech Stack
Flow sensor + ESP32 · Z-score/Isolation Forest anomaly detection · Firebase/Google Sheets · Power BI · Twilio SMS API

## Roadmap
Pilot (5 coolers) → Campus-wide expansion → Full rollout across MGSU affiliate colleges

---
*Built as part of the 1M1B Green Skills & Applied AI for Climate Action Internship.*
