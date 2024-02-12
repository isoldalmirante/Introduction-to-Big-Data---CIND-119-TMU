**Assignments completed for the Introduction to Big Data course Winter 2023**

**Course Description:**

This course is designed to give students an overview of big data, the state of the practice in analytics, the role of the data scientist, 
big data analytics in industry verticals, and analytics life-cycle as an end-to-end process. It focuses on key roles for a successful 
analytic project, the main phases of the life-cycle, developing core deliverables for stakeholders, teamwork skills, and problem-solving skills.

**Learn how to:**

- Engage in machine learning using Weka and IBM Watson.
- Employ appropriate statistical tests to test hypotheses on data.
- Implement machine learning algorithms both in supervised and unsupervised learning.
- Utilize relational database management systems, NoSQL, and Hadoop databases.
- Produce relevant visualizations from data.

**Assignment 1: Supervised learning using SAS**

The exercise was completed by first importing the breast-cancer-dataset.csv file into SAS and displaying its contents using the import and print procedures as instructed. 
Subsequently, a decision tree-based classification model was developed using the hpsplit procedure, allowing for an analysis of the confusion matrix, fit statistics, 
and variable importance through the Results View. Assessment metrics including accuracy, recall, and precision were computed based on the confusion matrix, with a clear 
identification of the positive class (recurrence-event or not-recurrence-event). Additionally, the grow algorithm was altered to "gini", and the assessment metrics were 
recalculated to compare the performance of the entropy and gini algorithms in building an accurate classifier.

**Assignment 2: Querying an RDBMS database using SQLiteStudio**

To tackle the exercise, I began by creating a database named "sample" using SQL commands. Within this database, I established a table named "test_data" and loaded the provided
dataset into it. Subsequently, I crafted SQL queries to fulfill the specified tasks. Firstly, I selected all rows from the "test_data" table where the "menopause" column had the 
value "ge40" and rows where the "age" column was less than 41. Additionally, I computed the average age across all rows and specifically across rows where the "deg_malig" value equaled 3. 
By executing these queries, I efficiently extracted and analyzed data from the dataset to meet the exercise requirements.
Throughout the process, attention to detail and adherence to SQL syntax were crucial. Each query was structured to accurately filter and compute the desired information from the "test_data" table. 
The creation of a well-organized database schema facilitated smooth data manipulation and ensured efficient execution of the queries. By following these steps, I effectively addressed the exercise's 
objectives, demonstrating proficiency in SQL query formulation and database management.

**Assignment 3: Querying a NoSQL database using MongoDB**

To complete this assignment using MongoDB, I first created a database named "sample" and within it, I created a collection named "test_data." Then, I loaded the provided data into the collection. 
For querying the data, I utilized MongoDB's query language. To select all rows where the menopause column has the value "ge40," I used the query {"menopause": "ge40"}. Similarly, to select all rows 
where age is less than 41, I employed the query {"age": {"$lt": 41}}. For selecting rows where age is less than 41 or the menopause column has the value "ge40," I combined the two conditions using 
the "$or" operator. To compute the average age across all rows, I utilized MongoDB's aggregation framework, specifically the $avg operator. By applying these queries, I efficiently retrieved and 
computed the desired data from the "test_data" collection in the MongoDB database.
