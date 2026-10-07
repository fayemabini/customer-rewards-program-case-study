# Risk Log

| ID | Risk | Impact | Likelihood | Mitigation / Recommendation | Status |
|---|---|---:|---:|---|---|
| R-01 | Reward value is too generous and harms margin | High | Medium | Model point economics before approval and set redemption caps | Open |
| R-02 | Reward value is too low to motivate customers | Medium | Medium | Validate customer value perception and monitor redemption rate | Open |
| R-03 | Users exploit repeatable actions to farm points | High | Medium | Add eligibility limits, cooldowns, and fraud rules | Open |
| R-04 | Refunds do not reverse points correctly | High | Medium | Include refund / cancellation cases in QA | Open |
| R-05 | Program is too complicated to understand | Medium | Medium | Keep rules simple and test customer-facing explanation | Open |
| R-06 | Website tracking fails for some actions | High | Low | Validate event tracking and create fallback handling | Open |
| R-07 | Support volume increases after launch | Medium | Medium | Prepare FAQ, internal support guide, and escalation process | Monitoring |

## Risk communication format

I prefer escalating risks with a recommendation attached.

Example:

> **Risk:** Course-completion points can currently be triggered more than once.
>
> **Recommendation:** Block launch of that earning rule until the trigger is limited to one reward per qualifying course completion.
