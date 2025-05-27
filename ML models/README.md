# 📊 Student Habits vs Academic Performance - EDA

This project explores the impact of various lifestyle and habit-based factors (like sleep, social media usage, study time, etc.) on students’ academic performance using the **"Student Habits vs Academic Performance"** dataset from Kaggle.

## 📁 Dataset Source

- **Kaggle URL**: [Click here to view](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)

## 📌 Dataset Features

| Column Name                  | Description                                   |
|-----------------------------|-----------------------------------------------|
| `student_id`                | Unique student identifier                     |
| `age`                       | Age of the student                            |
| `gender`                    | Gender (Male/Female/Other)                    |
| `study_hours_per_day`       | Average number of study hours per day         |
| `social_media_hours`        | Daily time spent on social media              |
| `netflix_hours`             | Daily Netflix or binge-watching time          |
| `part_time_job`             | Whether the student has a part-time job       |
| `attendance_percentage`     | Class attendance in percentage                |
| `sleep_hours`               | Daily average sleep hours                     |
| `diet_quality`              | Diet quality (Poor/Fair/Good)                 |
| `exercise_frequency`        | Frequency of exercise                         |
| `parental_education_level`  | Education level of parents *(has 91 missing)* |
| `internet_quality`          | Internet quality                              |
| `mental_health_rating`      | Mental health rating                          |
| `extracurricular_participation` | Participation in extracurriculars        |
| `exam_score`                | Final exam score                              |

## 📂 Project Files

| Filename      | Description                                            |
|---------------|--------------------------------------------------------|
| `eda.ipynb`   | Initial exploratory data analysis notebook             |
| `new_eda.ipynb` | Extended or refined version of the EDA notebook      |

---

## 🛠 How to Run the Project

### 1. Clone the Repository

If hosted on GitHub:
```bash
git clone https://github.com/shivamm070402/Student-Performance-vs-Habits/blob/main/ML%20models/eda.ipynb
cd Student-Performance-vs-Habits/ML\ models/


---

### How to create and commit this README:

```bash
# In your project folder
echo "# Student Performance vs Habits

## Overview
This project explores the relationship between students' habits and their exam scores. Using data analysis and visualization techniques, it investigates which habits positively or negatively influence academic performance.

## Setup Instructions

### 1. Clone the Repository
\`\`\`bash
git clone https://github.com/shivamm070402/Student-Performance-vs-Habits.git
cd Student-Performance-vs-Habits/ML\\ models/
\`\`\`

### 2. Install Required Libraries
Make sure you have Python installed. Then install dependencies:

\`\`\`bash
pip install pandas numpy matplotlib seaborn jupyter
\`\`\`

Or, if a \`requirements.txt\` file is provided:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

### 3. Launch Jupyter Notebook
\`\`\`bash
jupyter notebook
\`\`\`

Open one of these notebooks in your browser:
- \`eda.ipynb\` – Initial data exploration  
- \`new_eda.ipynb\` – Refined analysis

## Project Goals
- Explore correlations between habits and exam scores  
- Handle missing data (especially in \`parental_education_level\`)  
- Visualize data trends with box plots, histograms, scatter plots  
- Identify habits that influence academic performance

## Contact
For questions or contributions, please open an issue or pull request.

---

*Happy analyzing! 📊*

" > README.md

# Then add and commit
git add README.md
git commit -m "Add README with project setup and goals"
git push
