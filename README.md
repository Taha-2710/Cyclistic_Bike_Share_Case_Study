Business Problem

Cyclistic aims to increase annual memberships.
This case study analyzes historical ride behavior to identify actionable differences between casual riders and members, enabling targeted marketing strategies that drive long-term profitability.

Key Stakeholders

Lily Moreno — Director of Marketing

Cyclistic Marketing Team

Cyclistic Executive Team

Data Overview

~5.9 million trip-level records

Jan 2024 – Dec 2024 (full annual coverage)

First-party operational data from Motivate International Inc.

No demographic data due to privacy constraints

Approach:
Behavioral analysis using trip timing, duration, and frequency.

Tools Used

SQL — aggregation & behavioral queries

Python (pandas) — cleaning, validation, feature engineering

Tableau — stakeholder-ready visualizations

Excel — initial data inspection

Data Cleaning & Validation

Key steps:

Standardized ride start/end timestamps

Engineered ride_duration_sec and ride_duration_min

Retained trips with missing station data (flagged, not discarded)

Added weekday feature for temporal analysis

Removed invalid rides (<60 seconds, zero-duration)

Monthly datasets were standardized and merged into a consolidated, validated dataset suitable for analysis.

Analysis — Rider Behavior Insights

1️⃣ Ride Duration & Seasonality

Casual riders take longer rides, especially during warmer months

Members show stable ride durations year-round
➡ Indicates leisure-driven vs utility-driven usage

2️⃣ Weekday vs Weekend Usage

Casual riders peak on weekends

Members ride consistently across all days
➡ Habitual usage defines membership value

3️⃣ Ride Frequency

Members complete significantly more trips overall
➡ Value comes from frequency, not ride length

🔑 Key Insight

Casual riders who begin riding frequently — even with short trips — are the strongest candidates for membership conversion.
Short rides. Big habits. That’s where the subscription magic lives.

Recommendations — Driving Membership Conversion

1. Target High-Frequency Casual Riders
Focus on casual riders with repeated usage across weekends or months.
Action: In-app or email-based limited-time membership trials.

2. Position Membership Around Convenience
Emphasize ease, spontaneity, and routine — not just cost savings.
Action: Shift messaging toward everyday usability.

3. Time Campaigns Strategically
Casual riding peaks on weekends and during warmer months.
Action: Run seasonal and weekend-focused conversion campaigns.

Right rider. Right message. Right time.

Business Impact

A behavior-driven marketing approach allows Cyclistic to:

Improve conversion efficiency

Reduce untargeted outreach

Increase long-term member value and retention
