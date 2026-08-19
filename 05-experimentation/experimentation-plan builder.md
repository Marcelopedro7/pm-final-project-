# A/B Experiment Brief, RouteLogic (B2B)

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | One-Click Compliance Checklist |
| Persona | Dispatch Coordinator |
| Expected outcome | Increase Coordinator compliance-step completion from 48% to at least 60%. |
| Primary success metric | Coordinator compliance-step completion rate |
| Baseline rate | 48% |
| Guardrail metric | Core Dispatch CSAT |
| Guardrail boundary | must stay at 4.0/5 or higher |
| Second guardrail | · |
| Minimum Detectable Effect | +12 pts |
| Sample size per arm | 270 users per arm |
| Traffic split | 50 / 50 |
| Test duration | 42 days (6 weekly cycles) |
| Significance threshold | 95% (p < 0.05) |

## Control vs. Variant
- **Control (A):** Current compliance workflow, without the One-Click Compliance Checklist
- **Variant (B):** Current compliance workflow, with the One-Click Compliance Checklist enabled
- **Held constant (isolation check):** All other RouteLogic features, workflows, user permissions, and notifications remain unchanged

## Hypothesis
> I believe that One-Click Compliance Checklist for Dispatch Coordinator will result in Increase Coordinator compliance-step completion from 48% to at least 60%., as measured by a +12 pts change in Coordinator compliance-step completion rate within 42 days (6 weekly cycles). We will protect Core Dispatch CSAT throughout the test.

## Shipping criteria
> We will **ship** if Coordinator compliance-step completion rate improves by ≥ +12 pts at 95% (p < 0.05) and Core Dispatch CSAT does not reach must stay at 4.0/5 or higher after 42 days (6 weekly cycles).
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 42 days (6 weekly cycles), no results reviewed before this date.
