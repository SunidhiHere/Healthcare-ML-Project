# Healthcare ML Project
<img width="1408" height="768" alt="Gemini_Generated_Image_xwpuwyxwpuwyxwpu" src="https://github.com/user-attachments/assets/8702c8c2-8440-4f4a-9190-f60b527ce7cc" />


## Introduction
Modern healthcare facilities operate in high-pressure environments where efficient resource allocation directly impacts both patient outcomes and financial sustainability. Patient flow—the movement of patients through a healthcare facility from initial arrival to final discharge—is highly dynamic.
Traditionally, hospitals manage bed capacity and staffing retroactively, responding to shortages only after a patient has been fully evaluated and processed by medical staff. This lag in decision-making creates severe operational bottlenecks. In order to optimize hospital logistics, clinical teams need a way to predict a patient's ultimate disposition (whether they will require an inpatient hospital bed or be discharged after outpatient care) the exact moment they walk through the door.
The primary objective of this data science project is to build an intelligent, data-driven framework that predicts hospital admission requirements upon patient intake. By leveraging machine learning, this system aims to give hospital administrators hours of advance notice regarding incoming bed demand, thereby stabilizing resource management and minimizing operational delays.
By transforming reactive operational data into proactive clinical foresight, this project demonstrates how machine learning can bridge the gap between hospital administration efficiency and high-quality patient care.

## About Dataset
*This dataset contains operational, demographic, and clinical workflow tracking records for $9,216$ patients admitted or processed between January 2024 and September 2024. It is designed to mirror real-world hospital administration challenges, providing a rich blend of temporal, categorical, and numerical features.
*This dataset contains features including a unique Patient Id, the exact Patient Admission Date and Time of arrival, the processing staff member in Merged, demographic details for Patient Gender, Age, and Race, the assigned Department Referral, the final clinical outcome in Patient Admission Flag, a post-visit Patient Satisfaction Score scaled from $0$ to $10$, and the total Patient Waittime in minutes.

## Buisiness Question
* Business Question: How do patient arrival patterns (by hour of the day or day of the week) impact Patient Waittime, and how can we optimize hospital staffing during peak hours?
* Project Value: Helps hospital administration predict high-traffic periods, ensuring enough doctors/nurses are scheduled to minimize long delays.

## EDA(Elaborative Data Analysis) and observation
* This dataset contains 9,216 patient records across 11 columns, consisting of 8 categorical variables, 2 integer variables, and 1 floating-point variable. While most of the columns are fully populated, there are significant data completeness issues with Department Referral having only 3,816 non-null entries and Patient Satisfaction Score missing nearly 73% of its records with only 2,517 entries. Looking at the numerical metrics, the patient population ranges from 1 to 79 years old with an average age of roughly 40, while patient wait times span between 10 and 60 minutes with an overall average of 35.2 minutes. Finally, for the portion of patients who did leave feedback, the recorded satisfaction scores range from 0 to 10, yielding a mediocre average rating of approximately 5 out of 10.
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis

## Feature Engineering

## Algorithms Used

## Model Evaluation and Accuracy

## Conclusion

## Links and References
