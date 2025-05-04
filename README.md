# Medicare-Reimbursement-Patterns-by-State-2014-

## Table of content


- [Project objective](#project-objective)
- [Data source](#data-source)
- [Data Preparation Steps](#data-preparation-steps)
- [Conclusion](#conclusion)
- [Implication](#implication)



### Project overview:
This project analyzes 2014 Medicare reimbursement data across U.S. states to uncover geographic and service-based variations in healthcare spending per enrollee. Despite adjustments for age, sex, race, and local prices, notable disparities in Medicare costs persist, raising concerns about efficiency, access, and resource allocation. By breaking down reimbursements into hospital/skilled nursing, physician, and outpatient care, this analysis identifies high-cost drivers and highlights states that deliver care more efficiently. The resulting insights aim to support healthcare policymakers, providers, and analysts in making data-driven decisions to improve cost-effectiveness and equity in the Medicare system.


### Key issue:
Why do some states cost significantly more per Medicare enrollee than others, even after demographic and price adjustments?

### Project Objective:

The objective of this project is to:
Analyze Medicare reimbursement data (2014) by state to identify patterns and outliers.
Compare spending levels after adjusting for age, sex, race, and price.
Disaggregate costs by care type (hospital/SNF, physician, outpatient) to understand drivers.
Visualize geographic and service-based variation to support evidence-based policy decisions.
Provide actionable insights into potential efficiency gains or cost-control strategies for high-spending regions.

### Data Source
source: Centers for Medicare & Medicaid Services (CMS)
Dataset: Medicare Reimbursement Data by State (2014)[Download here] (https://data.world/adamhelsinger/county-state-medicare-spend/workspace/file?filename=pa_reimb_state_2014.xls)

### Variables:
Medicare enrollees per state, Total and adjusted reimbursements (age, sex, race, price), Service-specific reimbursements: hospital/skilled nursing, physician, outpatient, CMS regularly publishes this data to support transparency in healthcare spending and to enable analysis of regional differences in Medicare costs.

### Data Preparation Steps
Load Data, Imported the .xls file into  Power BI., Clean Column Names, Converted all headers to lowercase., Removed special characters and excessive words., Renamed long column names with shorter, meaningful labels (e.g., physician_reimb_price_adj)., Check for Missing Data, Verified that all numeric fields were populated., Handled missing or zero values if any (e.g., marked as NA or excluded from visual summaries)., Data Formatting, Ensured numeric values (e.g., reimbursements) were stored as numbers, not text., Rounded values to 2 decimals for clarity in charts.

#### Derived new insights: e.g., proportion of hospital cost out of total reimbursement.
Categorized states into high, medium, and low spending for comparison.
#### Visualization Preparation
Structured the data in tidy format for charts (rows = states, columns = metrics).
Geo-mapped states using standard U.S. state names or FIPS codes.

### Conclusion:

In 2014, Medicare reimbursement per enrollee varied widely across U.S. states, even after adjusting for age, sex, race, and price differences.
States like Florida and New York showed higher total reimbursements per enrollee, largely driven by hospital and skilled nursing facility costs.
States like Minnesota and Oregon demonstrated lower reimbursements, suggesting potentially more efficient healthcare delivery systems.
Price adjustments reduced spending differences in urbanized/high-cost regions but did not eliminate them, indicating that service usage intensity, not just price, plays a major role.
Hospital and skilled nursing reimbursements made up the largest share of costs in high-spending states, while outpatient services contributed more in efficient regions.

### Implication:

Policy interventions could focus on promoting outpatient care models, reducing unnecessary hospitalizations, and enhancing price transparency to contain Medicare costs.





