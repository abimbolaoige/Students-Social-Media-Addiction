Social Media Addiction Among Students: A Data-Driven Analysis

Background
This analysis was inspired by growing concerns and bitter outcries from parents regarding poor academic performance and the apparent loss of control over their children’s social media usage.

The goal was to identify patterns, assess the impact on academic performance and mental health, and propose actionable solutions to mitigate the adverse effects of social media addiction.

Methodology
A “Students’ Social Media Addiction” dataset sourced from Kaggle was downloaded in CSV format from various countries including Nigeria, converted to Excel, and cleaned for analysis by checking blank cells and duplicates. A pivot table was created to highlight key addiction indicators, and various charts, including pie and clustered column charts were used to visualize the data.

To simplify analysis, the following additional columns were included:

Addiction Level
Sleep Quality Category
Avg Daily Hour Usage Category

An interactive dashboard was developed using slicers to enable dynamic and engaging data exploration.

To enhance the depth of the analysis, the cleaned data was imported into Microsoft SQL Server (MSSQL), where a new database, "Social_Media_DB was created. Within it, a table named Social_Media_Addiction was designed to store addiction-related metrics with the following columns:

Student_ID				INT	Primary Key,
Age					INT,
Gender					VARCHAR(50),
Academic_Level			VARCHAR(50),
Country				VARCHAR(50),
Avg_Daily_Usage_Hours		INT,
Most_Used_Platform			VARCHAR(60),
Affects_Academic_Performance	VARCHAR(50),
Sleep_Hours_Per_Night			INT,
Mental_Health_Score			INT,
Relationship_Status			VARCHAR(60),
Conflicts_Over_Social_Media		INT,
Addicted_Score				INT,
Addiction_Level			VARCHAR(50),
Sleep_Quality_Category		VARCHAR(50),
Avg_Daily_Hour_Usage_Category	VARCHAR(50)



Data was inserted from excel via concatenation, and five insightful SQL queries were executed to uncover key patterns and correlations. Here's the link to the SQL file

After the analysis, some information were derived. 

Key Findings

1. High Average Daily Usage
Some students reported over 6 hours of daily social media use. The “Addicted User” and “Heavy User” categories predominantly logged more than 4 hours/day.

2. Academic Impact
There was a strong correlation between higher addiction levels and poorer academic performance. Students in the “High” addiction category were more likely to affirm that social media interfered with their studies.

3. Mental Health Concerns
Students with elevated addiction scores reported lower mental health scores, showing symptoms of anxiety, fatigue, and stress.

4. Sleep Deprivation
As addiction levels increased, sleep hours decreased. “Addicted Users” reported sleeping less than 6 hours/night, while “Regular Users” showed healthier sleep patterns.

5. Most Used Platforms
Instagram, TikTok, and YouTube were the dominant platforms among highly addicted users. These platforms, known for their short-form, infinite-scroll content, were particularly addictive.


Demographic Insights

Undergraduates constituted the majority of high-usage participants.

High daily usage was most prevalent in the USA, India, and Bangladesh.


Root Causes of Addiction

1. Instant gratification from likes, comments, and video content

2. Fear of Missing Out (FOMO)

3. Poor time management, especially among undergraduates

4. Emotional reliance on social validation

5. Peer and cultural influence through trending platforms


Proposed Solutions; Schools, Students, Parents, Tech companies 

For Educational Institutions

Conduct digital wellness workshops

Create tech-free zones or hours on campus

Integrate digital literacy and media ethics into the curriculum


For Students

Use digital wellbeing tools and app time limits

Establish screen-free bedtime routines

Replace scrolling with offline hobbies, physical activity, or educational content


For Parents

Encourage open conversations about media use

Promote offline family activities and set tech boundaries

Model balanced media habits


For Technology Platforms

Add reminders after extended screen time

Reward users for taking screen breaks

Limit autoplay and infinite-scroll functionalities


Suggested KPIs for Future Monitoring

Average Daily Social Media Hours

Average Sleep Hours

Self-Reported Mental Health Scores

Academic Performance Indicators (e.g., GPA, test scores)

Addiction Score trends by semester or year


Conclusion
This analysis reveals that social media addiction among students is a growing concern with clear implications for academic performance, mental health, and sleep quality. While social media holds educational and social value, its overuse poses real risks. By fostering collaboration among students, educators, parents, and tech companies, these issues can be effectively addressed through education, regulation, and the promotion of healthier digital habits.
