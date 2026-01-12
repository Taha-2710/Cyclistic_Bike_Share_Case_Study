# Cyclistic_Bike_Share_Case_Study
Case Study: How does a bike-share navigate speedy success ?

# Business Problem:
The business task is to analyze historical Cyclistic bike share data and to identify the behavioral pattern of bike use so that marketing team make targeted strategies to convert casual rider into members, there by increasing long-term profit of the organisation.

# Key Stakeholders
a-Lily Moreno, Director of Marketing
b-Cyclistic Marketing Team 
c-Cyclistic Executive Team

# Data Overview
This analysis uses Cyclistic’s historical bike-share trip data provided by Motivate International Inc., consisting of approximately 5.9 million individual trip records. The dataset covers the period from January 2024 to December 2024, providing a complete annual view of bike-share usage.
As first-party operational data collected directly through Cyclistic’s system, the dataset is current and reliable. Due to data privacy constraints, demographic details about riders are not available. Consequently, the analysis focuses on behavioral patterns, which are derived from key trip-level fields such as ride start and end timestamps.

# Data Cleaning and Validation
The dataset was initially reviewed in Microsoft Excel to assess structure, formatting, and data completeness. Python (pandas) was then used for systematic cleaning, transformation, and preparation of trip-level records, while Tableau was used for visualization.

Key cleaning and processing steps included:

Standardizing ride start and end timestamps to datetime format.

Creating calculated fields for ride_duration_sec and ride_duration_min to support duration-based analysis.

Retaining records with missing station names at the early stage, as they contained valid trip duration data and were flagged for further review.

Adding a Week_Day field to enable time-based behavioral analysis.

During validation, trips with zero duration or durations under 60 seconds were identified and removed, as they likely represented system errors, cancellations, or non-meaningful rides.

All cleaning steps were applied consistently across monthly datasets to ensure standardized column names, formats, and data types. The cleaned monthly files were then merged into a single consolidated dataset. Final validation checks confirmed that values fell within expected ranges, resulting in a reliable dataset suitable for downstream analysis and visualization.

