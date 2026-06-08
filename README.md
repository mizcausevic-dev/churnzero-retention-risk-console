# churnzero-retention-risk-console

Board-readable Kinetic Gain proof repo for **ChurnZero** platform and company signal coverage.

## Product thesis

Retention risk is hard to act on when product usage, sentiment, renewal timing, and executive coverage do not resolve into one decision.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** CS leaders, account teams, renewals operators, and SaaS value architects
- **Signal domain:** Customer Success
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product turns account health, adoption gaps, renewal blockers, and save-plan ownership into a retention command surface.
- **Value architecture:** Leaders can prioritize save motions, expansion candidates, and accounts where the value narrative no longer holds.

## What this repo proves

- **Normalize:** messy ChurnZero operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: ChurnZero journeys, account health, milestones, playbooks, renewal windows, and executive notes.

This is synthetic proof only. It does not connect to live ChurnZero tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- ChurnZero
- retention risk
- customer success
- renewals
- save plan
