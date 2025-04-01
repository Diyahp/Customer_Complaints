<h1> About the dataset </h1>
The Consumer Complaints Dataset is a structured collection of 14,000 complaints filed by customers regarding financial products and services.
It is designed to analyze consumer grievances, company responses, and resolution efficiency.
The dataset helps in identifying patterns in customer complaints, dispute trends, resolution times, and company performance across different financial institutions.
This dataset is crucial for financial analysts, data scientists, regulatory bodies, and businesses looking to improve customer satisfaction, ensure compliance, and optimize their complaint resolution processes.

## Project Goals

* Explore the dataset to understand its structure and distributions.
* Clean the data by handling missing values, outliers, and inconsistencies.
* Analyze the cleaned data to answer specific questions regarding complaint patterns.
* Visualize the findings to provide clear and actionable insights.

## Methodology

This project follows a structured approach, encompassing:

1.  **Data Loading and Exploration:**
    * Loading the dataset into a pandas DataFrame.
    * Exploring the dataset's shape, data types, missing values, and summary statistics.
    * Analyzing the distribution of key variables.
2.  **Data Cleaning:**
    * Handling missing values in relevant columns.
    * Addressing outliers in the 'Resolution time(in days)' column.
    * Converting date columns to datetime format.
    * Checking and handling duplicate entries.
3.  **Data Analysis:**
    * Calculating complaint frequencies by product type.
    * Identifying companies with the highest complaint volumes.
    * Calculating the average complaint resolution time.
    * Analyzing the relationship between issue types and timely responses.
    * Examining the distribution of consumer disputes.
    * Calculating the average response time by product.
4.  **Data Visualization:**
    * Generating bar charts to visualize complaint frequencies by product and company.
    * Creating a pie chart to illustrate the distribution of consumer disputes.
    * Creating a bar chart to visualize the average response time for each product.
    * Creating a contingency table to show the relationship between consumer disputes and timely responses.

## Key Findings

* **Complaint Volume by Product:**
    * "Mortgage" is the most frequently reported product in consumer complaints.
* **Complaint Volume by Company:**
    * "Bank of America" receives the highest volume of consumer complaints.
* **Average Resolution Time:**
    * The average complaint resolution time is approximately 2.01 days.
* **Response Timeliness:**
    * Response timeliness varies across different complaint issues, with some achieving 100% timely responses.
* **Consumer Disputes:**
    * A significant percentage of complaints result in consumer disputes.
    * The relationship between disputes and timely responses is shown in a contingency table.
* **Response Time Variation by Product:**
    * Average response times differ significantly across various financial products.

## Questions Answered

* What are the most common product types with complaints?
* Which companies receive the most complaints?
* What is the average response time for complaints?
* Is there a correlation between the type of issue and the timeliness of the response?
* How are consumer disputes distributed?
* What is the average response time by product?

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
