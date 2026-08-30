# ChargeWise AI

An AI-powered assistant that reduces EV range anxiety by helping first-time buyers find nearby charging stations, estimate ownership cost savings, and understand emissions impact.

**SDG Focus:** SDG 13 — Climate Action

## Problem
First-time EV buyers in India hesitate to switch from petrol/diesel vehicles due to uncertainty about charging station availability, driving range, and real cost savings. This "range anxiety" slows EV adoption and keeps transport emissions high.

## Solution
ChargeWise AI is a lightweight web app with two core tools:
1. **Chat Assistant** — answers natural-language questions about charging stations, EV costs, range anxiety, and vehicle recommendations.
2. **Cost & Emissions Calculator** — estimates annual fuel-cost savings and CO2 avoided by switching to an EV, based on daily driving distance.

## Features
- Conversational Q&A interface with quick-question shortcuts
- Rule-based response engine (swappable for OpenAI API / Hugging Face Transformers)
- Nearby charging station directory (demo dataset, ready to connect to a live maps API)
- Real-time cost and CO2 savings calculator

## Tech Stack
- HTML / CSS / JavaScript (no server required — runs entirely in the browser)
- Response logic designed to be swapped for a live LLM API (OpenAI / Hugging Face) in a future version
- Demo charging-station dataset (placeholder for a live maps/EV-infrastructure API)

## How to Run
1. Clone this repository
2. Open `index.html` directly in any browser — no installation or build step needed

```
git clone <this-repo-url>
cd chargewise-ai
open index.html   # or double-click the file
```

## Future Scope
- Native mobile app (Android/iOS)
- Live charging station availability via real-time API
- Multi-stop route optimization for long trips
- Regional language (Hindi and other Indian languages) support

## Author
Amit — Artificial Intelligence Final Project, Lenovo Bharat Care Capstone
