# Experince-Vs-Salary-Analysis-Project
This project involves analyzing the relationship between experience and salary using Jupyter Notebook. It utilizes libraries such as Pandas, Matplotlib, and Seaborn for data manipulation, visualization, and analysis. The data is loaded from a CSV file and explored to gain insights. 


For set up, follow these steps:

**Step 1:** Import the necessary libraries

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

**Step 2:** Load the data
Assuming you have your data in a CSV file named "salary_data.csv" located in the same directory as your notebook, you can load it using the following code:
data = pd.read_csv("salary_data.csv")

**Step 3:** Explore the data
Before diving into the analysis, it's essential to understand the structure and content of the dataset. You can use various Pandas functions to gain insights into the data. For example:
data.head()  # Display the first few rows
data.info()  # View the column data types and check for missing values
data.describe()  # Generate descriptive statistics


**Step 4:** Visualize the data
To analyze the relationship between experience and salary, you can create a scatter plot using Matplotlib or Seaborn. Here's an example using Seaborn:
sns.scatterplot(x='Experience', y='Salary', data=data)
plt.title('Experience vs. Salary')
plt.xlabel('Experience')
plt.ylabel('Salary')
plt.show()
This code will create a scatter plot with experience on the x-axis and salary on the y-axis.

**Step 5:** Analyze the data
After visualizing the data, you can perform statistical analysis to understand the relationship between experience and salary. One common approach is to calculate the correlation coefficient. Here's an example:
correlation = data['Experience'].corr(data['Salary'])
print(f"Correlation coefficient: {correlation}")

A correlation coefficient close to 1 indicates a strong positive correlation, while a value close to -1 indicates a strong negative correlation.
After processing data and performing various steps we have analyzed following output :-
![Year Experince vs Salary Graph](https://github.com/Aishwarya-Kore/Experince-Vs-Salary-Analysis-Project/assets/107603852/266a8e6f-18eb-4d78-a633-780917babc8f)






