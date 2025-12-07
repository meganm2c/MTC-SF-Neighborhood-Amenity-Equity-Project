| variable_name     | acs_code    | description                         | why_needed                                                   |
|:------------------|:------------|:------------------------------------|:-------------------------------------------------------------|
| pop_total         | B03002_001E | Total population                    | Normalization denominator for all per-capita amenity metrics |
| white_nonhisp     | B03002_003E | White Non-Hispanic (count)          | Demographic composition (race)                               |
| pct_white_nonhisp | derived     | White Non-Hispanic proportion       | Key racial equity variable                                   |
| gini              | B19083_001E | Income inequality (0–1)             | Income inequality metric for regressions                     |
| median_income     | B19013_001E | Median household income             | Economic stratification and control variable                 |
| poverty_denom     | B17001_001E | Poverty denominator                 | Required for poverty rate                                    |
| poverty_count     | B17001_002E | Poverty count                       | Required for poverty rate                                    |
| poverty_rate      | derived     | Poverty rate                        | Socioeconomic covariate (SES)                                |
| transit_commuters | B08301_010E | Workers commuting by public transit | Commute access proxy (accessibility indicator)               |