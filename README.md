# ML-Predicting_Income_Category

## Dataset Name: Adult Census Dataset
Link :https://archive.ics.uci.edu/dataset/2/adult

Description:
"Extraction was done by Barry Becker from the 1994 Census database.  A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))

Prediction task is to determine whether a person makes over 50K a year."

The features are workclass: This indicates the employment sector of the individual. Categories include Private, Self-emp-not-inc, State-gov, Federal-gov, and others.

fnlwgt         : Final weight, a weighting factor that estimates the number of people the census data represents.
education      : The highest level of education an individual has completed (e.g., Bachelors, HS-grad, 11th).
education-num  : The number of years of education corresponding to the highest level of education.
marital-status : The marital status of the individual (e.g., Never-married, Married-civ-spouse, Divorced).
occupation     : The occupation of the individual (e.g., Adm-clerical, Exec-managerial, Handlers-cleaners).
relationship   : Describes the individual's family relationship (e.g., Husband, Wife, Not-in-family).
race           : The race of the individual (e.g., White, Black, Asian-Pac-Islander, Amer-Indian-Eskimo).
sex            : The gender of the individual (e.g., Male, Female).
capital-gain   : Capital gains recorded (income from investments or assets).
capital-loss   : Capital loss recorded (loss from investments or assets).
hours-per-week : The number of hours the individual works per week.
native-country : The country of origin (e.g., United-States, Mexico, Cuba).
income         : This is the target variable, indicating whether the individual earns <=50K or >50K annually.

## Histograms for numerical features
<img width="811" alt="Screenshot 2025-02-08 at 10 29 02 PM" src="https://github.com/user-attachments/assets/af3be8ef-23f3-4f25-bfc1-6c1ee94db0af" />
## Density Plot
<img width="811" alt="Screenshot 2025-02-08 at 10 30 12 PM" src="https://github.com/user-attachments/assets/8b2db8a1-2858-478f-9e5d-3603026e476f" />
## Income Category Distribution
<img width="811" alt="Screenshot 2025-02-08 at 10 30 47 PM" src="https://github.com/user-attachments/assets/dda85e8a-42e5-4094-b8ff-c2b95b9b5667" />
## Heat Map for Features
<img width="811" alt="Screenshot 2025-02-08 at 10 31 10 PM" src="https://github.com/user-attachments/assets/1d38c71c-7656-46ea-9195-85a760db79fe" />
## Comparison of Models: Accuracy Score
<img width="811" alt="Screenshot 2025-02-08 at 10 31 56 PM" src="https://github.com/user-attachments/assets/24151cc4-5e24-4d32-bd5c-876a18841d96" />
## Comparison of Models: Accuracy Score after GridSearchCV
<img width="811" alt="Screenshot 2025-02-08 at 10 32 18 PM" src="https://github.com/user-attachments/assets/ff64200b-43c2-4054-8b4f-24ae2e1954f9" />







