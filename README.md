**Problem Statement:**

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. A typical lead conversion process can be represented using the following funnel:

![image](https://github.com/Sonalitt/Lead-Scoring-Case-Study/assets/152708978/7074933d-6339-4a25-8ec7-d248b103f285)

**Goals of the Case Study:**

Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

**Steps Followed:**

Data Reading
Data Cleaning
Exploratory Data Analysis (EDA)
Creation of Dummy Variables
Splitting Data into Train and Test Sets
Model Building
Prediction Making
Model Evaluation
ROC Curve Analysis
Prediction on Test Set
Precision-Recall Analysis

**Conclusion:**

1. Prioritize features with positive coefficients to refine targeted marketing tactics effectively.
2. Formulate strategies to attract top-quality leads from high-performing lead sources.
3. Customized messaging to engage working professionals more effectively.
4. Optimize communication channels based on their impact on lead engagement.
5. Allocate more budget to advertising on the Welingak Website to maximize visibility and impact.
6. Implement incentives or discounts for successful lead referrals to encourage further referrals.

**Files Uploaded/Used:**

1. Leads_Scoring_Case_Study.ipynb : Python file includes coding and data analysis
2. Assignment Subjective Questions.pdf
3. Lead Scoring Case Study - Presentation.pdf : Includes Presentation
4. Lead Scoring Case Study - Summary.pdf : Summary of the case study
5. Leads.csv : Dataset
6. Leads Data Dictionary.xlsx : Data Dictionary
