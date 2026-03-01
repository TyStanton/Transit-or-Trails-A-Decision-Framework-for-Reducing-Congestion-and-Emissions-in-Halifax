# Data Wrangling Documentation (Milestone 2)

## Dataset 1: Nova Scotia Traffic Volumes (Provincial Highway System)

### Issues Identified
- Dataset covers the entire province; must filter to Halifax-area segments.
- Multiple columns not relevant to analysis.
- Potential missing values for some segments/years.

### Wrangling Steps
- Filtered to Halifax-area highway segments (based on available location fields).
- Selected key columns: year (or count year), location/segment identifier, AADT (traffic volume).
- Removed incomplete records where AADT is missing.
- Standardized year format and ensured AADT is numeric.

### Assumptions
- AADT is used as a proxy for congestion pressure and private vehicle dependence.
- Halifax-area segments approximate commuting and traffic pressure relevant to HRM’s investment choices.

---

## Dataset 2: HRM Open Data (Selected Transportation-Related Dataset)

### Issues Identified
- HRM provides many datasets; not all are relevant to transportation/mobility.
- Format varies by dataset (field names, coordinate fields, date formats).

### Wrangling Steps
- Selected HRM dataset(s) directly relevant to transportation infrastructure or mobility context.
- Removed non-essential metadata fields.
- Standardized column names and date formats where applicable.
- Prepared dataset for visualization (aggregations or counts where needed).

### Assumptions
- HRM dataset provides supporting context for local infrastructure patterns and constraints.
