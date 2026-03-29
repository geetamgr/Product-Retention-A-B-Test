-> A mobile app is experencing low user retention after signup.
-> Only 30% of user return after 7days

Goal: Increase 7-day retention rate

Product question: Why are users dropping off and how can we improve retention?

# Daily Analysis(User Behaviour)
Dataset
- user_id          - feature_usage
- signup_date      - time_spent
- session_count    - country
  
# Analysis you perform
- cohort analysis(Day1, Day 7 retention)
- funnel:
        signup - first session - repeat usage
Insight: Users who do not use feature X in their first session are 40% less likely to return within 7 days.

# Metrics
- Rentention rate( Day 7)
- Engagement (session per user)
- feature adoption rate
- Conversion funnel drop-off
  
eg: Day 7 retention-> Returning users after 7 days/ total new users

# Experiment (A/B) test
Hypothesis: Encouraging users to use feature X in their first session will improve retention.
Experiment design:
Group              Description
Control            Normal Onboarding
Treatment          Highlight feature X during onboarding

Results:
- Control retention 30%
- Treatment retention 38%
+8% improvement

# Decision making
Roll out onboarding change to all users to increase retention and long-term engagement

# To improve onboarding feature adoption increase 7% day retention?
This project will include:
1. Simulated product data
2. SQL- style analysis in python
3. funnel and retention metrics
4. A/B test simulation
5. Statistical test
6. Final product decision

# Project overview: we'll assume a mobile app has
- New users signing up
- A key onboarding feature called feature_X
- A concern that users who do not use feature_X early tend to churn

# We want to measure:
- Measure onboarding funnel performance
- Check whether feature_X usage relates to retention
- Run an A/B test where treatment users see a prompt encouraging feature_X
- Decide whether to roll out the change


