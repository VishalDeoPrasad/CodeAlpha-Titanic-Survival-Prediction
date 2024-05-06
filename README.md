# TITANIC-SURVIVAL-PREDICTION
Predict passenger survival on the Titanic using features like age,gender, and ticket class.
# Titanic Dataset Analysis

## Project Overview:
The Titanic dataset analysis aims to explore and understand the factors that influenced the survival rates of passengers aboard the RMS Titanic during its tragic sinking. This project involves thorough data exploration, cleaning, and analysis to gain insights into the demographics of the passengers and the variables affecting their survival.

## Steps Followed:
1. **Data Acquisition**: Acquired the Titanic dataset in CSV format, containing information about passengers such as their age, sex, ticket class, fare, and more.

2. **Data Exploration**: Explored the dataset to understand its structure, including the available columns, data types, and basic statistics.

3. **Data Cleaning**:
   - Handled Missing Values: Checked for missing values in each column and decided on appropriate strategies for handling them. For example, filled missing age values with the median age, and embarked port with the most common port.
   - Outlier Detection: Identified and handled outliers, if any, in numerical variables like age and fare.
   - Data Type Conversion: Converted data types as necessary, such as converting categorical variables to appropriate data types.

4. **Univariate Analysis**:
   - Conducted univariate analysis for each variable in the dataset:
     - Calculated descriptive statistics (mean, median, mode, standard deviation, min, max).
     - Created visualizations (histograms, bar charts, pie charts) to explore the distribution and characteristics of each variable.

5. **Bivariate Analysis**:
   - Analyzed the relationship between survival and various factors including:
     - Passenger class (Pclass)
     - Sex
     - Age
     - Number of siblings/spouses (SibSp)
     - Number of parents/children (Parch)
     - Fare
     - Embarked port
   - Calculated survival rates for different categories of each factor and visualized the relationships using appropriate charts (bar charts, stacked bar charts).

## Univariate Analysis:

### 1. Survival:
- Calculated the percentage of survivors and non-survivors.
- Visualized the counts of survivors and non-survivors using a bar chart.

### 2. Passenger Class (Pclass):
- Determined the frequency of passengers in each ticket class (1st, 2nd, 3rd).
- Visualized the counts of passengers in each ticket class using a bar chart.

### 3. Sex:
- Examined the frequency of male and female passengers.
- Visualized the proportion of male and female passengers using a pie chart.

### 4. Age:
- Calculated descriptive statistics such as mean, median, mode, standard deviation, min, and max age.
- Visualized the distribution of passenger ages using a histogram.

### 5. Number of Siblings/Spouses (SibSp):
- Explored the frequency of passengers with different numbers of siblings/spouses.
- Visualized the counts of passengers with different numbers of siblings/spouses using a bar chart.

### 6. Number of Parents/Children (Parch):
- Analyzed the frequency of passengers with different numbers of parents/children onboard.
- Visualized the counts of passengers with different numbers of parents/children using a bar chart.

### 7. Fare:
- Calculated descriptive statistics for passenger fares.
- Visualized the distribution of passenger fares using a histogram or box plot.

### 8. Cabin:
- Determined the number of unique cabin numbers.
- Checked for missing values and calculated the percentage of missing values in the Cabin column.

### 9. Embarked Port:
- Explored the frequency of passengers embarking from each port (Cherbourg, Queenstown, Southampton).
- Visualized the counts of passengers embarking from each port using a bar chart.


## Bivariate Analysis:

### 1. Survival vs. Passenger Class (Pclass):
- Passengers in higher classes had higher survival rates compared to those in lower classes.
- Visualized the survival rates for each passenger class using a bar chart.

### 2. Survival vs. Sex:
- Female passengers had a significantly higher survival rate compared to male passengers.
- Visualized the survival rates for each gender using a bar chart.

### 3. Survival vs. Age Group:
- Analyzed the relationship between survival and age groups.
- Found that children and elderly passengers had higher survival rates compared to adults.
- Visualized the survival rates for different age groups using a bar chart or line plot.

### 4. Survival vs. Number of Siblings/Spouses (SibSp):
- Explored how survival rates varied based on the number of siblings/spouses a passenger had onboard.
- Visualized the survival rates for different numbers of siblings/spouses using a bar chart.

### 5. Survival vs. Number of Parents/Children (Parch):
- Investigated the impact of the number of parents/children a passenger had onboard on their survival.
- Visualized the survival rates for different numbers of parents/children using a bar chart.

### 6. Survival vs. Fare:
- Examined the relationship between survival and fare paid by passengers.
- Found that passengers who paid higher fares had higher survival rates.
- Visualized the survival rates for different fare ranges using a bar chart or line plot.

### 7. Survival vs. Embarked Port:
- Analyzed how survival rates varied based on the port of embarkation.
- Found differences in survival rates among passengers embarking from different ports.
- Visualized the survival rates for each embarked port using a bar chart.


## Results:
- **Survival Rate by Passenger Class**: Passengers in higher classes had higher survival rates compared to those in lower classes.
- **Survival Rate by Sex**: Female passengers had a significantly higher survival rate compared to male passengers.
- **Survival Rate by Age Group**: Children and elderly passengers had higher survival rates compared to adults.
- **Survival Rate by Number of Siblings/Spouses and Number of Parents/Children**: Passengers with fewer family members onboard had higher survival rates.
- **Survival Rate by Fare Range**: Passengers who paid higher fares had higher survival rates.
- **Survival Rate by Embarked Port**: Passengers embarking from certain ports had higher survival rates compared to others.

Through thorough data exploration, cleaning, and analysis, this project provides valuable insights into the factors influencing survival rates among Titanic passengers.
