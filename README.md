# CUSTOMER CHURN ANALYSIS
<p align="justify">
  This project uses Python with Google Colab to create a model of machine learning to predict customer churn. I completed this project while participating in Fresh Graduate Academy at <a href="https://www.linkedin.com/in/indahsh/details/education/968984033/multiple-media-viewer/?profileId=ACoAADQ0K_IBB-BflJ1wnBkU3Z47qF6xVW9xyvI&treasuryMediaId=1714306461924">Digital Talent Scholarship</a>.
</p>

## 1. BUSINESS UNDERSTANDING
### 1.1. Description
<p align="justify">
  Telecommunication companies are increasing because internet use in communication is expanding, which can result in competition between providers. Customers can choose the appropriate provider and switch from the previous provider, defined as customer churn. 
</p>

<p align="justify">
  Switching providers by customers can result in reduced revenue for telecommunications companies. Using existing datasets is expected to produce customer churn predictions so companies can create business strategies for customers to survive.
</p>

### 1.2. Objectives
The objectives to be achieved in this project are as follows the following.
1. <p align="justify">Identify insights through exploratory data analysis.</p>
2. <p align="justify">Obtain the best performance by comparing different models.</p>
3. <p align="justify">Implement an effective customer retention strategy based on data analysis and churn rate prediction results.</p>

## 2. DATA UNDERSTANDING
- <p align="justify">The data used is about customer churn, spanning from April 15, 2020, to June 8, 2020, and was obtained from <a href="https://www.kaggle.com/c/customer-churn-prediction-2020/overview">Kaggle</a>.</p>
- <p align="justify">The data consists of 4,250 rows and 20 columns containing cellular variables.</p>

| No. | Column | Description | Data Type |
| --- | --- | --- | --- |
| 1 | state | 2-letter code of the US state of customer residence | String |
| 2 | account_length | Number of months the customer has been with the current telco provider | Numerical |
| 3 | area_code | Customer's telephone area code | String |
| 4 | international_plan | The customer has an international plan (yes/no) | Boolean |
| 5 | voice_mail_plan | The customer has a voice mail plan (yes/no) | Boolean |
| 6 | number_vmail_messages | Number of voice-mail messages | Numerical |
| 7 | total_day_minutes | Total minutes of day calls | Numerical |
| 8 | total_day_calls | Total number of day calls | Numerical |
| 9 | total_day_charge | Total charge of day calls | Numerical |
| 10 | total_eve_minutes | Total minutes of evening calls | Numerical |
| 11 | total_eve_calls | Total number of evening calls | Numerical |
| 12 | total_eve_charge | Total charge of evening calls | Numerical |
| 13 | total_night_minutes | Total minutes of night calls | Numerical |
| 14 | total_night_calls | Total number of night calls | Numerical |
| 15 | total_night_charge | Total charge of night calls | Numerical |
| 16 | total_intl_minutes | Total minutes of international calls | Numerical |
| 17 | total_intl_calls | Total number of international calls | Numerical |
| 18 | total_intl_charge | Total charge of international calls | Numerical |
| 19 | number_customer_service_calls | Number of calls to customer service | Numerical |
| 20 | churn | Customers make service changes (yes/no) | Boolean |

## 3. CONCLUSION
<p align="justify">
  The conclusions that can be drawn based on the above analysis are as follows.
</p>

- <p align="justify">Only 14% (98 customers) of the total customers have churned, indicating a relatively low churn rate.</p>
- <p align="justify">Customers with area code 415 have the highest churn rate, suggesting a regional pattern in customer retention issues.</p>
- <p align="justify">Most customers who churned don't have an international plan, indicating that this service isn't a significant factor in retention.</p>
- <p align="justify">Most customers who churned don't have a voice mail plan, indicating that this service isn't a significant factor in retention.</p>
- <p align="justify">There is a positive correlation between the total minutes of day calls and churn, implying that customers with higher usage may have different needs or face issues not addressed by the current service.</p>
- <p align="justify">Total minutes of day calls affect customer churn; the higher the total day minutes, the higher the customer churn.</p>
- <p align="justify">The Random Forest model outperforms the Support Vector Machine (SVM) model in predicting customer churn, making it a more reliable tool for this analysis.</p>
- <p align="justify">Based on model predictions, 8% (49 customers) are at risk of churning, highlighting a critical group for targeted retention efforts.</p>

## 4. RECOMMENDATION
<p align="justify">
  Based on the conclusion, recommendations for the company can be given as follows.
</p>

- <p align="justify">Since customers without international and voice mail plans show higher churn rates, investigate whether these plans are adequately marketed or if there are barriers to uptake. Consider offering trials, discounts, or bundling these services with other popular plans.</p>
- <p align="justify">The positive correlation between high total day call minutes and churn suggests that heavy users might have unmet needs or experience service quality issues. Engage with these customers to gather feedback and explore whether specific problems, such as call quality or cost concerns, need addressing.</p>
- <p align="justify">With higher churn rates observed among customers with account lengths of 101-150 months, developing engagement strategies for this group is crucial. Implement loyalty programs, offer personalized rewards, or conduct check-ins to strengthen their relationship with the company during this critical period.</p>
