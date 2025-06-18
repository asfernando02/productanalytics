# SaaS User Funnel and Retention Analysis
In this project, I simulated user behavior data for a SaaS product and conducted a full funnel and retention analysis using Python, SQL (SQLite), and data visualization techniques. The goal was to understand how users move through the product lifecycle and identify points of churn or engagement.

## Key Components:

### Synthetic Data Generation:
Created realistic user and event datasets, including signups, email verification, logins, and upgrades across various device types and countries.

### Funnel Analysis:
Tracked users through the core activation funnel:

signup → verify_email → login → upgrade

Quantified drop-off at each stage using both pandas and SQL to simulate real-world querying workflows.

### Retention Cohort Analysis:

Grouped users into weekly cohorts based on signup date.

Calculated D1, D7, D30 login retention behavior.

Visualized results as a heatmap, normalized by cohort size to express retention as a percentage.

### Insights:

Identified which cohorts had stronger retention over time.

Observed typical behavior patterns such as drop-offs after signup or Day 1.

Demonstrated how product teams can use cohort analysis to measure the impact of changes to onboarding, product features, or marketing.

