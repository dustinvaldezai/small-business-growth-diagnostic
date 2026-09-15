# Synthetic Retention Snapshot

This example shows how customer-return behavior can be framed without overstating certainty.

Assume the observed customer history contains:

- 3,500 identifiable first-observed customers
- 3,100 customers old enough to have a full 90-day return window
- 620 of those eligible customers returned within 90 days
- 1,760 H1 visits, of which 1,080 came from customers with an earlier observed visit

Calculated signals:

```text
90-day return rate = 620 ÷ 3,100 = 20.0%
Share of H1 visits with an earlier observed visit = 1,080 ÷ 1,760 = 61.4%
```

## Interpretation

These two signals can coexist:

- repeat customers may contribute materially to current volume
- many first-observed customers may still fail to return quickly

That suggests retention deserves attention, but it does **not** prove that retention is the entire growth problem.

## Important caveat

If the available customer history begins on a fixed date, some people labeled first-observed may have visited before the dataset begins. Identity matching and deduplication can also affect the counts.

For that reason, this type of result should be described as **directional customer-behavior evidence**, not a perfect lifetime retention measure.

All values in this example are synthetic.