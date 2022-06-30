# PCOS-Detection-in-Females
Polycystic Ovary Syndrome (PCOS) Polycystic Ovary Syndrome (PCOS) is a health problem that affects women of childbearing age. Women with PCOS have a hormonal imbalance and metabolism problems that may affect their overall health.Women with PCOS produce higher-than-normal amounts of male hormones. This hormone imbalance causes their body to skip menstrual periods and makes it harder for them to get pregnant.
# PCOS Symptoms #
![pcom symptoms](https://user-images.githubusercontent.com/88290919/176607070-e6a93413-f055-4413-ad8c-1b97157f83be.jpeg)

# ABOUT THE DATA #

1. This dataset contains all physical and clinical parameters to determine PCOS and infertility related issues. There are a total of 44 parameters.

2. This data is collected from 10 different hospitals across Kerala, India.

3. The unit used is feet to cm

4. Blood pressure entered as systolic and diastolic separately

5. RBS means Random glucose test

6. Beta-HCG cases are mentioned as Case I and II

7. Blood Group indications: A+ = 11, A- = 12, B+ = 13, B- = 14, O+ =15, O- = 16, AB+ =17, AB- = 18

# DATA PROCESSING #

1. Merging the two files that are sorted into two based on patients with infertility and without infertility

2. Dropping the repeated features

3. Encoding categorical variables (dtype objects)

4. Dealing with missing values

# EXPLORATORY DATA ANALYSIS #

1.  Feature selection based on the correlation factor
2.  Patterns Of Length Of The Menstrual Cycle
3.  Patterns Of BMI
4.  Patterns Of Irregularity In Mensuration
5.  Number of Follicles
6.  Some Miscellaneous EDA

# MODEL BUILDING #

1. Assigning values to features as X and target as y
2. Split test and training sets
3. Fitting a vanilla model as the base Random Forest model
4. Hyperparameter tuning using GridSearch CV
5. Fitting the final model
6. Evaluating the confusion matrix
7. Evaluating the classification report




![the end](https://user-images.githubusercontent.com/88290919/176611199-9fc3dbc3-2321-44ba-9159-f25c509b92c5.jpg)


