# Data Dictionary Template

Use this file to document every important field in your dataset. A strong data dictionary makes your cleaning decisions, KPI logic, and dashboard filters much easier to review.

## How To Use This File

1. Add one row for each column used in analysis or dashboarding.
2. Explain what the field means in plain language.
3. Mention any cleaning or standardization applied.
4. Flag nullable columns, derived fields, and known quality issues.

## Dataset Summary

| Item | Details |
|---|---|
| Dataset name | _Fill in_ |
| Source | _Fill in_ |
| Raw file name | _Fill in_ |
| Last updated | _Fill in_ |
| Granularity | _e.g. one row per order / customer / transaction / day_ |

## Column Definitions

| Column Name | Data Type | Description | Example Value | Used In | Cleaning Notes |
|---|---|---|---|---|---|
| _column_1_ | _string / int / float / date_ | _What this field means_ | _sample_ | _EDA / KPI / Tableau_ | _Null handling, type casting, renaming, standardization_ |
| _column_2_ | _string / int / float / date_ | _What this field means_ | _sample_ | _EDA / KPI / Tableau_ | _Null handling, type casting, renaming, standardization_ |
| _column_3_ | _string / int / float / date_ | _What this field means_ | _sample_ | _EDA / KPI / Tableau_ | _Null handling, type casting, renaming, standardization_ |
| _column_4_ | _string / int / float / date_ | _What this field means_ | _sample_ | _EDA / KPI / Tableau_ | _Null handling, type casting, renaming, standardization_ |

## Derived Columns

| Derived Column | Logic | Business Meaning |
|---|---|---|
| _kpi_field_1_ | _formula or transformation_ | _Why this derived field matters_ |
| _kpi_field_2_ | _formula or transformation_ | _Why this derived field matters_ |

## Data Quality Notes

- _List important caveats such as missing time periods, duplicate records, inconsistent category labels, or outlier handling._
