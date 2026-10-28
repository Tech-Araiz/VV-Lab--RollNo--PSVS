# Defect Taxonomy for Requirements

| # | Category | Definition | Example (from PSVS) |
|---|----------|------------|---------------------|
| 1 | Ambiguity | A statement can be read in more than one valid way. | S10 "per year": calendar year or rolling 12 months? |
| 2 | Vagueness | Uses imprecise, unquantified terms with no threshold. | S6 "safe temperature"; S2 "a large number of boxes" |
| 3 | Incompleteness | Missing information needed to implement or test (actors, conditions, exceptions, error cases). | S1 does not say who registers depositors or how. |
| 4 | Contradiction | Two requirements (or parts of one) cannot both be satisfied. | S7 "never above -18°C" vs S8 "warmed to 0°C". |
| 5 | Non-verifiability | No practical test, measurement or inspection can show the requirement is met. | S12 "good audit trail" |
| 6 | Redundancy | The same requirement is stated more than once, risking divergence. | S2 is subsumed by the limits of S3. |
| 7 | Infeasibility | Cannot be achieved with realistic technology, cost or physical laws. | S7 "never" cannot be guaranteed during power or hardware failure. |
| 8 | Untraceability | No source, rationale or link to stakeholder need, or links to undefined downstream items. | S3 limits (50,000 / 20,000) have no stated rationale. |
| 9 | Inconsistent terminology | Different words used for the same concept (or one word for different concepts). | "withdraw" (S4, S10), "release" (S5), "withdrawn" (S11) |
