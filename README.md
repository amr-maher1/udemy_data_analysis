#  Udemy Data Analysis Project 

##  Overview

This project is an exploratory data analysis (EDA) on a Udemy courses dataset. The goal is to derive insights about course subjects, prices, levels, subscribers, and more.

The analysis was performed using Python in a Jupyter Notebook. The dataset includes information about thousands of Udemy courses.

---

##  Objectives & Questions Answered

###  Subject
- What is the distribution of subjects?

  
  <img width="561" height="547" alt="download" src="https://github.com/user-attachments/assets/95a64932-e511-4894-913c-1f0e02e3d83b" />

  
- How many courses per subject?
  Web Development        1200
  Business Finance       1199
  Musical Instruments     681
  Graphic Design          603
- Which subject is the most popular?
  the most popular subject is  Web Development
###  Subscribers
- Number of subscribers per subject.
  we find that
  Business Finance       1870747
  Graphic Design         1063148
  Musical Instruments    846719
  Web Development        7980572
- Aggregate stats (min, max, mean, sum).
  mean= 3193.3711648112953
  max= 268923
  min= 0
  sum= 11761186
- Course with the highest number of subscribers.
  the course is Learn HTML5 Programming From Scratch
- Number of subscribers per year.
  2011     119028
  2012     555339
  2013    1723438
  2014    1930406
  2015    3475324
  2016    2966644
  2017     991007
###  Level
- How many levels exist?
All Levels            1932
Beginner Level        1271
Intermediate Level    421
Expert Level          58
- Distribution of courses per level.

  
  <img width="561" height="521" alt="download" src="https://github.com/user-attachments/assets/195bf1fa-0771-4647-83ec-07239f64f6fa" />


- Subscribers per level.
subject              level             
Business Finance     All Levels            699
                     Beginner Level        341
                     Intermediate Level    128
                     Expert Level           31
Graphic Design       All Levels            298
                     Beginner Level        243
                     Intermediate Level     57
                     Expert Level            5
Musical Instruments  Beginner Level        296
                     All Levels            276
                     Intermediate Level    101
                     Expert Level            7
                     52                      1
Web Development      All Levels            659
                     Beginner Level        391
                     Intermediate Level    135
                     Expert Level           15
- Most common level per subject.
  The most commen level is all level
###  Lectures
- Relation between levels and lectures.

<img width="1617" height="853" alt="download" src="https://github.com/user-attachments/assets/20fedc48-b75a-4341-8db9-f3e123753295" />

  
- Lectures vs reviews.

  
<img width="1634" height="853" alt="download" src="https://github.com/user-attachments/assets/db9cf4d1-c563-4dee-9894-41d3f3a24a04" />


###  Price
- Average, minimum, and maximum course prices.
  max= 200
  min= 0
- Most profitable courses.
  The most profitable course is The Web Developer Bootcamp
- Udemy's potential earnings.
  is equale= 884982395.0

### 🟩 is_paid
- How many courses are free vs paid?
Is_paid    3372
Free       310
- Distribution of paid/free courses per subject.

<img width="561" height="455" alt="download" src="https://github.com/user-attachments/assets/f8177bb4-5c0c-4e9b-8d8a-bb3b1cec083f" />


###  Course Title
- Longest and shortest course titles.
is Aprende a tocar el Acordeón 'de oído y con téc..
---

##  Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib / Seaborn
- Numpy
