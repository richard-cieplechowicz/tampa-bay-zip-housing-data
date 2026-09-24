# Tampa Bay ZIP Code Housing and Rent Burden, 2020-2024

Compiled by Richard Cieplechowicz (Ryszard Cieplechowicz), Tampa Bay, Florida.
License: Creative Commons Attribution 4.0 International (CC BY 4.0). Free to use, share and adapt with credit.

## What this is
A ZIP-level (ZCTA) table of housing costs, rent burden, income and tenure for the four-county Tampa Bay metro: Hillsborough, Pinellas, Pasco and Hernando. 132 ZIP code tabulation areas with at least 500 residents.

## Source
U.S. Census Bureau, American Community Survey 2020-2024 5-year estimates, tables B01003, B01002, B19013, B25064, B25077, B25003, B25002, B25070. Retrieved via the Census Reporter API. ZIP-to-county assignment uses the Census Bureau 2020 ZCTA-to-county relationship file; each ZCTA is assigned to the county holding the largest share of its land area.

## Columns
- zip: 5-digit ZCTA
- county: assigned county
- population: total population (B01003)
- median_age: median age (B01002)
- median_household_income: dollars (B19013)
- median_gross_rent: dollars per month, rent plus utilities (B25064)
- median_home_value: owner-occupied units, dollars (B25077)
- occupied_units, renter_units: occupied housing units and renter-occupied units (B25003)
- renter_share_pct: renter units / occupied units
- vacancy_rate_pct: vacant units / all housing units (B25002)
- rent_burdened_30plus_pct: renters paying 30% or more of household income on gross rent, excluding "not computed" (B25070)
- severely_rent_burdened_50plus_pct: same, 50% or more
- rent_to_income_pct: median gross rent x 12 / median household income (a rough ZIP-level ratio, not a household measure)
- small_sample_flag: "yes" when the ZIP has fewer than 300 renter units; percentages there carry wide margins of error

## Limits
ACS figures are survey estimates with margins of error. ZCTAs approximate, but are not identical to, USPS ZIP codes. Values are 5-year averages, not a single year. Blank cells mean the Census Bureau did not publish an estimate.

## Suggested citation
Cieplechowicz, Richard (2026). Tampa Bay ZIP Code Housing and Rent Burden, 2020-2024. CC BY 4.0. Data: U.S. Census Bureau ACS 5-year estimates.
