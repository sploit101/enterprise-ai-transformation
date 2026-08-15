# Scoring Methodology

## Why I used a scoring model

A list of AI ideas is easy to create. The harder part is deciding which ideas deserve attention first.

For this student case study, I used a deliberately simple model that can be explained in a meeting and adjusted if stakeholders disagree with the weights.

## Scoring dimensions

Each qualitative dimension is scored from **1 (low)** to **5 (high)**.

| Dimension | Weight | Interpretation |
|---|---:|---|
| Business Value | 30% | Expected contribution to cost, revenue, service, quality or productivity |
| Feasibility | 20% | Technical and process practicality |
| Data Readiness | 15% | Availability and usability of required data |
| Ease of Implementation | 15% | Inverse of implementation effort |
| Risk Advantage | 10% | Inverse of risk level |
| ROI Attractiveness | 10% | Simple annual-value / implementation-cost ratio |

## Formula

`Priority Score = weighted average of the six 1-5 dimensions x 20`

This gives a score between 20 and 100.

### Priority tiers

- **High:** score >= 80
- **Medium:** score 65-79.9
- **Low:** score < 65

### Quick-win rule

A use case is marked as a quick win when:

- Priority Score >= 80
- Feasibility >= 4
- Implementation Effort <= 3
- Risk <= 3

## Important limitation

This is not a financial investment model or a universal AI maturity framework. Real companies would validate the assumptions with process owners, IT, data protection, security, finance and other stakeholders before funding a pilot.
