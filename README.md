# Growth & Lifecycle Agent 🤖

> An AI-powered workflow that analyzes user behavior data and auto-generates lifecycle marketing strategies — segmentation, campaigns, messaging, and A/B tests in one automated run.

**Built by Khushi Dhanurkar · Powered by Claude API**

🔗 [View Live Demo](https://kdhanurkar.github.io/lifecycle-agent)

---

## What It Does

Lifecycle marketing teams spend hours manually segmenting users, analyzing churn trends, and drafting campaign strategies. This agent replaces that process with a single data input.

Paste a user behavior dataset → the agent automatically outputs:

- **User segments** — grouped by recency, engagement, and monetization (RFM)
- **Campaign strategy** — one targeted campaign per segment with goals and business impact
- **Email + push copy** — personalized messaging ready to use or adapt
- **A/B test plans** — hypotheses, variables, and success metrics
- **Overall measurement framework** — 3–5 KPIs to track success

---

## How It Works

```
User Dataset → AI Analysis → Segmentation → Campaign Strategy → Messaging → A/B Tests
```

1. **Input** — Paste CSV user data (User ID, sign-up date, last active date, sessions, purchases, subscription type, country)
2. **Configure** — Set your company/product type and primary goal (retention, conversion, reactivation, upsell, or activation)
3. **Run** — The 6-step prompt fires automatically via the Claude API
4. **Explore** — Ask follow-up questions in context (e.g. "Which campaigns should be prioritized first?")

---

## The 6-Step Agent Prompt

The agent is powered by a structured prompt that instructs Claude to act as a Senior PM + Lifecycle Marketing Manager. It runs through:

| Step | Output |
|------|--------|
| 1 — User Segmentation | 4–6 segments with names, descriptions, and approximate sizes |
| 2 — Key Insights | 3–5 behavioral insights, churn risks, and upsell opportunities |
| 3 — Campaign Strategy | 1 campaign per segment with goal and business impact |
| 4 — Messaging | 2 email subject lines, email body, and push notification per campaign |
| 5 — Experimentation Plan | 2 A/B tests with hypothesis, variable, and success metrics |
| 6 — Success Metrics | 3–5 KPIs to measure overall strategy performance |

---

## Tech Stack

| Tool | Role |
|------|------|
| Claude API (Sonnet) | Core AI engine — analysis, segmentation, copy generation |
| HTML / CSS / JavaScript | Frontend interface, no frameworks needed |
| GitHub Pages | Free static hosting |
| Google Sheets | Sample user behavior dataset |

---

## Running It Locally

1. Clone the repo
```bash
git clone https://github.com/yourusername/lifecycle-agent.git
```

2. Open `index.html` in any browser — no server or install needed

3. Enter your [Anthropic API key](https://console.anthropic.com) in the key field

4. Load the sample dataset or paste your own CSV data

5. Click **Run Lifecycle Agent**

> Your API key stays in your browser only. It is never stored or transmitted anywhere other than directly to the Anthropic API.

---

## Sample Dataset Format

The agent expects CSV data with these columns:

```
User_ID, Sign_Up_Date, Last_Active_Date, Last_Purchase_Date,
Sessions, Total_Purchases, Subscription_Type, Country
```

A sample dataset is included — just click **"Load sample dataset"** in the app.

---

## Skills Demonstrated

- **Prompt engineering** — designing multi-step, structured AI instructions with consistent output
- **Growth marketing thinking** — applying RFM segmentation, lifecycle strategy, and A/B testing frameworks
- **AI product intuition** — scoping an agent's inputs, outputs, and evaluation criteria
- **Technical execution** — building and deploying a working AI-powered web app from scratch

---

## What's Next

- [ ] Connect to a live data source (Mixpanel, Amplitude, or HubSpot export)
- [ ] Build a UI layer optimized for non-technical marketers
- [ ] Add segment-specific tone and voice customization
- [ ] Automate output formatting into a shareable campaign brief

---

## About

This project was built as part of an exploration into AI-powered marketing workflows — specifically how prompt engineering and lifecycle marketing strategy can be combined into a repeatable, automated tool.

For questions or feedback, connect on [LinkedIn](https://linkedin.com/in/yourprofile) ← add your LinkedIn URL
