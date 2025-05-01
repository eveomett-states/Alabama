# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Alabama Json and Shapefile

This json and shapefile were created by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies. 

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on April 25, 2025:

[Population data](https://redistrictingdatahub.org/dataset/alabama-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[County data](https://redistrictingdatahub.org/dataset/alabama-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

[Congressional District data](https://redistrictingdatahub.org/dataset/2023-alabama-congressional-districts-plan-approved/): 2023 Alabama Congressional Districts Plan Approved

[State House District data](https://redistrictingdatahub.org/dataset/2021-alabama-state-house-adopted-plan/): 2021-2023 Alabama State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-alabama-state-senate-adopted-plan/): 2021 Alabama State Senate Approved Plan

[2024 election data](https://redistrictingdatahub.org/dataset/alabama-2024-general-election-precinct-level-results-and-boundaries/): Alabama 2024 General Election Precinct-Level Results and Boundaries

[2022 election data](https://redistrictingdatahub.org/dataset/alabama-2022-general-election-precinct-level-results-and-boundaries/): Alabama 2022 General Election Precinct-Level Results and Boundaries

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-alabama-precinct-and-election-results/): VEST 2020 precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-alabama-precinct-and-election-results/): VEST 2018 precinct and election results 

[2017 election data](https://redistrictingdatahub.org/dataset/vest-2017-alabama-precinct-and-election-results/): VEST 2017 precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-alabama-precinct-and-election-results/): VEST 2016 precinct and election results

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `VTDST20`: Voting tabulation district FIPS code
- `GEOID20`: VTD FIPS code
- `NAME20`: Voting tabulation district name
- `CD`: Congressional district ID in 2021 enacted congressional map
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2021 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `AGR17R`: Number of votes for 2017 Republican Commissioner of Agriculture candidate
- `AGR17O`: Number of votes for 2017 other party's Commissioner of Agriculture candidate
- `AGR18R`: Number of votes for 2018 Republican Commissioner of Agriculture candidate
- `AGR18O`: Number of votes for 2018 other party's Commissioner of Agriculture candidate
- `AGR22R`: Number of votes for 2022 Republican Commissioner of Agriculture candidate
- `AGR22O`: Number of votes for 2022 other party's Commissioner of Agriculture candidate
- `AJ522D`: Number of votes for 2022 Democratic Associate Justice 5 of the Supreme Court candidate
- `AJ522R`: Number of votes for 2022 Republican Associate Justice 5 of the Supreme Court candidate
- `AJ522O`: Number of votes for 2022 other party's Associate Justice 5 of the Supreme Court candidate
- `AJ622R`: Number of votes for 2022 Republican Associate Justice 6 of the Supreme Court candidate
- `AJ622O`: Number of votes for 2022 other party's Associate Justice 6 of the Supreme Court candidate
- `ATG17D`: Number of votes for 2017 Democratic attorney general candidate
- `ATG17R`: Number of votes for 2017 Republican attorney general candidate
- `ATG17O`: Number of votes for 2017 other party's attorney general candidate
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `ATG18O`: Number of votes for 2018 other party's attorney general candidate
- `ATG22D`: Number of votes for 2022 Democratic attorney general candidate
- `ATG22R`: Number of votes for 2022 Republican attorney general candidate
- `ATG22O`: Number of votes for 2022 other party's attorney general candidate
- `AUD17D`: Number of votes for 2017 Democratic Auditor candidate
- `AUD17O`: Number of votes for 2017 other party's Auditor candidate
- `AUD17R`: Number of votes for 2017 Republican Auditor candidate
- `AUD18D`: Number of votes for 2018 Democratic Auditor candidate
- `AUD18O`: Number of votes for 2018 other party's Auditor candidate
- `AUD18R`: Number of votes for 2018 Republican Auditor candidate
- `AUD22O`: Number of votes for 2022 other party's Auditor candidate
- `AUD22R`: Number of votes for 2022 Republican Auditor candidate
- `CFJ24D`: Number of votes for 2024 Democratic Chief Justice of the Supreme Court candidate
- `CFJ24R`: Number of votes for 2024 Republican Chief Justice of the Supreme Court candidate
- `CFJ24O`: Number of votes for 2024 other party's Chief Justice of the Supreme Court candidate
- `GOV17D`: Number of votes for 2017 Democratic gubernatorial candidate
- `GOV17R`: Number of votes for 2017 Republican gubernatorial candidate
- `GOV17O`: Number of votes for 2017 other party's gubernatorial candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `GOV22D`: Number of votes for 2022 Democratic gubernatorial candidate
- `GOV22R`: Number of votes for 2022 Republican gubernatorial candidate
- `GOV22O`: Number of votes for 2022 other party's gubernatorial candidate
- `LTG17D`: Number of votes for 2017 Democratic Lieutenant Governor candidate
- `LTG17R`: Number of votes for 2017 Republican Lieutenant Governor candidate
- `LTG17O`: Number of votes for 2017 other party's Lieutenant Governor candidate
- `LTG18D`: Number of votes for 2018 Democratic Lieutenant Governor candidate
- `LTG18R`: Number of votes for 2018 Republican Lieutenant Governor candidate
- `LTG18O`: Number of votes for 2018 other party's Lieutenant Governor candidate
- `PRE16D`: Number of votes for 2016 Democratic Presidential candidate
- `PRE16R`: Number of votes for 2016 Republican Presidential candidate
- `PRE16O`: Number of votes for 2016 other party's Presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic Presidential candidate
- `PRE20R`: Number of votes for 2020 Republican Presidential candidate
- `PRE20O`: Number of votes for 2020 other party's Presidential candidate
- `PRE24D`: Number of votes for 2024 Democratic Presidential candidate
- `PRE24R`: Number of votes for 2024 Republican Presidential candidate
- `PRE24O`: Number of votes for 2024 other party's Presidential candidate
- `PSC16R`: Number of votes for 2016 Republican President, Public Service Commission candidate
- `PSC16O`: Number of votes for 2016 other party's President, Public Service Commission candidate
- `PSC17D`: Number of votes for 2017 Democratic President, Public Service Commission candidate
- `PSC17R`: Number of votes for 2017 Republican President, Public Service Commission candidate
- `PSC17O`: Number of votes for 2017 other party's President, Public Service Commission candidate
- `PSC18D`: Number of votes for 2018 Democratic President, Public Service Commission candidate
- `PSC18R`: Number of votes for 2018 Republican President, Public Service Commission candidate
- `PSC18O`: Number of votes for 2018 other party's President, Public Service Commission candidate
- `PSC20D`: Number of votes for 2020 Democratic President, Public Service Commission candidate
- `PSC20R`: Number of votes for 2020 Republican President, Public Service Commission candidate
- `PSC20O`: Number of votes for 2020 other party's President, Public Service Commission candidate
- `SAC17R': Number of votes for 2017 Republican 
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State candidate
- `SOS18R`: Number of votes for 2018 Republican Secretary of State candidate
- `SOS18O`: Number of votes for 2018 other party's Secretary of State candidate
- `TRE18D`: Number of votes for 2018 Democratic Treasurer candidate
- `TRE18R`: Number of votes for 2018 Republican Treasurer candidate
- `TRE18O`: Number of votes for 2018 other party's Treasurer candidate
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
