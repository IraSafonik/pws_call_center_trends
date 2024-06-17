# PWC - Call Centre Trends Dashboard
<img width="752" alt="Знімок екрана 2024-06-17 о 18 30 28" src="https://github.com/IraSafonik/pws_forage/assets/32171563/35dcdad7-e893-47d6-87e2-731fd9936964">

## 💡 Project Overview

This project involves creating an interactive Power BI dashboard for visualizing key performance indicators (KPIs) and metrics related to call center performance for PhoneNow. The primary objective is to provide a transparent and insightful overview of long-term trends in customer and agent behavior. This dashboard will help the Call Centre Manager, Claire, in her discussions with management by highlighting crucial aspects such as call volumes, response times, customer satisfaction, and agent performance.

## ☝️ Project Goals

- **Visualize Key Metrics**: Provide a clear and comprehensive view of call center metrics including total calls answered/abandoned, speed of answer, call durations, and overall customer satisfaction.
- **Trend Analysis**: Identify and visualize long-term trends in both customer and agent behavior to facilitate data-driven decision-making.
- **Agent Performance**: Highlight agent performance metrics to identify top performers and areas needing improvement.

## 💼 Tasks

1. Collect and preprocess call center data.
2. Identify and define relevant KPIs.
3. Design and develop a Power BI dashboard to visualize these KPIs.
4. Ensure the dashboard is user-friendly and provides actionable insights.
5. Collaborate with the Call Centre Manager to refine and adjust the dashboard as needed.

## 🛠️ Tools and Technologies

- **Power BI**: For data visualization and dashboard creation.
- **Microsoft Excel**: For initial data collection and preprocessing.
- **Python (optional)**: For advanced data preprocessing if needed.
- **Podcasts and Articles**: For enhancing understanding of data visualization and digital upskilling.

## 🗂️ Data Sources

### Call Centre Dataset

| Column                    | Description                                                       |
|---------------------------|-------------------------------------------------------------------|
| Call Id                   | Unique identifier for each call                                   |
| Agent                     | Name or ID of the agent handling the call                         |
| Date                      | Date of the call                                                  |
| Time                      | Time of the call                                                  |
| Topic                     | Topic or reason for the call                                      |
| Answered (Y/N)            | Whether the call was answered (Yes/No)                            |
| Resolved                  | Whether the issue was resolved during the call                    |
| Speed of answer in seconds| Time taken to answer the call, measured in seconds                |
| AvgTalkDuration           | Average duration of the call in seconds                           |
| Satisfaction rating       | Customer satisfaction rating for the call                         |

## 💻 Process and Steps

### 1️⃣ Step 1: Data Collection and Preprocessing
- Collect all relevant data from the Call Centre Manager.
- Clean and preprocess the data using Power Query to ensure it is ready for analysis.

### 2️⃣ Step 2: KPI Identification and Definition
- Work with the Call Centre Manager to identify the most relevant KPIs.
- Define how each KPI will be calculated and visualized in the dashboard.

### 3️⃣ Step 3: Dashboard Design and Development
- Design the layout of the dashboard, focusing on clarity and ease of use.
- Develop the dashboard in Power BI, ensuring it accurately reflects the identified KPIs and metrics.
- Create interactive elements such as filters and drill-downs to allow for detailed analysis.

### 4️⃣ Step 4: Review and Refinement
- Present the initial version of the dashboard to the Call Centre Manager for feedback.
- Make necessary adjustments based on the feedback to ensure the dashboard meets all requirements.

### 5️⃣ Step 5: Finalization and Delivery
- Finalize the dashboard and ensure it is fully functional.
- Provide the Call Centre Manager with the necessary training to use and interpret the dashboard.

## Dashboard👇
![Screenshot_8](https://github.com/IraSafonik/pws_forage/assets/32171563/3f935d86-2e94-430a-9bee-85fae2b68e5c)

## 🌟Insights:

### Overall Call Center Statistics
- The average satisfaction rating for the period is 3.40 out of 5.
- 81.08% of calls were answered, while 18.92% were unanswered.
- 72.92% of calls were resolved successfully, while 27.08% were unresolved.
- The average speed of answering a call was 67.52 seconds.

### Monthly Call Trends
- The number of calls was relatively consistent across the three months (January, February, March), ranging from 311 to 318 calls per month.
- The total number of calls for the three-month period was 5,000.

### Agent Performance
- There are 8 agents handling calls in the call center.
- Jim handled the highest number of calls (536), followed by Dan (523), and Becky (517).
- Martha had the highest average satisfaction rating (3.47), followed by Dan (3.45), and Diane (3.41).
- Joe had the slowest average speed of answering calls (70.99 seconds), while Becky was the fastest (65.33 seconds).

### Call Topics
- The most common call topic was related to Streaming, with 1022 calls (around 18.5% of total calls).
- Technical Support was the second most common topic, with 1019 calls (around 18.2% of total calls).
- The least common topic was related to Contract, with 976 calls (around 6.6% of total calls).

### Call Resolution
- For most call topics, the majority of calls were resolved successfully.
- The highest resolution rate was for the Streaming topic, with around 73% of calls resolved.
- The lowest resolution rate was for the Contract topic, with around 63% of calls resolved.

## 🚀Recommendations:

### 1. Improve Call Answer Rate 
(18.92% of calls were unanswered).
- Increase staffing during peak call volumes.
- Optimize call queuing and distribution system.

### 2. Enhance Agent Training 
(Agents with lower satisfaction ratings (e.g., Joe: 3.33, Greg: 3.40). Call topics with lower resolution rates (e.g., Contract: ~63%)).
- Provide targeted training for underperforming agents.
- Encourage knowledge sharing among high and low performers.
- Develop training programs for specific call topics.

### 3. Optimize Call Handling Efficiency 
(Joe had the slowest average speed of answering calls (70.99 seconds)).
- Analyze and address bottlenecks in call handling process.
- Implement call prioritization strategies.
- Explore self-service options for routine inquiries.

### 4. Improve Call Resolution Rate 
(27.08% of calls were unresolved).
- Investigate root causes of low resolution rates.
- Enhance agent knowledge and resources for complex inquiries.
- Implement call escalation process for unresolved issues.

### 5. Conduct Regular Performance Reviews
- Implement regular performance reviews with constructive feedback.
- Recognize and reward top-performing agents.
- Gather feedback from agents for process improvements.

### 6. Analyze Call Trends and Patterns
- Continuously monitor call trends and patterns.
- Adjust staffing, training, and resources based on evolving call topics.
- Leverage data-driven insights for proactive improvements.

## 🌿 Results and Conclusion

The final Power BI dashboard provides a comprehensive and insightful view of the call center's performance. Key trends and metrics are clearly visualized, allowing the Call Centre Manager to make informed decisions and effectively communicate with management. This project not only demonstrates the power of data visualization but also highlights the importance of digital upskilling in today's fast-changing work environment.
