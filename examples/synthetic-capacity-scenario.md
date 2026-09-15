# Synthetic Capacity Scenario

This example shows how a stretch target can be translated into operating requirements before treating it as a growth goal.

Assume:

- target: **600 appointments/month**
- average appointment duration: **75 minutes**
- 9 active providers

Required service hours:

```text
600 appointments × 75 minutes = 45,000 minutes
45,000 ÷ 60 = 750 service hours/month
```

Now compare that requirement with three staffing scenarios:

| Scenario | Provider-days/week | Productive hours/provider-day | Approx. monthly productive hours |
| --- | ---: | ---: | ---: |
| Conservative | 21 | 6 | 546 |
| Base | 30 | 7 | 910 |
| Flexible | 39 | 8 | 1,352 |

## Interpretation

The raw provider count does not answer the capacity question by itself.

The more useful questions are:

- How many provider-days recur each week?
- When are those hours available?
- Do providers cover the services customers are requesting?
- Are rooms, breaks, cancellations, or scheduling rules reducing usable capacity?

A business can have enough theoretical monthly hours while still having a peak-time or service-compatibility constraint.

These numbers are synthetic and are included only to demonstrate the modeling method.