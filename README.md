A comprehensive exploratory data analysis (EDA) project examining social media addiction patterns 
among students and their effects on academic performance, mental health, sleep quality, and 
relationships.

Project Overview:
This Jupyter Notebook analyzes the "Students Social Media Addiction" dataset to understand how 
social media usage patterns affect various aspects of students' lives. The study helps identify 
risk factors and provides insights for interventions to improve student wellbeing.

Key Research Questions:
- How does social media usage affect academic performance?
- What is the relationship between social media addiction and sleep quality?
- How does social media impact mental health scores?
- Do relationship statuses correlate with addiction levels?
- Which platforms are most associated with high addiction scores?

Analysis Components:

1. **Data Preparation**
   • Dataset: 700+ student records with 13 attributes
   • Libraries: Pandas, NumPy, Matplotlib, Seaborn
   • Data cleaning and preprocessing
   • Missing value handling

2. **Exploratory Data Analysis**
   • Demographic distributions (Age, Gender, Country, Academic Level)
   • Platform usage patterns and daily usage hours
   • Addiction score distributions
   • Correlation analysis

3. **Key Investigations**
   • Sleep hours vs academic performance impact
   • Mental health scores vs social media effects
   • Addiction scores by relationship status
   • Platform preferences and usage patterns

Major Findings:

**Academic Performance & Sleep:**
- Students reporting academic impact sleep significantly less (lower median)
- Clear negative correlation between social media usage and sleep quality
- "YES" group shows noticeably reduced sleep duration vs "NO" group

**Mental Health Impact:**
- Students unaffected by social media: Mean score = 7.4 (range: 7-9)
- Students affected by social media: Mean score = 5.6 (range: 5-6)
- 25% lower mental health scores for affected students
- Strong evidence of mental health challenges linked to excessive usage

**Relationship Status & Addiction:**
- Single students: Highest addiction scores with wide variation
- In Relationship: Moderate addiction levels (mean: 6.34)
- Complicated status: Highest mean score (7.03)
- Clear correlation between relationship status and addiction patterns

Visualizations:
- Box plots comparing sleep hours by academic impact
- Mental health score distributions across groups
- Addiction score analysis by relationship status
- Statistical summaries with descriptive statistics
- Custom seaborn styling for publication-quality plots

Technical Stack:
- **Language**: Python 3.12.7
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook
- **Statistical Methods**: Descriptive statistics, groupby analysis, boxplot comparisons

Practical Applications:
- Identifying at-risk student populations
- Developing targeted intervention strategies
- Informing campus mental health programs
- Creating awareness campaigns about healthy social media use
- Supporting academic counseling initiatives

Dataset Attributes (13 features):
- Demographics: Student_ID, Age, Gender, Academic_Level, Country
- Usage: Avg_Daily_Usage_Hours, Most_Used_Platform
- Impact: Affects_Academic_Performance, Sleep_Hours_Per_Night
- Wellbeing: Mental_Health_Score, Relationship_Status
- Addiction: Addicted_Score, Conflicts_With_Family

