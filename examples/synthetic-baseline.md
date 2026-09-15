# Synthetic Baseline Example

This example demonstrates the calculation pattern with invented values.

Assume a small appointment-based business recorded the following accepted appointments across six months:

| Month | Accepted appointments |
| --- | ---: |
| Jan | 382 |
| Feb | 401 |
| Mar | 417 |
| Apr | 389 |
| May | 405 |
| Jun | 396 |

Total accepted appointments = **2,390**

Working monthly baseline:

```text
2,390 ÷ 6 = 398.3 accepted appointments/month
```

## Why this is only a working baseline

The first calculation is easy. The harder part is deciding what it means.

Before using the result for strategy, the analyst should verify:

- whether every month uses the same status definition
- whether accepted appointments are a reasonable proxy for completed services
- whether cancellations or duplicate records materially distort the result
- whether the six-month period reflects normal operations

The output should therefore be framed as a **working operating baseline**, not a perfect measure of completed demand.