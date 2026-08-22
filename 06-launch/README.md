# RouteLogic Velocity: Simplifying Compliance for Dispatch Coordinators

> A faster, simpler compliance workflow that helps Dispatch Coordinators complete required tasks with less friction and fewer manual workarounds.

**Marcelo Siku · Product Management Cohort · Jun 2026** · https://github.com/Marcelopedro7/pm-final-project-

Prototype: https://dispatch-swift-flow.lovable.app/

---

## Final Project Deliverables

### Slide 5 · Strategy
- **Problem:** Customers may churn as competitors offer more efficient solutions, while operations teams are forced to rely on spreadsheets, mapping tools, and phone calls to manage route changes
- **Value proposition:** We will allow operations teams to pre-establish and optimize routes, while continuing to manage them offline when the main system is unavailable, reducing manual work and operational disruption.
- **Hypothesis:** I believe the One-Click Compliance Checklist for Dispatch Coordinators will increase Coordinator compliance-step completion by at least 12 percentage points versus Control at the 42-day read date. We will protect Core Dispatch CSAT, ensuring it remains at or above 4.0/5 throughout the experiment

### Slide 6 · Research
- **Competitive analysis:** Dispatch Coordinators rely on spreadsheets, mapping tools, WhatsApp, and phone calls as manual workarounds when RouteLogic workflows become slow, unreliable, or difficult to use. Leaner competitors offering more flexible workflows increase the risk of customer churn
- **Journey map:** Start shift → Review routes → Handle route changes → Complete compliance tasks → Coordinate with drivers → Shift handoff

### Slide 7 · Blueprint
- **Roadmap:** # Feature Roadmap, Module 4 · RouteLogic Velocity

**Team:** 2 engineers + 1 designer + 1 CS lead

## Strategic anchors
- **Persona:** Dispatch Coordinator
- **Primary metric:** Coordinator compliance-step completion rate, currently 48%.
- **Moment of misery:** System and connectivity failures disrupt route management, forcing the dispatcher to rely on WhatsApp, phone calls, and other manual workarounds to keep drivers moving.
- **Guardrail:** Core Dispatch CSAT, currently 4.1/5, must not decline.

## Scoring
| Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|
| B1 One-Click Compliance Checklist | 5 | 2 | Quick Win | Now | Directly attacks the 48% completion metric — collapsing 14.6 min into a pre-filled form is the single fastest lever we have on the primary KPI. |
| B2 Smart Daily Report Auto-Fill | 3 | 4 | Time Sinker | Later | AI auto-fill is engineering-cool but solves a report that isn't the compliance step or the connectivity failure — expensive distraction from the anchors. |
| B3 Shift Handoff Wizard | 4 | 3 | Major Project | Later | Real time savings (6.8 min/day), but it's adjacent to the core friction, not the friction itself — nice-to-have once compliance and connectivity are solved. |
| B4 Mobile-First Coordinator Dashboard | 5 | 5 | Major Project | Next | High value (consolidates compliance/handoff/dispatch), but a full IA rebuild in 2 taps isn't a 4-week, 2-engineer job — roadmap item, not pilot scope. |
| B5 Step Progress Indicator | 2 | 1 | Fill-In | Later | Cheap polish that may nudge completion rate slightly, but it's a UI garnish, not a fix for the underlying 14.6-min bottleneck. |
| B6 Driver Alert Notifications | 3 | 3 | Time Sinker | Next | Hits the Moment of Misery head-on — this is the feature that can actually displace WhatsApp/phone-call workarounds during connectivity gaps. |
| B7 Contextual AI ETA Display | 1 | 3 | Time Sinker | Cut | 11% adoption is a signal, not a fluke — building further on a feature Coordinators are already ignoring is effort with no proven demand. |
| B8 Fleet Analytics Manager View | 1 | 4 | Time Sinker | Cut | This serves the Manager/Exec persona, not the Dispatch Coordinator — classic stakeholder-driven ask that doesn't belong in a Coordinator-focused pilot. |
| B9 Compliance Audit Trail Export | 2 | 2 | Fill-In | Later | Touches the compliance domain but serves auditors, not the Coordinator's daily pain — low frequency, low urgency for this persona. |
| B10 In-App Coordinator Training | 2 | 3 | Time Sinker | Cut | Doesn't move the needle for your existing 48%-completion NOW: B1 One-Click Compliance Checklist
NEXT: B6 Driver Alert Notifications
LATER: B4 Mobile-First Coordinator Dashboard; B3 Shift Handoff Wizard
CUT: B7 Contextual AI ETA Display; B8 Fleet Analytics Manager View
- **PRD highlights:** Feature: One-Click Compliance Checklist
Persona: Dispatch Coordinator
Must-have: Pre-filled compliance form with all required fields in one simple flow
Should-have: Save progress if the Coordinator leaves before submitting
Could-have: Progress indicator showing checklist completion
Won’t-have (now): AI-generated compliance recommendations
Flow: Compliance Overview → Pre-Filled Checklist → Completion Confirmation
- **Prototype:** https://dispatch-swift-flow.lovable.app/

### Slide 8 · Validation
Hypothesis: One-Click Compliance Checklist will increase Coordinator compliance-step completion by ≥12 percentage points vs. Control while maintaining Core Dispatch CSAT ≥4.0/5.
Control: Current compliance workflow without the checklist.
Variant: Current compliance workflow with the One-Click Compliance Checklist enabled.
Metrics: Compliance completion rate; baseline 48%, MDE +12pp, guardrail CSAT ≥4.0/5; 270 users/arm, 50/50 split, 42 days, p < 0.05.
Shipping criteria: Ship if completion improves by ≥12pp vs. Control at p < 0.05 and CSAT remains ≥4.0/5 at the fixed 42-day read date.

### Slide 9 · Launch
- **GTM:** Goal: Engagement — deepen adoption by making compliance faster and easier.
Audience: Existing Dispatch Coordinators responsible for RouteLogic’s daily compliance workflow.
Tier: M — Targeted rollout across selected customer accounts.
Channels: Owned — in-app banner, targeted launch email, and Help Center
- **Metrics:** Success metrics: Coordinator compliance-step completion rate (target ≥60%), One-Click Compliance Checklist adoption rate, and average compliance completion time.
Bad signal: Checklist adoption increases but compliance completion remains near the 48% baseline — users are trying the feature, but it is not resolving the core friction.

### Slide 10 · Story
- **Friction + aha:** TFriction point: The hardest part was filtering a large amount of qualitative and quantitative evidence without jumping straight to solutions.
Aha moment: I realized that the biggest user complaint is not always the most important product problem. Connecting user friction to the 48% compliance completion rate helped me prioritize the problem with the strongest measurable impact.
- **Takeaways / next:** Key takeaway: Strong product decisions come from connecting user pain, business impact, and measurable evidence rather than jumping directly to features.
What I’d do next: Run the 42-day experiment, analyze both quantitative results and Coordinator feedback, and expand the rollout if the One-Click Compliance Checklist reaches the success criteria.

---

Submitted to the Product Management Certification learning platform · Product School.
