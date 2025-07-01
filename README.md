# 2017 Yellow Taxi Analysis

## Exploratory data analysis (EDA)

*Notebook: eda-yellow-taxi-trip-2017.ipynb*

### *When and where are peak trip volumes?*
Most of the peak trip volume is concentrated in pick-ups across Manhattan, with Upper East Side South, Midtown Center, and Penn Station/Madison Square West being the top three areas. Pick-up volume tends to peak in the evening on a daily basis and midweek on a weekly basis. Trip activity generally decreases during the summer months and in February.

### *Which times/zones generate highest revenue?*
A similar trend is observed in revenue: it tends to be higher in the evenings and midweek; while total revenue typically declines in the summer months and in February. Interestingly, pick-up from the two airports in Queens generated significantly higher revenue in 2017.

### *How does cash versus credit card behavior differ?*
Tip amounts made in cash are not captured in the data. Nevertheless, revenue from credit card payments overwhelmingly dominates across zones and time periods.

### *What factors are associated with higher tips (credit card only)?*
The data suggests that tip amounts are not strongly associated with common trip variables, implying that tipping may be more influenced by unmeasured behavioral factors, such as customer satisfaction, interaction quality, payment interface design, etc.
