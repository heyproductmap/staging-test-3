# Metrics Tracking

**Competency:** Delivery

## Summary

Define, track, and report metrics that show whether the startup is progressing towards product-market fit. Good metrics tracking connects daily work to validation milestones and surfaces problems before they become crises.

## Key Concepts

### North Star and Supporting Metrics

- **North Star Metric (NSM):** the single metric that best captures the core value your product delivers to users. Leading indicator of long-term revenue.
- **Supporting metrics:** 3–5 metrics that drive or explain the NSM. One per strategic theme or team.
- **Counter-metrics:** guardrail metrics that flag if optimising the NSM creates unintended harm (e.g., quality drops while quantity rises).

### Leading vs. Lagging Indicators

| Type | Description | Example |
|------|-------------|---------|
| **Leading** | Predictive — changes before outcomes do | Daily active users, feature adoption rate |
| **Lagging** | Confirming — measures outcomes after the fact | Monthly revenue, annual churn rate |

Use both: leading indicators help you act in time; lagging indicators confirm results.

### Metrics and Validation Milestones

Every metric you track should answer a validation question: does the problem exist, does the solution work, will people pay, does usage retain? Tie each metric to the milestone it validates and to the PMF signals you are watching — see [pmf-signals.md](../../01_strategy/product-market-fit/pmf-signals.md).

| Validation milestone | Metrics that prove it | Status |
|----------------------|-----------------------|--------|
| Problem validated | [e.g., % of interviews confirming the pain] | [Fill in] |
| Solution works | [e.g., activation rate, task completion] | [Fill in] |
| Willingness to pay | [e.g., conversion to paid, pilot signings] | [Fill in] |
| Retention holds | [e.g., week-4 retention flattening] | [Fill in] |

---

## North Star Metric

**NSM:** [Fill in: the one metric that best captures value delivered to users]

**Definition:** [Fill in: precise definition — what counts, what doesn't, how it is calculated]

**Current value:** [Fill in]

**Target:** [Fill in]

**Why this metric:** [Fill in: one sentence explaining why this captures core value]

---

## Events to Track — AARRR Funnel

Replace placeholder event names with the actual events relevant to your product.

### Acquisition

| Event | Trigger | Properties |
|-------|---------|------------|
| [e.g., Landing Page Visited] | User arrives on main landing page | source, medium, campaign |
| [e.g., Signup Started] | User opens registration flow | referral_source |
| [e.g., Signup Completed] | User creates account | plan_type |

### Activation

| Event | Trigger | Properties |
|-------|---------|------------|
| [e.g., Onboarding Completed] | User finishes setup flow | steps_completed |
| [e.g., First Core Action Taken] | User performs the key value action | feature_name |
| [e.g., Aha Moment Reached] | User reaches the defined aha moment | session_number |

### Retention

| Event | Trigger | Properties |
|-------|---------|------------|
| [e.g., Weekly Active Session] | User logs in and takes action in a week | week_number |
| [e.g., Feature Used Multiple Times] | Repeat usage of a core feature | feature_name, usage_count |
| [e.g., Return Visit After Lapse] | User returns after 7+ days away | days_since_last_visit |

### Referral

| Event | Trigger | Properties |
|-------|---------|------------|
| [e.g., Invite Sent] | User sends an invitation | channel |
| [e.g., Referral Signup Completed] | Referred user completes signup | referrer_id |

### Revenue

| Event | Trigger | Properties |
|-------|---------|------------|
| [e.g., Pricing Page Viewed] | User visits pricing | plan_viewed |
| [e.g., Trial Started] | User activates a trial | trial_type |
| [e.g., Subscription Purchased] | User completes checkout | plan, amount, billing_cycle |
| [e.g., Subscription Renewed] | Subscription auto-renews | plan, period |

---

## Reporting Cadence

| Cadence | Audience | Metrics Reviewed | Owner |
|---------|---------|-----------------|-------|
| Weekly | Founders / team | [Fill in: e.g., activation rate, usage, experiment results] | [Name] |
| Monthly | Founders | [Fill in: e.g., NSM, retention curves, burn vs. plan] | [Name] |
| Monthly / Quarterly | Investors | [Fill in: e.g., PMF signals, growth rate, runway] | [Name] |

## Product Map AI Agent

Fill in this context file with the **[Make data-driven decisions](https://productmap.dev/profile/assistant/fa0d4967-95ad-4ad1-85d3-ffbea8996e07/chat/analysis)** agent on [Product Map](https://productmap.dev/profile/assistant/fa0d4967-95ad-4ad1-85d3-ffbea8996e07). Use it to define your north star metric, build a metrics dashboard, and tie tracking to validation milestones and PMF signals.

## Related

- [kpis-metrics.md](./kpis-metrics.md)
- [PMF Signals](../../01_strategy/product-market-fit/pmf-signals.md)
- [Experiments](../../02_discovery/experiments/experiments.md)
