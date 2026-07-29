# Business Solutions & Recommendations

## 1. What percentage of users stop using the chatbot after their first few conversations?

### Findings

The analysis revealed that most users do not return immediately after using the chatbot. User retention after 1 day and 7 days was relatively low, while a larger proportion of users returned only after 30 days.

### Business Insight

The chatbot experiences weak early-stage user retention, indicating that users lose interest shortly after onboarding. This suggests that the initial user experience is not engaging enough to encourage continued usage.
19.71 users stop using the chatbot

### Recommendation

- Improve the onboarding experience.
- Introduce personalized welcome conversations.
- Send follow-up notifications within the first week.
- Reward users for consecutive days of usage.

---

# 2. Which user segments have the highest churn?

### Findings

The analysis indicates that user churn is primarily associated with poor chatbot experience rather than demographic characteristics.

returned_after_30_days	count(returned_after_30_days)	max_session_duration	avg_session_duration	max_days	avg_days
                  1            6565	                   403	                        38.1971	       119	   69.8932
                  0	           7247	                   221	                        24.5830	       119	   41.447

Users experiencing:

- Slow responses
- High error rates
- Poor network quality
- Low satisfaction
- Negative feedback

were more likely to discontinue using the chatbot.

### Business Insight

Poor product performance is the primary driver of churn rather than user demographics.

### Recommendation

- Improve chatbot response quality.
- Reduce technical issues.
- Monitor customer feedback continuously.

---

# 3. Does session duration affect retention?

### Findings

| Returned After 30 Days | Average Session Duration |
|-------------------------|-------------------------:|
| Yes | **38.20 minutes** |
| No | **24.58 minutes** |

Users who returned after 30 days spent significantly more time interacting with the chatbot than users who did not return.

### Supporting Evidence

TherapyBot-v2 achieved the highest maximum session duration (**403 minutes**), while TherapyBot-v2.5-Turbo recorded the lowest maximum session duration (**221 minutes**), indicating that TherapyBot-v2 was able to sustain longer user engagement.

### Business Insight

Longer chatbot sessions are associated with higher user retention, suggesting that users who have more engaging conversations are more likely to continue using the platform.

### Recommendation

- Improve conversation quality.
- Encourage longer user interactions through personalized conversations.
- Add conversation continuation suggestions.

---

# 4. Does conversation quality influence customer satisfaction?

### Findings

TherapyBot-v2.5-Turbo recorded:

- Slowest average response time
- Highest error rate
- Poor network quality
- Highest negative feedback
- Lowest customer satisfaction

### Business Insight

Conversation quality has a strong relationship with customer satisfaction. Slower responses and technical issues are associated with lower user satisfaction.

### Recommendation

- Improve chatbot response quality.
- Reduce response time.
- Improve model accuracy.
- Optimize server performance.

---

# 5. Which countries have the highest and lowest retention rates?

| Country | Retention Rate |
|----------|---------------:|
| Germany | **38.10%** |
| Australia | **38.02%** |
| Canada | **36.77%** |
| United Kingdom | **36.60%** |
| United States | **35.42%** |
| India | **35.01%** |

### Findings

- Highest Retention: **Germany (38.10%)**
- Lowest Retention: **India (35.01%)**

### Business Insight

Users in Germany and Australia demonstrate higher engagement and are more likely to continue using the chatbot. India and the United States show comparatively lower retention, indicating opportunities to improve the user experience in these markets.

### Recommendation

- Analyze customer feedback from low-retention countries.
- Improve localization and onboarding.
- Study successful user behavior in high-retention countries.

---

# 6. Which devices are associated with better user engagement?

| Device | Average Session Duration | Maximum Session Duration |
|---------|-------------------------:|-------------------------:|
| Mobile | **16.71 min** | **403 min** |
| Desktop | 16.53 min | 203 min |
| Tablet | 16.02 min | 172 min |

### Findings

Mobile users recorded both the highest average session duration and the longest individual session.

### Business Insight

Mobile devices provide the highest user engagement, suggesting users prefer interacting with the chatbot through mobile devices.

### Recommendation

- Continue optimizing the mobile application.
- Improve desktop and tablet user experience.
- Prioritize mobile-first feature development.

---

# 7. Does subscription status impact retention?

| User Type | Retention Rate |
|-----------|---------------:|
| Non-Subscriber | **36.54%** |
| Subscriber | **34.90%** |

### Findings

Non-subscribers showed a slightly higher retention rate than subscribers.

### Business Insight

Subscription status alone does not significantly improve user retention. Product quality and user experience appear to play a greater role in encouraging users to return.

### Recommendation

- Improve premium feature value.
- Increase subscriber-exclusive benefits.
- Focus on improving overall chatbot experience.

---


# 8. Does response time affect user satisfaction?

### Findings

TherapyBot-v2.5-Turbo recorded:

- Highest average response time
- Highest negative feedback
- Lowest customer satisfaction

### Business Insight

Slower response times are associated with lower customer satisfaction. Improving response speed is likely to enhance the overall user experience.

### Recommendation

- Optimize model inference speed.
- Reduce server latency.
- Improve API performance.

---

# 9. What actions can the company take to improve long-term user retention?

## Key Recommendations

### Improve TherapyBot-v2.5-Turbo

- Reduce response latency.
- Improve conversation quality.
- Minimize technical errors.
- Enhance network reliability.

---

### Increase User Engagement

- Personalized onboarding.
- Daily reminders.
- Conversation continuation prompts.
- Gamification features.
- Achievement badges.

---

### Improve Customer Satisfaction

- Faster responses.
- More accurate AI-generated answers.
- Better personalization.
- Improved emotional understanding.

---

### Increase Subscription Value

- Exclusive premium features.
- Faster response times.
- Priority model access.
- Personalized recommendations.

---

### Continuous Monitoring

Track the following KPIs through a Power BI dashboard:

- Retention Rate
- Churn Rate
- Customer Satisfaction
- Response Time
- Error Rate
- Session Duration
- Subscription Conversion
- Daily Active Users (DAU)
- Monthly Active Users (MAU)

---

# Final Business Conclusion

The analysis indicates that **user retention is primarily influenced by conversation quality, session engagement, response speed, and overall chatbot reliability rather than subscription status alone**. Users who engaged in longer conversations were more likely to return after 30 days, while slower response times, higher error rates, and lower customer satisfaction—particularly with **TherapyBot-v2.5-Turbo**—were associated with poorer user experiences. Additionally, mobile devices demonstrated the highest user engagement, and countries such as Germany and Australia achieved stronger retention rates than India and the United States. These findings suggest that improving chatbot performance, enhancing conversation quality, reducing technical issues, and strengthening user engagement strategies can significantly reduce churn, improve customer satisfaction, and drive long-term business growth.