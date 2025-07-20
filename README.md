
## Udemy Courses Data Analysis Report
# Overview
This exploratory data analysis (EDA) project explores a large dataset of Udemy online courses to uncover key insights related to course subjects, pricing, levels, popularity, number of subscribers, and other metrics.
The dataset contains thousands of courses across multiple categories. The analysis was conducted using Python in a Jupyter Notebook environment.

# Objectives
This project aims to answer the following key questions:

# Subjects:

-What is the distribution of courses per subject?

-Which subject is the most popular in terms of subscribers?

# Subscribers:

-How many subscribers per subject?

-What are the overall stats for subscribers (mean, max, min, sum)?

-What is the course with the highest number of subscribers?

-How does the number of subscribers change by year?

# Course Levels:

-How many levels are there?

-How are courses distributed across levels and subjects?

-What is the most common level?

# Lectures:

-What is the relationship between course level and number of lectures?

-What is the relationship between lectures and reviews?

# Price Analysis:

-What is the average, minimum, and maximum course price?

-What is the most profitable course?

-What are Udemy's potential total earnings?

# Paid vs Free Courses:

-How many courses are free vs paid?

-How are free/paid courses distributed across different subjects?

# Course Titles:

-What are the longest and shortest course titles?

# Dataset Description
-Source: Udemy course dataset

Key Columns:

subject

price

level

num_subscribers

num_lectures

num_reviews

is_paid

published_timestamp

title

## Key Findings
# Subject Distribution
-Total courses per subject:

Web Development: 1200 courses

Business Finance: 1199 courses

Musical Instruments: 681 courses

Graphic Design: 603 courses

-Most popular subject (by total subscribers): Web Development

# Subscribers Analysis
-Subscribers per subject:

Web Development: 7,980,572

Business Finance: 1,870,747

Graphic Design: 1,063,148

Musical Instruments: 846,719

-Aggregate statistics:

Mean: 3,193

Max: 268,923

Min: 0

Total: 11,761,186

-Course with the most subscribers:
Learn HTML5 Programming From Scratch

-Subscribers per year:

2011: 119,028

2012: 555,339

2013: 1,723,438

2014: 1,930,406

2015: 3,475,324

2016: 2,966,644

2017: 991,007

# Course Levels
-Number of levels:

All Levels: 1,932

Beginner: 1,271

Intermediate: 421

Expert: 58

-Most common level: All Levels

-Distribution per subject and level:

<img width="552" height="708" alt="download" src="https://github.com/user-attachments/assets/ea39cd28-4210-4ac6-ac7f-eb0ed97c1e23" />



-Subject	All Levels	Beginner	Intermediate	Expert
Web Development	659	391	135	15
Business Finance	699	341	128	31
Graphic Design	298	243	57	5
Musical Instruments	276	296	101	7

# Lectures Analysis
Analyzed relationship between:

Levels vs Number of Lectures

<img width="1617" height="853" alt="download" src="https://github.com/user-attachments/assets/ba8c3ac1-773e-460f-a24a-6a1018f59651" />


Lectures vs Reviews

<img width="1634" height="853" alt="download" src="https://github.com/user-attachments/assets/47d19a37-7a1b-4903-ab12-a59ca2fa8c61" />



# Price Analysis
Max price: $200

Min price: $0


- Most profitable course:
The Web Developer Bootcamp

- Estimated total earnings:
$884,982,395.00

- Paid vs Free Courses
Number of courses:

Paid: 3,372

Free: 310

-Paid vs Free per subject:


<img width="627" height="602" alt="download" src="https://github.com/user-attachments/assets/0e57eeab-df78-4c48-851c-c0afde0ed21e" />




# Course Titles
-Longest title:
Aprende a tocar el Acordeón 'de oído y con técnica'


# Tools & Libraries Used
Tool	Purpose
-Python	Programming language
-Jupyter	Interactive coding
-Pandas	Data manipulation
-NumPy	Numerical operations
-Matplotlib	Data visualization
-Seaborn	Statistical visualization

# Insights & Recommendations
-Investing in Web Development content can attract a high number of subscribers.

-Courses at the "All Levels" tier are most common and may appeal to broader audiences.

-High subscriber count does not always mean high revenue — pricing plays a key role.

-Udemy’s free courses attract users, but paid content dominates the platform’s potential revenue.
