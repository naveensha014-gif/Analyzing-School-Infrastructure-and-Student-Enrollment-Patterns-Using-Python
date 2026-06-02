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
School Identification Details
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

**Data Cleaning and Pre-processing**
•	Handle duplicates
•	Handle missing values (impute or drop)
•	Drop Highly Missing Columns
•	Fill Missing Numerical Values
•	Fill Missing Categorical Values
•	Renaming columns improves readability and usability.
•	Data Type Conversion
•	Converting object type school code into string:
•	Converting numeric columns:
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
**•	Measure of Central Tendency**
**Interpretation:**
	Most schools have lower student enrollment.
	Few schools have very high student counts.
	The distribution is positively skewed.
	Many schools are small or rural.
	A few schools are overcrowded.
	Educational authorities may need better student distribution and infrastructure planning.
	Mean is greater than median due to large schools pulling the average upward.
**Variance and Standard Deviation**
**Interpretation:**
	High standard deviation indicates wide variation in student enrollment.
	Schools differ significantly in size.
	Some schools operate with very small enrollments while others are heavily populated.
	This variability can affect:
	Teacher allocation
	Classroom requirements
	Government funding
	Infrastructure planning
	Large variation suggests uneven educational resource distribution.
**Skewness and Kurtosis**
**Interpretation:**
	Presence of many outliers.
	Positive skewness indicates long right tail.
	High kurtosis suggests extreme values exist.
	Some schools are exceptionally large compared to average schools.
	This may indicate:
	Urban concentration
	Popular government institutions
	Resource imbalance
	Authorities may investigate whether overcrowded schools require expansion.
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
	The analysis revealed major patterns in:
	Student distribution 
	Teacher allocation 
	School infrastructure 
	Rural vs urban educational differences 
	Enrollment trends across school categories 

The dataset clearly shows that educational resources are not evenly distributed across schools.

K**ey Insights:**

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

Performed in This Project

•	Distribution of students 
•	Average teacher count 
•	School age analysis 
•	School type counts 
•	Enrollment distribution

**2. Diagnostic Analysis:**

Diagnostic Analysis is used to identify the reasons behind trends and patterns. This helped to identify the root causes of educational inefficiencies.

Performed in This Project

•	Correlation between students and teachers 
•	Urban vs rural enrollment comparison 
•	Student-Teacher Ratio analysis 
•	Outlier identification

**3. Predictive Analysis:**

Predictive Analysis is used to find the historical data to predict future outcomes. This analysis helped to find the Supports of the future educational planning and budgeting.

Possible Future Applications

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
2.   Urban and overcrowded schools require 
      •	More classrooms 
      •	Better facilities 
      •	Additional educational resources, for improved classroom management and reduced overcrowding.
3.   Introducing the followings to reduce the dropout rates. 
      •	Scholarship programs 
      •	Career guidance 
      •	Transport support 
      •	Awareness initiatives 
4.   Schools showing infinite Student-Teacher Ratio need immediate investigation by conducting audits and staffing verification, which can improve the operational efficiency.
5.   Since latitude and longitude are available, governments can perform the below points for better educational accessibility. 
      •	Map underserved regions 
      •	Identify school density gaps 
      •	Plan new school locations strategically
     
**Final Conclusion**

This project successfully transformed raw educational data into meaningful insights.
**The analysis revealed:**
•	Enrollment imbalance 
•	Teacher allocation gaps 
•	Urban-rural educational differences 
•	Infrastructure challenges 
**The dataset is highly valuable for:**
•	Educational policy planning 
•	Resource allocation 
•	Predictive modeling 
•	Public sector decision-making 
With advanced analytics and visualization, this dataset can support smarter educational reforms and long-term planning.    
