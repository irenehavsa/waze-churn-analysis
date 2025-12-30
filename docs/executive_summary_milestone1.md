# Waze Churn Analysis Project – Preliminary Data Summary

## Overview
The Waze data team is developing a data analytics initiative focused on supporting sustainable user growth by reducing monthly churn on the Waze application. In this context, churn refers to users who have uninstalled the app or have become inactive.

This executive summary presents a high-level overview of the data, current project status, and key findings from Milestone 1. These early insights inform the strategic direction and next phases of the project.

## Project Status

**Objective:** Identify meaningful relationships within user data that can inform churn-reduction strategies.

**Approach:**
* Constructed a structured analytical dataset
* Defined each row as a unique user observation and each column as a distinct variable
* Generated preliminary descriptive statistics
* Conducted initial behavioral analysis to surface patterns and trends

**Outcome:**
The analysis revealed several notable relationships between user behaviors and churn indicators. These findings establish a foundation for deeper exploration and targeted analysis in subsequent phases.

## Key Insights
* This dataset includes 14,999 users, of whom 82% are retained and 18% have churned.
* The dataset contains 12 unique variables, with data types including objects, floats, and integers.
* The label column has 700 missing values, with no evidence to suggest the missingness is non-random. These missing values account for less than 5% of the total rows.
* On average, churned users completed ~3 more drives in the last month than retained users.
* Retained users used the app on more than twice as many days as churned users during the last month.
* The median churned user drove ~200 additional kilometers and spent about 2.5 more hours driving in the last month compared with the median retained user.
* **Churned users concentrated more drives into fewer days, and their trips were longer in both distance and duration**. This pattern may indicate a user profile worth further investigation.
* The median churned user drove 698 kilometers per driving day in the last month, which is roughly 240% of the per–driving-day distance of retained users.
* **Regardless of churn status, users in this dataset drive extensively, suggesting that the data may not be representative of typical drivers in the general population**.

## Next Steps
* Prioritize additional data collection and analysis focused on super-drivers. Their high usage patterns may reflect unmet needs that differ from those of typical users and could be contributing to churn.
* Conduct comprehensive exploratory data analysis (EDA) and develop clear, decision-oriented visualizations to support data-driven recommendations and guide future product and analytics initiatives.
