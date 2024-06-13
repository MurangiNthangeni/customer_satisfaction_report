# Customer Satisfaction Report

## Objective: Developing a customer satisfaction report to analyze survey data.
 
#### Dataset: Using the following predefined dataset for this task:
 
#### Sample customer satisfaction data for the task

np.random.seed(1)
customers = ['Customer A', 'Customer B', 'Customer C', 'Customer D', 'Customer E']
responses = np.random.choice(['Very Satisfied', 'Satisfied', 'Neutral', 'Unsatisfied', 'Very Unsatisfied'], size=50)
 
survey_data = pd.DataFrame({
    'Customer': np.random.choice(customers, size=50),
    'Response': responses
})
 
#### Subtasks:
 
1.Calculate and visualize the distribution of customer responses using a bar chart.
2.Display a summary table with the count and percentage of each response category.
3.Implement a radar chart to compare satisfaction levels across different customer segments.
4.Create a word cloud based on customer feedback comments.
5.Include interactive filters to explore responses based on customer segments.
