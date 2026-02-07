# Bellabeat Case Study: Smart Device Usage Analysis

Analysis of FitBit tracker data to identify usage trends and inform Bellabeat's marketing strategy for their Leaf smart device.

**[📊 View Full Report](bellabeat-analysis.html)**

## Project Overview

**Business Question:** What are the trends in smart device usage, and how can these insights guide Bellabeat's marketing strategy?

**Data Source:** FitBit Fitness Tracker Data (30+ users, March-May 2016)

**Tools Used:** R, RStudio, tidyverse, lubridate

## Key Findings

### Device Engagement

- **11% of logged days** show device non-wear, indicating engagement drop-off
- User engagement varies widely: some users log consistently (40+ days), others drop off quickly (<10 days)

### Activity Patterns

- **Median daily steps: 7,881** on valid wear days
- **72.8% of days** show moderate-to-high activity (≥5,000 steps)
- **Light activity dominates:** Users average 3.5 hours of light activity vs. only 6 minutes of vigorous activity per day
- Activity patterns are consistent between weekdays and weekends

### Sleep Tracking

- **31% of users never track sleep** despite tracking activity
- Among sleep trackers, engagement is inconsistent (1-31 nights logged)
- Average sleep duration: 7 hours with 92% efficiency

## Recommendations

1. **Improve engagement:** Develop re-engagement features for users who show signs of dropping off
2. **Celebrate light activity:** Market the value of everyday movement, not just intense workouts
3. **Encourage sleep tracking:** Educate users on sleep tracking benefits and simplify the process
4. **Focus on consistency:** Help users build steady habits rather than sporadic bursts of activity

## Files in This Repository

- `bellabeat-analysis.html` — Full analysis report with code and visualizations
- `bellabeat-analysis.Rmd` — R Markdown source file
- `/data` — Raw datasets (FitBit tracker data)

## About

This case study was completed as part of the Google Data Analytics Certificate capstone project.

**Author:** Ayu  
**Date:** February 2025
