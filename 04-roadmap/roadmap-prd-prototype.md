# Feature Roadmap, Module 4 · RouteLogic Velocity

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
| B10 In-App Coordinator Training | 2 | 3 | Time Sinker | Cut | Doesn't move the needle for your existing 48%-completion coordinators, and content build eats disproportionate designer/CS time this sprint. |

## Roadmap
### NOW, Pilot (4 weeks, 3 accounts)
- **B1 One-Click Compliance Checklist**, Directly attacks the 48% completion metric — collapsing 14.6 min into a pre-filled form is the single fastest lever we have on the primary KPI.

### NEXT, GA Release (weeks 5-8)
- **B4 Mobile-First Coordinator Dashboard**, High value (consolidates compliance/handoff/dispatch), but a full IA rebuild in 2 taps isn't a 4-week, 2-engineer job — roadmap item, not pilot scope.
- **B6 Driver Alert Notifications**, Hits the Moment of Misery head-on — this is the feature that can actually displace WhatsApp/phone-call workarounds during connectivity gaps.

### LATER, backlog
- **B2 Smart Daily Report Auto-Fill**, AI auto-fill is engineering-cool but solves a report that isn't the compliance step or the connectivity failure — expensive distraction from the anchors.
- **B3 Shift Handoff Wizard**, Real time savings (6.8 min/day), but it's adjacent to the core friction, not the friction itself — nice-to-have once compliance and connectivity are solved.
- **B5 Step Progress Indicator**, Cheap polish that may nudge completion rate slightly, but it's a UI garnish, not a fix for the underlying 14.6-min bottleneck.
- **B9 Compliance Audit Trail Export**, Touches the compliance domain but serves auditors, not the Coordinator's daily pain — low frequency, low urgency for this persona.

### ✂ Cut List
- **B7 Contextual AI ETA Display**, 11% adoption is a signal, not a fluke — building further on a feature Coordinators are already ignoring is effort with no proven demand.
- **B8 Fleet Analytics Manager View**, This serves the Manager/Exec persona, not the Dispatch Coordinator — classic stakeholder-driven ask that doesn't belong in a Coordinator-focused pilot.
- **B10 In-App Coordinator Training**, Doesn't move the needle for your existing 48%-completion coordinators, and content build eats disproportionate designer/CS time this sprint.
