# HEADLINE
Explain where your dataset came from, and any potential challenges

This dataset came from an open-source archive on Kaggle on student lifestyle measured against their academic performance. Datapoints included  information on students' study habits, attendance, sleep patterns, social media usage, and academic performance. 

The dataset includes both numerical and categorical features, along with realistic relationships between lifestyle factors and academic outcomes. A small number of missing values, duplicate records, and outliers are included to simulate real-world data challenges.

## Data Analysis 

To comb through my data, I first created filters to sort out any empty values and delete null data. Afterwards, I played around with pivot tables to identify interesting trends or relationships. 

1. I first looked at the relationship between gender and academic performance factors (CGPA, Exam Score, Study Hours per Day). I created averages for the performance factors and compared them against the gender category; ultimately, the difference between genders was negligible, with only a decimal point of difference between Female and Male.

2. I then looked at the relationship between the academic performance rating given in the dataset (split between Poor, Average, and Good) and similar academic performance factors, including average attendance. Here, the relationship was more cogent, as all of the academic performance factors increased as the performance rating improved. For example, the average CGPA for students with a "Poor" academic performance rating was 1.9 on a 4.0 scale, while students with a "Good" rating had an average CGPA of 3.6. Factors such as attendance and study hours likely influenced this, as students with a "Poor" rating had an average attendance of 79.4% and studied for an average of 2.1 hours a day, as compared to those with a "Good" rating, whose average attendance was 83.7% and studied for an average of 4.7 hours a day.

3. I also wanted to see how stress level impacted other lifestyle and academic aspects, namely average hours of sleep and average exam score. Stress level was split into 3 categories (Low, Medium, High), and I created a pivot table to compare stress against the aforementioned factors. Here, I found that while the difference was minute, there did seem to be a slight relationship between stress level and these factors. Students with a "Low" stress level averaged 7.05 hours of sleep and scored an exam score average of 72.29. On the other hand, students with a "High" stress level averaged 6.75 hours of sleep a night. Intriguingly enough, however, students with "High" stress performed most poorly in exams, with an exam score average of 71.78. This could highlight a potential relationship between sleep levels and exam scores, or perhaps the negative impact of stress on academic performance.

## Data Visualizations 

