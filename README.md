# LaunchPath — AI-Assisted Provider Onboarding

**LaunchPath** is an academic product-management portfolio project by **Harish Chandrasekar**. It explores how an AI-assisted onboarding workflow could help small-business service providers understand requirements, remove blockers, and reach activation faster.

> **Disclosure:** This is an independent academic/portfolio project. It is not affiliated with Wonderschool or any other employer. Customer quotes, metrics, and usage data are simulated. The interactive "AI" experience is implemented with deterministic JavaScript to demonstrate product behavior without a backend or live LLM.

## Live demo

After publishing with GitHub Pages, replace this line with your public URL:

`https://YOUR-GITHUB-USERNAME.github.io/launchpath/`

## What I wanted to demonstrate

- Customer problem framing
- Onboarding funnel and activation metrics
- Voice-of-customer synthesis
- Interactive prototyping
- Next-best-action product design
- Experiment prioritization
- AI/LLM product architecture and safety trade-offs
- Product ownership from problem → prototype → measurement

## Product problem

Small-business providers may stall during onboarding when:
1. requirements are unclear,
2. progress is not visible,
3. document status is ambiguous,
4. next steps are generic,
5. help arrives only after a support ticket is created.

The product hypothesis is that **contextual, prioritized guidance can reduce customer effort and improve activation**.

## North-star metric

**Provider activation rate**

Supporting metrics:
- Median time to activation
- Paid conversion
- Support tickets per provider
- CSAT
- First-customer / early-revenue milestone

## Prototype flow

The interactive prototype asks for:
- provider type,
- location,
- onboarding stage,
- target launch timing,
- current blocker.

It then returns:
- a priority level,
- the recommended next action,
- the reason for that recommendation,
- a short action checklist.

## Product architecture

```text
Product Events
      ↓
Provider Context
      ↓
Rules + Trusted Content Retrieval
      ↓
LLM Explanation / Personalization
      ↓
Task Completion or Human Handoff
```

For compliance-sensitive decisions, deterministic rules and trusted content should remain the source of truth. The LLM is used for explanation, summarization, and personalization rather than inventing policy.

## Research approach

Because this is an academic project, the current quotes and data are simulated. In a real product environment, I would validate the problem using:
- interviews with recently activated and stalled providers,
- support-ticket analysis,
- onboarding funnel events,
- cohort analysis,
- usability testing.

## Prioritized experiments

| Experiment | Hypothesis | Illustrative RICE | Primary metric |
|---|---|---:|---|
| Missing-document detector | Clear document status reduces compliance drop-off | 8.6 | Compliance completion |
| Dynamic onboarding checklist | Personalized steps reduce time-to-activation | 8.1 | Median activation time |
| First-customer playbook | Post-launch guidance improves early success | 6.9 | 30-day first sale |
| Triggered progress nudges | Timely reminders recover stalled users | 6.3 | 7-day reactivation |

## About me

I have 3+ years of experience in engineering and product-operations work, including customer requirements, validation planning, release coordination, KPI reporting, and cross-functional problem solving. I completed a Master's in Industrial Engineering at Northeastern University.

## Tech

- HTML
- CSS
- Vanilla JavaScript
- No framework
- No backend
- No live LLM

## Run locally

Clone or download the repository, then open:

```text
index.html
```

No installation is required.

## Publish with GitHub Pages

1. Create a GitHub repository named `launchpath`.
2. Upload all files from this project.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.
7. GitHub will provide a public URL similar to:
   `https://YOUR-GITHUB-USERNAME.github.io/launchpath/`

## Suggested application description

> I built LaunchPath as an academic product case study around AI-assisted provider onboarding. I mapped the user journey and activation funnel, identified likely friction points, designed a next-best-action workflow, built an interactive prototype, defined product metrics, and prioritized experiments. The current data is simulated, and the AI interaction is represented with deterministic prototype logic so I could focus on the product experience and measurement strategy.
