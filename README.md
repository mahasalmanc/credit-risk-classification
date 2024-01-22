# Credit Risk Classification Challenge

Overview of the analysis:
The purpose of this analysis was to use supervised machine learning to determine whether or not an individual is holding a healthy or high-risk loan based on a set of various features.
The financial information being considered includes the size of the loan, the interest rate, the individual's income, number of accounts, and total debt. 
From the data available, majority of loans were considered healthy, with a value count of 75036. High-risk loans made up a value count of 2500. 

To analyze the data, the dataset was divided into training and testing sets. Then a logistic regression module was used to ultimately compare predicted scores with the test scores.

Results:
We found that the accuracy rate for the data was 95%. Precision and recall scores were high for both healthy and high-risk loans, but close to 100% for healthy.

Summary:
High-risk loans had lower rates of precision and recall, and I would argue that those are more important to have accurate. If an individual is flagged when they in fact are holding a healthy loan, that is a risk for their credit score. 
