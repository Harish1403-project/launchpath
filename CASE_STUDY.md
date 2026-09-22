# LaunchPath Product Case Study

## 1. Context

LaunchPath is an academic portfolio project exploring an AI-assisted onboarding experience for small-business service providers.

The project is intentionally framed as a **product problem**, not an "AI demo." The core question is:

> How might we reduce provider uncertainty during onboarding and help more users reach activation with less manual support?

## 2. User problem

A time-constrained owner/operator may need to understand:
- what information is required,
- which documents have been accepted,
- what remains incomplete,
- which task matters most next,
- what success looks like after launch.

A long checklist can create activity without clarity. The proposed product therefore emphasizes a single prioritized next action.

## 3. Jobs to be done

When onboarding, a provider wants to:
1. understand what is required,
2. know what to do next,
3. see visible progress,
4. get an explanation when something is unclear,
5. reach a first meaningful business outcome quickly.

## 4. Hypothesis

If the product uses onboarding context to identify the current blocker and recommends a clear next action, then providers should complete onboarding faster and need less manual support.

## 5. Research plan

Because this is an academic project, the included quotes and metrics are simulated.

A real validation plan would use:
- 5–8 qualitative interviews across activated and stalled providers,
- support-ticket theme coding,
- step-level funnel analysis,
- time-between-events analysis,
- usability testing,
- cohort comparison before and after rollout.

## 6. Metrics

### North star
Provider activation rate.

### Supporting metrics
- Median time to activation
- Compliance completion
- Paid conversion
- Support tickets per provider
- CSAT
- First-customer milestone

### Guardrails
- Incorrect compliance guidance
- Escalation rate
- Repeat-contact rate
- User-reported confusion
- Content freshness / policy mismatch

## 7. Proposed workflow

1. Collect context.
2. Detect the highest-priority blocker.
3. Retrieve the relevant trusted content.
4. Apply deterministic rules where correctness is critical.
5. Use an LLM for explanation and personalization.
6. Give one prioritized action.
7. Measure completion.
8. Escalate uncertain or high-risk cases.

## 8. MVP

The portfolio prototype includes:
- an activation dashboard,
- funnel drop-off analysis,
- simulated customer feedback,
- an interactive next-best-action flow,
- experiment prioritization,
- a conceptual AI architecture.

A real MVP would begin smaller:
- one high-friction onboarding step,
- one provider segment,
- one measurable activation event,
- a human fallback.

## 9. Experiment plan

### Experiment 1: Missing-document detector
Hypothesis: clear status labels reduce compliance-stage abandonment.

Primary metric: compliance completion.

### Experiment 2: Dynamic onboarding checklist
Hypothesis: personalized next steps reduce median time to activation.

Primary metric: median activation time.

### Experiment 3: Progress nudges
Hypothesis: event-triggered reminders recover stalled providers.

Primary metric: seven-day reactivation.

## 10. AI product trade-offs

LLMs are useful for:
- plain-language explanations,
- summarization,
- contextual guidance,
- personalization.

LLMs should not independently decide:
- compliance eligibility,
- legal or regulatory interpretation,
- whether a required document can be waived.

Those actions should rely on deterministic product rules, trusted content, and human escalation.

## 11. What I would do next

If this were moving from portfolio prototype to real product work, I would:
1. interview recently activated and stalled users,
2. validate the largest funnel drop-off,
3. define the exact activation event,
4. instrument the funnel,
5. test a single onboarding intervention,
6. measure behavioral improvement,
7. then add AI only where it improves clarity or speed.
