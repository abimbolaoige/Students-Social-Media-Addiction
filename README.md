“Social Media Addiction Among Students: A Data-Driven Analysis”

📱 Social Media Addiction Among Students: A Data-Driven Analysis

🧠 Background

This project was inspired by growing concerns and outcries from parents, educators, and stakeholders regarding poor academic performance and the apparent loss of control over students' social media usage.

The analysis seeks to identify patterns, assess the impact of social media addiction on academic performance and mental health, and propose actionable strategies to mitigate its adverse effects.


🗂️ Project Structure


Social-Media-Addiction-Analysis/
│
├── data/
│   └── students\_social\_media.csv           # Cleaned dataset from Kaggle
│
├── sql/
│   └── social\_media\_addiction.sql          # SQL script for DB schema, inserts, and insights
│
├── dashboard/
│   └── dashboard\_screenshot.png            # Excel dashboard visual
│
├── README.md                               # Project overview and usage guide
└── findings.pdf (optional)                 # In-depth report (if available)

🧰 Tools & Technologies Used

- Microsoft SQL Server (MSSQL)
- Microsoft Excel (Data Cleaning & Dashboard)
- Excel Pivot Tables & Slicers
- Charts: Pie Charts, Clustered Columns, etc.
- Data Source: Kaggle (Students’ Social Media Addiction dataset)

🧪 Methodology

- Dataset downloaded in CSV format from Kaggle (global, multi-country).
- Cleaned and structured in Excel: removed blanks, checked for duplicates.
- Additional computed columns:
  - **Addiction Level**
  - **Sleep Quality Category**
  - **Average Daily Hour Usage Category**
- Created pivot tables and interactive dashboards with slicers.
- Imported cleaned data into MSSQL:
  - Created `Social_Media_DB` database.
  - Defined `Social_Media_Addiction` table with columns covering demographics, usage patterns, mental health, and academic metrics.
- Executed SQL queries to extract insights.

🧾 Table Schema

```sql
Student_ID                       INT PRIMARY KEY,
Age                              INT,
Gender                           VARCHAR(50),
Academic_Level                   VARCHAR(50),
Country                          VARCHAR(50),
Avg_Daily_Usage_Hours            INT,
Most_Used_Platform               VARCHAR(60),
Affects_Academic_Performance     VARCHAR(50),
Sleep_Hours_Per_Night            INT,
Mental_Health_Score              INT,
Relationship_Status              VARCHAR(60),
Conflicts_Over_Social_Media      INT,
Addicted_Score                   INT,
Addiction_Level                  VARCHAR(50),
Sleep_Quality_Category           VARCHAR(50),
Avg_Daily_Hour_Usage_Category    VARCHAR(50)
````

📊 Key Insights

1. High Average Daily Usage

Many students reported over **6 hours/day** on social media.
"Addicted" and "Heavy" users mainly used platforms for more than 4 hours/day.

2. Academic Impact

Strong correlation between addiction level and academic struggles.

3. Mental Health Concerns

* Higher addiction scores matched with lower mental health scores.

4. Sleep Deprivation

* As usage increased, sleep hours decreased significantly.

5. Most Addictive Platforms

* Instagram, TikTok, YouTube dominated among high-addiction users.


🌍 Demographic Observations

* **Undergraduates** were the most affected group.
* Top countries with high usage: **USA, India, Bangladesh**.


🔍 Root Causes of Addiction

1. Instant gratification from likes/comments
2. Fear of Missing Out (FOMO)
3. Poor time management
4. Emotional dependence on validation
5. Peer/cultural influences


💡 Proposed Solutions

🎓 For Schools

* Host digital wellness workshops
* Create tech-free campus zones
* Add media literacy to curriculum

👩🏽‍🎓 For Students

* Use app timers/digital wellbeing tools
* Set screen-free routines
* Engage in offline hobbies

👨‍👩‍👧 For Parents

* Encourage open communication
* Promote offline bonding
* Model balanced media habits

💻 For Tech Companies

* Introduce screen-time reminders
* Reward breaks
* Restrict infinite-scroll & autoplay


📈 Suggested KPIs for Future Monitoring

* Avg Daily Social Media Usage Hours
* Avg Sleep Hours
* Mental Health Score (self-reported)
* Academic Performance (GPA/Test Scores)
* Addiction Score Trends (Semester/Yearly)


⚙️ How to Run This Project

Prerequisites

* Microsoft SQL Server or Azure Data Studio
* Excel (for dashboard viewing)

Steps

1. Create a new database:

```sql
CREATE DATABASE Social_Media_DB;
```

2. Run the SQL script in `/sql/social_media_addiction.sql` to:

   * Create the table
   * Insert sample data
   * Execute analytical queries


 📌 Credits

* Dataset: [https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships]
* Analysis & Report: Abimbola Odunola Ige


📬 Contact

Feel free to connect or give feedback:
Email: [abimbolaoige@gmail.com)
GitHub: [github.com/abimbolaoige)





