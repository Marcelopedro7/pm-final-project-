# Experimentation Plan (Module 5)

## Get your documents ready
- **From M3, your hypothesis sentence:** We believe that simplifying the compliance workflow for Dispatch Coordinators will increase compliance completion from 48% to at least 60% and reduce reliance on manual workarounds. We will test this through a 6-week pilot while ensuring Core Dispatch CSAT does not significantly decline from its current 4.1/5.
- **From M3, your primary success metric & guardrail metric:** Coordinator compliance-step completion rate, currently 48%, & Core Dispatch CSAT, currently 4.1/5, must not decline.
- **From M4, the feature you scoped in your PRD this is what you're testing:** One-Click Compliance Checklist

## Define your experiment parameters
- **Feature under test pull from your M4 PRD:** One-Click Compliance Checklist
- **Persona pull your M2 persona:** Dispatch Coordinator
- **Expected outcome the behaviour change you expect, from your M3 hypothesis:** Increase Coordinator compliance-step completion from 48% to at least 60%.
- **Primary success metric the one number that defines success, from M3:** Coordinator compliance-step completion rate
- **Baseline rate today's rate of your primary metric, from your M3 data:** 48%
- **Guardrail metric & boundary what must not break, and how far it can move before you investigate:** Core Dispatch CSAT — must remain at or above 4.0/5.
- **Minimum Detectable Effect (MDE) the smallest improvement worth shipping, your floor:** 12 percentage points
- **Sample size per arm use the calculator in the builder, baseline + MDE:** 270 users per arm
- **Traffic split & test duration 50/50 standard · cover ≥ 2 weekly cycles:** 6 weeks
- **Significance threshold p < 0.05 is standard, explain any deviation:** p < 0.05

## Define your control and variant
- **Control (A) the current experience, reference your M2 moment of misery and M3 funnel/workflow data:** Current RouteLogic compliance workflow without the One-Click Compliance Checklist.
- **Variant (B) your single change, copy the relevant screens & functional requirements from your M4 PRD:** Current RouteLogic compliance workflow with the One-Click Compliance Checklist enabled.
- **Isolation check, what has NOT changed? list everything identical between arms (app version, recommendation engine, notifications, onboarding). If something changed inadvertently, your test is compromised.:** All other RouteLogic features, workflows, user permissions, and notifications remain unchanged.

## Formalize your hypothesis & shipping criteria
- **Your hypothesis (filled in):** I believe that the One-Click Compliance Checklist for Dispatch Coordinators will increase compliance completion from 48% to at least 60%, as measured by a 12-percentage-point increase in Coordinator compliance-step completion rate within 6 weeks. We will protect Core Dispatch CSAT, ensuring it remains at or above 4.0/5 throughout the test.
- **Your shipping criteria (filled in):** We will SHIP if Coordinator compliance-step completion rate improves by at least 12 percentage points at p < 0.05 and Core Dispatch CSAT remains at or above 4.0/5 after 6 weeks. We will ITERATE if the result is positive but below the 12-percentage-point MDE. We will KILL if the compliance completion rate shows no improvement or declines. The read date is fixed at the end of 6 weeks, with no results reviewed before this date.
- **Hardest parameter to define, and did it change your hypothesis? quick debrief:** The MDE was the hardest parameter to define because I had to decide what level of improvement would be meaningful enough to justify shipping the feature. Setting it at 12 percentage points helped make the hypothesis more specific and measurable, but it did not fundamentally change the hypothesis.
