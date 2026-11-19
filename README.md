# B2B buying signals: open daily data

Daily counts of B2B buying signals found by [Vendo AI](https://vendo-ai.com/), grouped by broad signal type, with the number of decision-makers found for those signals. Aggregates only: no names, no
companies, no contact data.

Live report with charts: **[https://vendo-ai.com/b2b-buying-signals-report/](https://vendo-ai.com/b2b-buying-signals-report/)**

## Latest window: October 23, 2026 to November 18, 2026

| Signal type | Signals | Decision-makers |
|---|---:|---:|
| Hiring | 22,326 | 6,456 |
| Funding and company news | 16,775 | 2,712 |
| Local business | 16,592 | 24,801 |
| Leadership changes | 5,923 | 4,140 |
| Tech and product intent | 4,665 | 450 |
| Social and LinkedIn intent | 2,584 | 674 |
| **All types** | **68,865** | **39,233** |

About 17,854 signals in an average week.

## Files

| File | Rows | Columns |
|---|---:|---|
| `data/daily_by_type.csv` | 162 | date, signal_type, signals, decision_makers |

Coverage so far: 2026-10-23 to 2026-11-18. The files grow every week; older days are kept.

## Methodology

A buying signal is a public event that shows a company may be ready to buy, such as hiring for a related role, a
funding round, a new leader, a change in tools or a new location. Vendo AI finds these events every day and matches
each one to the person who decides at that company. The files count the signals by broad type and the
decision-makers found for them. The mix reflects the markets Vendo AI customers sell to, so treat the data as a view
of what is visible, not a census. Today is never included until the day is complete.

## Licence and citation

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite as:

> Vendo AI, B2B Buying Signals Report, November 2026. https://vendo-ai.com/b2b-buying-signals-report/

Questions: info@vendo-ai.com
