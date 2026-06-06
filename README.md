**Analyzing School Infrastructure and Student Enrollment Patterns Using Python**

**Objective:**

The objective of this project is to analyze the basic details of schools dataset using Python to gain insights into:

•	School distribution across states, districts, and villages

•	Student enrollment patterns across different classes

•	Availability of school infrastructure such as classrooms and teachers

•	Relationship between school management, school type, and student strength

•	Geographic analysis of schools using latitude and longitude data

•	Identification of trends and gaps in educational resources

This project aims to use Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, and visualization to support better understanding of the education system and resource allocation.

**Dataset information:**

**Source:** https://indiadataportal.com/

**Location:** https://indiadataportal.com/p/udise/r/moe-udise_basic_details-pl-ot-sib

**Year/Timeline:** Data collected during the period 1701 to 2021

**Domain:** Education

# Business Problem

Educational institutions and government authorities often face challenges in understanding whether schools are adequately distributed and properly equipped to support student populations. Large datasets containing school information are available, but extracting meaningful insights manually is difficult and time-consuming.

**There may be issues such as:**

•	Uneven distribution of schools across regions

•	Insufficient infrastructure in certain schools

•	Imbalance between student enrollment and teacher availability

•	Lack of visibility into school management and resource utilization

•	Difficulty identifying areas that require educational improvements

Without proper analysis, decision-makers may struggle to allocate resources effectively and improve the quality of education.

**Expected Outcome:**

The project is expected to deliver a data-driven analysis of school information using Python techniques. The outcomes include:
•	Cleaned and organized school dataset for analysis

•	Visual insights into school distribution and enrollment trends

•	Identification of regions with inadequate infrastructure or staffing

•	Comparative analysis of school categories and management types

•	Charts and dashboards showing key educational indicators

•	Actionable insights that can support better planning and resource allocation in the education sector

The final project will help stakeholders understand patterns in the education system and make informed decisions based on data analysis.

**Dataset Source:**

The dataset used in this project is a school information dataset containing basic details of schools. It is typically collected from educational department records or public educational data repositories. The dataset includes institutional information related to schools, infrastructure, management, and location details.

**Dataset Size:**

The dataset consists of:

•	Multiple rows representing individual schools

•	Several columns containing school-related attributes

•	Structured tabular data stored in CSV (Comma-Separated Values) format

•	Suitable for data analysis, visualization, and machine learning preprocessing using Python

**Dataset Features**

The dataset contains various attributes related to schools, such as:

**School Identification Details**

•	School name

•	School code

•	District and block information

**Location Information**

•	Village/Town

•	Latitude and longitude

•	State and district

**School Management Details**

•	School category

•	Management type

•	School type

**Infrastructure Information**

•	Number of classrooms

•	Availability of facilities

•	Building status

**Academic Information**

•	Medium of instruction

•	Grades/classes available

•	Student enrollment details

**Human Resources**

•	Number of teachers

•	Staff-related information

These features help in performing exploratory data analysis, identifying educational trends, and evaluating school infrastructure and resource distribution.

**Tools & Technologies**

**Platform**

Google Colab

**Programming Language**

Python

**Libraries Used**

**Data Processing**

NumPy

Pandas

**Visualization**

Matplotlib

Seaborn

Plotly Express

**Text Processing**

re

**Warning Handling**

warnings

**Data Cleaning and Pre-processing**

•	Handle duplicates

•	Handle missing values (impute or drop)

•	Drop Highly Missing Columns

•	Fill Missing Numerical Values

•	Fill Missing Categorical Values

•	Renaming columns improves readability and usability.

•	Data Type Conversion

**Converting object type school code into string:**

•	Converting numeric columns

•	Outlier Treatment

**Data Transformation / Data Wrangling**

•	Total Students Per School

•	Calculating school age

•	Categorizing school size

**Final EDA (Exploratory Data Analysis)**

•	 Dataset Shape After Cleaning

•	Checking Final Missing Values

•	Summary Statistics

**Statistical analysis & Visualizations**

# Measure of Central Tendency (Total Students)
**Values**

Mean: 84.41 students

Median: 67 students

Mode: 30 students

**Interpretation**

The average school has approximately 84 students.

Half of the schools have 67 students or fewer.

The most common enrollment size is 30 students.

Since Mean (84.41) > Median (67) > Mode (30), the distribution is positively skewed.

A large number of schools have low enrollment, while a smaller number of schools have very high enrollment.

**Insight**

This indicates an uneven distribution of students across schools, where many schools operate with small enrollments while a few schools accommodate large student populations.

**Variance and Standard Deviation**

**Values**

Variance: 3,920.13

Standard Deviation: 62.61

**Interpretation - Variance**

Student enrollment varies considerably between schools.

A standard deviation of 62.61 students is relatively high compared to the mean of 84.41 students.

Schools differ significantly in size and capacity.

**Insight**

The education system contains a mix of:

Small schools with very low enrollment

Medium-sized schools

Large schools with high enrollment

This suggests unequal utilization of educational infrastructure.

# Interpretation - Standard Deviation

Many schools are clustered around the average enrollment level.

Several schools fall far from the mean.

The wide spread confirms high variability in student enrollment.

**Numerical Evidence**

Approximate enrollment range for most schools:

84.41 ± 62.61

= 22 to 147 students

**Insight**

Most schools are expected to have enrollment within this range, while schools outside this range may require special attention for resource planning.

**Skewness and Kurtosis**

**Values**

Skewness: 0.855

Kurtosis: -0.178

**Interpretation**

**Skewness**

Positive value indicates a right-skewed distribution.

A few schools have exceptionally high student counts.

**Kurtosis**

Slightly negative kurtosis indicates a flatter distribution than a normal distribution.

Extreme values exist but are not excessively concentrated.

**Insight**

The distribution is moderately skewed and contains some large schools that significantly influence overall averages.

**Visualizations**

**1. Univariate Analysis:**

	Distribution of School Age

	Count of School types

	Boxplot – Student Teacher Ratio

**2. Bivariate Analysis**

	Scatterplot – Teachers vs Students

	Barplot – Average Students by School Type

	Correlation Heatmap

**3. Multivariate Analysis**

	 Pairplot

	Pivot Table Analysis

	 Grouped Barplot

**Documentation, Insights & Presentation**

**Summary:**

The school dataset contains over 1.14 million school records with information related to:

	Student enrolment

	Teacher availability 

	Infrastructure 

	School categories 

	Geographic locations 

	Educational levels 

**After data cleaning:**

	Most missing values were successfully handled.

	The dataset became highly reliable for analysis.

	Only minor issues remained in the Student-Teacher Ratio due to division by zero. 

	**The analysis revealed major patterns in:**

	Student distribution 

	Teacher allocation 

	School infrastructure 

	Rural vs urban educational differences 

	Enrollment trends across school categories 

The dataset clearly shows that educational resources are not evenly distributed across schools.

**Key Insights:**

	Student Enrollment is Highly Uneven which indicates imbalance in school distribution and infrastructure utilization.

	Student-Teacher Ratio Varies Significantly where some schools have very high Student-Teacher Ratio and few schools even reported students without teachers.

	Enrollment decreases from primary classes to higher secondary levels which may lead to 

• Student dropouts 

• Migration 

• Lack of higher secondary facilities 

• Economic challenges 

	Urban schools generally accommodate more students than rural schools; hence the Urban educational infrastructure experiences greater pressure and overcrowding.

	Infrastructure modernization and maintenance may become important policy concerns since many schools are several decades old.

**Types of Analysis:**

**1. Descriptive Analysis:**

It summarizes the historical data using:

•	Mean 

•	Median 

•	Standard deviation 

•	Charts and graphs

Which helps to understand the current educational landscape.

**Performed in This Project**

•	Distribution of students 

•	Average teacher count

•	School age analysis 

•	School type counts 

•	Enrollment distribution

**2. Diagnostic Analysis:**

Diagnostic Analysis is used to identify the reasons behind trends and patterns. This helped to identify the root causes of educational inefficiencies.

**Performed in This Project**

•	Correlation between students and teachers 

•	Urban vs rural enrollment comparison 

•	Student-Teacher Ratio analysis 

•	Outlier identification

**3. Predictive Analysis:**

Predictive Analysis is used to find the historical data to predict future outcomes. This analysis helped to find the Supports of the future educational planning and budgeting.

**Possible Future Applications**

Using this dataset, models can predict:

•	Future enrollment growth 

•	Teacher requirements 

•	School infrastructure demand 

•	Dropout risk

**4. Prescriptive Analysis:**

Prescriptive Analysis is used to provide the actionable recommendations. This helped to Support evidence-based policy decisions.

**Based on this dataset**

Authorities can:

•	Allocate more teachers to understaffed schools 

•	Improve urban infrastructure 

•	Expand overcrowded schools 

•	Focus on higher-secondary retention programs

**Recommendations / Decision Support**

1.   Schools with high Student-Teacher Ratios should receive additional teachers for
    
      •	Better learning quality
     
      •	Reduced teacher workload
     
      •	Improved student performance
     
4.   Urban and overcrowded schools require
    
      •	More classrooms
     
      •	Better facilities
     
      •	Additional educational resources, for improved classroom management and reduced overcrowding.
     
7.   Introducing the followings to reduce the dropout rates.
   
      •	Scholarship programs
     
      •	Career guidance
     
      •	Transport support
     
      •	Awareness initiatives
     
9.   Schools showing infinite Student-Teacher Ratio need immediate investigation by conducting audits and staffing verification, which can improve the operational efficiency.
    
11.   Since latitude and longitude are available, governments can perform the below points for better educational accessibility.
12.   
      •	Map underserved regions
      
      •	Identify school density gaps
      
      •	Plan new school locations strategically
   
# Final conclusion:

This project analyzed 1,140,993 cleaned school records containing information on student enrollment, teachers, infrastructure, school types, and geographic locations.

**Major Findings**

✅ Average school enrollment is **84** students

✅ Half of the schools have **67** students or fewer

✅ The most common school size is **30** students

✅ Enrollment variability is high (Standard Deviation = **62.61**)

✅ Student distribution is positively skewed (Skewness = **0.855**)

✅ Teacher and classroom availability increase with student enrollment

✅ Urban schools generally accommodate more students than rural schools

✅ Several schools show unusually high student-teacher ratios, indicating staffing shortages

**Overall Conclusion**

The analysis reveals that India's school ecosystem experiences:

Uneven student distribution

Teacher allocation gaps

Urban-rural enrollment disparities

Infrastructure utilization differences

These findings can support educational authorities in making data-driven decisions regarding teacher deployment, infrastructure development, school expansion, and resource allocation to improve educational quality and accessibility.
