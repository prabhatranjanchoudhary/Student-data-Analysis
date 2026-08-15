# Student data Analysis
📊 Student Marks Analysis

A beginner-friendly data analysis project using Python, Pandas, NumPy, Matplotlib, and Seaborn to explore student performance and identify relationships between academic scores and demographic/parental factors.

📌 Project Overview

This project analyzes a dataset containing students' Math, Reading, and Writing scores, along with information such as gender, ethnic group, parents' education, parents' marital status, and sports participation.

The goal is to clean the dataset, explore its structure, identify patterns, and visualize relationships that may be associated with student performance.

🎯 Objectives

- Understand and inspect the student dataset
- Perform basic data cleaning
- Analyze gender and ethnic-group distributions
- Examine the relationship between parents' education and student scores
- Examine the relationship between parents' marital status and student scores
- Explore the distribution of Math, Reading, and Writing scores
- Create visualizations to communicate findings clearly

🛠️ Technologies Used

- Python
- Pandas - Data manipulation and analysis
- NumPy - Numerical operations
- Matplotlib - Data visualization
- Seaborn - Statistical visualization
- Jupyter Notebook - Development environment

📂 Dataset

The project uses a CSV dataset named:

"Student_Scores.csv"

The dataset contains information related to:

- Gender
- Ethnic Group
- Parents' Education
- Parents' Marital Status
- Practice Sport
- Math Score
- Reading Score
- Writing Score

🔍 Analysis Performed

1. Data Inspection

The dataset was inspected using:

- "head()"
- "describe()"
- "info()"
- "isnull().sum()"

An unnecessary "Unnamed: 0" column was identified and removed during data cleaning.

2. Gender Distribution

A count plot was created to compare the number of male and female students in the dataset.

3. Parents' Education vs Student Performance

The average Math, Reading, and Writing scores were calculated for different levels of parents' education.

A heatmap was used to make the comparison easier to understand.

Observation: Students whose parents have higher levels of education generally show higher average scores in this dataset. This indicates an association, not necessarily a causal relationship.

4. Parents' Marital Status vs Student Performance

Average Math, Reading, and Writing scores were compared across different parental marital-status categories.

Observation: The differences between groups appear relatively small, suggesting that parents' marital status has little observable association with student scores in this dataset.

5. Score Distribution

Box plots were created for:

- Math Score
- Reading Score
- Writing Score

These visualizations help identify the distribution, spread, and potential outliers in student performance.

6. Ethnic Group Distribution

The number and proportion of students belonging to different ethnic groups were visualized using a pie chart and count plot.

7. Sports Participation

A count plot was used to examine the distribution of students based on sports participation.

📈 Key Insights

- The dataset contains more female students than male students.
- Parents' education level appears to be associated with differences in average student scores.
- Parents' marital status shows little observable relationship with student scores in this dataset.
- Math, Reading, and Writing scores show different distributions and levels of variation.
- The dataset contains students from multiple ethnic groups with different representation levels.
- Sports participation varies across the students in the dataset.

🚀 How to Run the Project

1. Clone this repository:

git clone https://github.com/your-username/student-marks-analysis.git

2. Navigate to the project folder:

cd student-marks-analysis

3. Install the required libraries:

pip install pandas numpy matplotlib seaborn jupyter

4. Start Jupyter Notebook:

jupyter notebook

5. Open:

"Student_Marks_Analysis.ipynb"

6. Make sure "Student_Scores.csv" is located in the same directory as the notebook.

📁 Project Structure

Student-Marks-Analysis/
│
├── Student_Marks_Analysis.ipynb
├── Student_Scores.csv
└── README.md

📚 What I Learned

Through this project, I practiced:

- Loading CSV data with Pandas
- Inspecting and cleaning datasets
- Handling unnecessary columns
- Using "groupby()" and aggregation
- Calculating average scores
- Creating statistical visualizations
- Using Seaborn and Matplotlib
- Interpreting patterns in datasets
- Communicating data-driven observations

🔮 Future Improvements

Possible improvements for future versions include:

- Adding correlation analysis between numerical variables
- Creating more detailed comparisons between student groups
- Analyzing whether sports participation is associated with academic performance
- Adding interactive visualizations
- Building a simple dashboard using Power BI or Tableau
- Performing more advanced statistical analysis

👨‍💻 Author

Prabhat

This project is part of my journey toward becoming a Data Analyst.
