# Confiance

Confiance is a front-end-only interactive prototype for a B2B platform that helps South African brands build customer trust and loyalty.

**Loyalty is built on trust.**

The prototype connects three perspectives in one shared demo: a brand team responds to public concerns, creators verify the customer experience, and customers see what changed. All sample people, brands, incidents, and posts are fictional. No backend or live social feeds are connected.

## Experiences

- **Landing page (`/`)** — introduces Confiance and links to each experience.
- **Brand dashboard (`/brand`)** — overview, Social Outcry Radar, QA Audits, Transparency Log, Status Tiers, and How it works.
- **Creator Hub (`/creator`)** — missions, anonymous audit tools, private reporting, verification, and broadcasts.
- **Customer App (`/customer`)** — Trust Board, Spotlight, Trust Council community, polls, and status rewards.

Use the floating **Demo switcher** to move between experiences. **Reset** restores the initial sample data. Demo changes are held in shared in-memory state and reset when the page is refreshed.

## Try the demo flow

1. In the Brand Dashboard, open **Social Outcry Radar** and select **Simulate viral outcry**.
2. Open the new outcry, create a Transparency Log incident, and launch a verification audit.
3. In the Creator Hub, accept the mission, progress the audit, and send a private report.
4. Return to the Brand Dashboard, review the flagged issue, and log a public fix.
5. In the Creator Hub, verify and endorse the fix.
6. In the Customer App, see the update on the Trust Board and explore the community features.

## Run in Replit

Start the **Confiance web** workflow to run the app in the Replit preview. Its development command is:

```bash
pnpm --filter @workspace/confiance-trust run dev
```

Check TypeScript with:

```bash
pnpm --filter @workspace/confiance-trust run typecheck
```

## Technology

React, TypeScript, Vite, React Router, Tailwind CSS, Recharts, Lucide, and Framer Motion.

## Demo data and privacy

The Trust Agent, social posts, creator aliases, audit cards, customer activity, and notifications are simulated locally in the browser. The prototype does not submit real reports, access a device camera, or send user data to a server. The POPIA copy shown in the Creator Hub describes the intended product concept; this prototype does not issue or store real virtual cards or aliases.
