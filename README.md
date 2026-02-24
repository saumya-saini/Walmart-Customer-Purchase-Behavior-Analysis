# walmart-eda

# Customer Purchase Behavior Analysis (CLT & Confidence Intervals)

Overview

This project analyzes retail transaction data (550K+ records) to understand how customer spending varies across gender, marital status, and age groups using statistical inference and the Central Limit Theorem (CLT).

The goal: determine whether spending differences are statistically meaningful and scalable to population level.

# Business Question

Do men spend more than women per transaction?

Do married customers spend more than unmarried customers?

Which age group contributes the highest revenue?

Can we estimate population averages reliably using sampling?

# Methodology

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Mean Comparison Across Segments

Confidence Interval Estimation (90%, 95%, 99%)

Bootstrapping

Central Limit Theorem validation (varying sample sizes)

# Key Findings

Men spend more per transaction than women

Married customers spend slightly more than unmarried customers

Age group 26–35 is the highest spending segment

Larger sample sizes produce narrower confidence intervals (CLT validated)

Spending differences are statistically reliable, not random

# Tools Used

Python

Pandas

NumPy

Seaborn

Matplotlib

SciPy
