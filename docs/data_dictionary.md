# Data Dictionary
## Dataset Name: waze_dataset.csv
### Dataset Overview
Each row represents a user’s activity aggregated at a monthly level.
The target variable `label` indicates whether a user discontinued usage during the corresponding month.

### Columns Description
| Column Name | Type | Description |
|------------|------|-------------|
| ID | int | A sequential numbered index |
| label | obj | Binary target variable ("retained" vs "churned") indicating whether a user has churned at any time during the course of the month |
| sessions | int | Number of times a user opens the app during the month |
| drives | int | Number of occurrences where the user drives at least 1 km during the month |
| device | obj | Type of device used to start a session |
| total_sessions | float | Model-estimated total number of sessions since the user onboarded |
| n_days_after_onboarding | int | Number of days since the user signed up for the app |
| total_navigations_fav1 | int | Total number of navigations since onboarding to the user’s first favourite place |
| total_navigations_fav2 | int | Total number of navigations since onboarding to the user’s second favourite place |
| driven_km_drives | float | Total kilometres driven during the month |
| duration_minutes_drives | float | Total driving duration (in minutes) during the month |
| activity_days | int | Number of days the user opens the app during the month |
| driving_days | int | Number of days the user drives at least 1 km during the month |
