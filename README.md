# neural-network-challenge-1
Repository for Module 18 Homework Challenge

**Code file**: student_loans_with_deep_learning.ipynb <br>
**Model**: student_loans.keras

Briefly answer the following questions in the space provided:

1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

>The data needed should include:
>
>- Student demographic information (e.g., age, income, credit score, academic performance)
>- Details about available student loan options (e.g., interest rates, repayment terms, eligibility criteria)
>- Student's financial needs and goals (e.g., desired loan amount, preferred repayment timeline)
>- Historical data on student loan performance and outcomes (e.g., default rates, employment rates after graduation)
>
>This data is relevant as it helps the system understand the student's financial profile, match them with suitable loan options, and predict the likelihood of successful loan repayment.

2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

>The system would likely use a combination of content-based filtering and collaborative filtering:
>- Content-based filtering: Analyzes the student's profile and loan characteristics to recommend loans that match the student's needs.
>- Collaborative filtering: Considers experiences and preferences of similar students for personalized recommendations.
>
>This approach is suitable as it leverages both individual and collective characteristics for accurate recommendations.

3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.

>- Ensuring data privacy and security: Handling sensitive financial and personal information requires robust measures.
>- Addressing the dynamic nature of student loan options: Regular updates are needed to provide accurate recommendations as loan options and regulations change.
>- Accounting for individual circumstances and preferences: Unique financial situations and goals might not be easily captured, requiring flexibility in the system.
