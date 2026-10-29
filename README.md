# Confiance

**Loyalty is built on trust.**

Confiance is a B2B SaaS prototype that helps South African brands keep customers when competitors are only one click away. It builds trust across the whole customer experience through anonymous quality audits, a live transparency log, an AI social media outcry radar and a customer community portal.

> Built for Credify Systems, Customer Loyalty challenge.
> **Live demo:** https://confiance-trust-platform--olwethumabena.replit.app 
---

## The problem

Customers can compare prices and switch providers in seconds. Brands spend on advertising, discounts and loyalty programmes, yet still lose customers because of hidden costs, unreliable delivery, weak support and low trust. A single public complaint, amplified by a creator, can turn one failure into mass churn. Discounts hide the problem without fixing it.

**Root cause:** marketing sells an experience that operations cannot deliver, and the two teams work in silos.

## The idea

Confiance is built on one conceptual model:

```
Customer Loyalty = (Convenience + Price) x Trust
```

Trust is built by **Service Quality**, **Support** and **Transparency**. Price and convenience are easy for competitors to copy, so trust is the multiplier that matters. This is a conceptual model, since in practice trust declines gradually.

## The three experiences

Confiance has three separate interfaces, because each user group needs a different experience.

| Experience | Who it is for | What it does |
|---|---|---|
| **Brand Dashboard** | Operations and CX teams | Trust Score and loyalty KPIs, **Social Outcry Radar**, QA audits, Transparency Log, status tiers |
| **Creator Hub** | Creators and auditors | Audit missions, anonymous audit toolkit, private reporting to operations, verified co-host broadcasts |
| **Customer App** | Shoppers | Trust Board, UGC spotlight, peer Trust Councils, co-creation voting, status rewards |

### Social Outcry Radar (the headline feature)

An AI agent scans social platforms for public outcry about the brand. It groups posts into topics, estimates reach and sentiment, predicts the Trust Score impact if nothing is done, and recommends a four-step response playbook:

1. Acknowledge publicly through the Transparency Log
2. Assign an operations owner
3. Launch a verification audit with creators
4. Notify affected customers

> In this prototype the radar uses **simulated data**. It does not connect to real social media accounts.

## Demo walkthrough

1. **Brand:** press "Simulate viral outcry" in the Radar. The Trust Score shows a predicted drop.
2. **Brand:** open the outcry, create a Transparency Log incident and launch a verification audit.
3. **Creator:** accept the new mission and report the issue privately.
4. **Brand:** the issue appears as "Issue flagged". Log a fix publicly.
5. **Creator:** tap "Verify and endorse" to create the co-host broadcast.
6. **Customer:** the Trust Board shows the fix and the customer earns points.
7. **Brand:** the outcry moves to "Contained" and the Trust Score recovers.

Use the demo switcher in the corner to move between views, and "Reset demo" to start again.

## How I would measure success

A 90-day split-cohort pilot compares conventional email support and discount-led retention (control) against Confiance (test), followed by longer cohort tracking. Metrics avoid discount codes:

- **Organic UGC Velocity:** unpaid customer videos per month
- **Churn Deflection Index:** customers who stay after a verified service failure
- **Community Active Retention Rate:** non-transactional engagement in community channels
- **Repeat Purchase Rate and cohort retention**

## Risks and safeguards

- **Whistleblower risk:** a brand that ignores a flagged issue gives creators public leverage. Issues are reported privately first.
- **Creator independence:** creators clearly disclose their partnership (#Ad) and report findings honestly, positive or negative, in line with advertising rules.
- **Privacy:** virtual cards and burner aliases are encrypted and recycled after each audit, with POPIA in mind.
- **Budget shift:** moving spend from acquisition to retention may slow short-term sign-ups.
- **Limits:** transparency cannot fix a broken supply chain.

## Tech stack

React, Vite, React Router, Tailwind CSS, Recharts, lucide-react, framer-motion

This is a **front-end-only prototype**. It uses seeded mock data and shared in-memory state, with no backend or database.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL shown in the terminal. If you use Replit, press **Run**.

## Important notes

- All brands, creators, customers and social posts in this prototype are **fictional**. Any resemblance to real people or businesses is coincidental.
- All figures are simulated for demonstration. 

## Author

Olwethu Mabena. Honours in IT (Security and Network Engineering). 
