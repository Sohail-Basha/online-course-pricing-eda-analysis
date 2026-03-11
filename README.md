# Online Course Pricing EDA Analysis

## Project Overview
This project analyzes online course data to understand the relationship between course pricing, ratings, and learner engagement.  
Using exploratory data analysis (EDA) and statistical hypothesis testing, the project evaluates whether paid courses perform better than free courses in terms of ratings and review counts.

The dataset was collected through web scraping from the Class Central website and contains information about courses, platforms, ratings, reviews, and pricing type.

## Objectives

- Analyze distribution of course ratings and reviews
- Compare ratings between free and paid courses
- Study learner engagement using review counts
- Analyze rating trends across different platforms
- Examine the relationship between ratings and reviews
- Use hypothesis testing to determine statistical significance

## Dataset

The dataset contains **405 online courses** with the following features:

| Feature | Description |
|------|-------------|
| Course Name | Name of the course |
| Platform | Platform offering the course |
| Rating | Average course rating (0–5) |
| Reviews | Number of learner reviews |
| Course Type | Free or Paid |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Workflow

### 1 Data Collection
Course data was collected using web scraping techniques from the Class Central platform.

### 2 Data Cleaning
- Standardized course pricing labels
- Converted ratings and reviews into numeric format
- Cleaned inconsistent labels

### 3 Exploratory Data Analysis

#### Univariate Analysis
- Rating distribution
- Review distribution
- Course type distribution
- Platform-wise course distribution

#### Bivariate Analysis
- Reviews vs Ratings
- Average Rating: Free vs Paid Courses
- Average Rating by Platform

#### Multivariate Analysis
- Reviews vs Rating by Course Type

## Hypothesis Testing

### Hypothesis 1  
Do Paid Courses Have Different Ratings than Free Courses?

**Null Hypothesis (H₀)**  
There is no significant difference in ratings between free and paid courses.

**Alternative Hypothesis (H₁)**  
There is a significant difference in ratings between free and paid courses.

Test Used: **Independent Two Sample t-test**

Result:
# Online Course Pricing EDA Analysis

## Project Overview
This project analyzes online course data to understand the relationship between course pricing, ratings, and learner engagement.  
Using exploratory data analysis (EDA) and statistical hypothesis testing, the project evaluates whether paid courses perform better than free courses in terms of ratings and review counts.

The dataset was collected through web scraping from the Class Central website and contains information about courses, platforms, ratings, reviews, and pricing type.

## Objectives

- Analyze distribution of course ratings and reviews
- Compare ratings between free and paid courses
- Study learner engagement using review counts
- Analyze rating trends across different platforms
- Examine the relationship between ratings and reviews
- Use hypothesis testing to determine statistical significance

## Dataset

The dataset contains **405 online courses** with the following features:

| Feature | Description |
|------|-------------|
| Course Name | Name of the course |
| Platform | Platform offering the course |
| Rating | Average course rating (0–5) |
| Reviews | Number of learner reviews |
| Course Type | Free or Paid |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Workflow

### 1 Data Collection
Course data was collected using web scraping techniques from the Class Central platform.

### 2 Data Cleaning
- Standardized course pricing labels
- Converted ratings and reviews into numeric format
- Cleaned inconsistent labels

### 3 Exploratory Data Analysis

#### Univariate Analysis
- Rating distribution
- Review distribution
- Course type distribution
- Platform-wise course distribution

#### Bivariate Analysis
- Reviews vs Ratings
- Average Rating: Free vs Paid Courses
- Average Rating by Platform

#### Multivariate Analysis
- Reviews vs Rating by Course Type

## Hypothesis Testing

### Hypothesis 1  
Do Paid Courses Have Different Ratings than Free Courses?

**Null Hypothesis (H₀)**  
There is no significant difference in ratings between free and paid courses.

**Alternative Hypothesis (H₁)**  
There is a significant difference in ratings between free and paid courses.

Test Used: **Independent Two Sample t-test**

Result:
t-statistic = 5.73
p-value = 2.10e-08

Since **p < 0.05**, the null hypothesis is rejected.

Conclusion:  
Paid courses show significantly different ratings compared to free courses.

### Hypothesis 2  
Do Paid Courses Receive More Reviews?

Result:
t-statistic = 0.054
p-value = 0.277

Since **p > 0.05**, we fail to reject the null hypothesis.

Conclusion:  
There is no statistically significant difference in review counts between free and paid courses.

## Key Insights

- Paid courses have higher average ratings compared to free courses
- Review distribution is highly skewed
- A small number of courses receive very high engagement
- Higher-rated courses tend to attract more reviews
- Some platforms consistently show higher average ratings
