# Statistical Review and A/B Testing for TikTok Claims Project

## Project Overview
The TikTok data team's objective is to develop a machine learning model to assist in the classification of claims for user submissions. In this phase of the project, the data team conducted a hypothesis test to analyze the relationship between `verified_status` and `video_view_count`. The goal was to determine whether there is a statistically significant difference in the number of views for TikTok videos posted by verified accounts versus unverified accounts.

## Project Details
The TikTok data team focused on understanding the relationship between `verified_status` and `video_view_count`. Two primary approaches were taken:

1. **Mean Value Analysis:** The team examined the mean values of `video_view_count` for each group of `verified_status` in the sample data. The findings revealed that the majority of accounts were unverified, with 265,663 unverified accounts and 91,439 verified accounts.

2. **Two-Sample Hypothesis Test:** In alignment with the preliminary mean value findings, a two-sample hypothesis test was conducted. This statistical analysis aimed to determine if any observed difference in the sample data is due to an actual difference in the corresponding population means.

## Key Insights
The analysis demonstrates that there is a difference in the number of views between TikTok videos posted by verified accounts and TikTok videos posted by unverified accounts. These findings suggest the possibility of fundamental behavioral differences between these two groups of accounts: verified and unverified.

It would be valuable to investigate the root cause of this behavioral difference. Some questions to consider include:
- Do unverified accounts tend to post more engaging videos?
- Is the engaging content related to claims or opinions?
- Are unverified accounts associated with spam bots that help inflate view counts?

## Suggestions
The data team suggests moving forward by building a regression model on `verified_status`. A regression model for `verified_status` can provide insights into user behavior within the group of verified users. This contextual information can be used to interpret results from a claim classification model, which will be developed in the subsequent phases of the project.
