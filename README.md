E-Commerce Data Analysis and Visualization
This project is for getting in-depth analysis on how certian KPI'S (key performance indictators) contribute to the growth of an online sales market. These KPI's include:

Purchase time
Average daily transactions
Gender type
Geographical purchase traffic
Status of transactions
Total revenue
This project for the public with much recommendations for people aiming to get into the field of data analysis, and also business managers that want to see how an interactive dashboard can give insights into the activities of their businesses.

Badges
Introduction to Data Science : cognitveclass.ai

Data Science Tools : cognitveclass.ai

Author
@Apprentice-doa
Documentation
Documentation

Feedback
If you have any feedback, please reach out to me at: akdaniel0009@gmail.com

🚀 About Me
I'm a Data Scientist with experience in building end -to- end data analytics projects and machine learning algorithms.

Hi, I'm Daniel! 👋
🔗 Links
portfoliolinkedintwitter

Ongoing Projects
👩‍💻 I'm currently working on Logistic Regression modelling and Sentiment Analysis.

Current Learning path
🧠 I'm currently learning end-to-end machine learning projects.

Collaborations
👯‍♀️ I'm looking to collaborate on Data Visualization and machine learning projects.

💬 Ask me about Features Engineering in Data analytics, and other data analytics development chain.

⚡️ Fun fact: If you torture the data enough, it will confess to anything.

🛠 Skills
Python, DAX, Power Query, Features engineering, object-oriented programming.

Lessons Learned
What did you learn while building this project? What challenges did you face and how did you overcome them?

Related
Here are some related projects

Awesome README

Screenshots
App Screenshot

Environment Variables
To run this project, you will need to add the following environment variables to your .env file

API_KEY

ANOTHER_API_KEY

Documentation
Data Source
The data was sourced from kaggle, an open source platform for getting open source public datasets. The link to the dataset is: https://www.kaggle.com/datasets/roopeshbharatwajkr/ecommerce-dataset

Data Extraction
The dataset was gotten in spreadsheet(xlsx) format and imported into PowerBI.

Data Transformation
Before the dataset was loaded into PowerBI, it was first transformed.

The columns that were not needed for the analysis were removed [Transaction Id, Customer_ Id, Year_Month, Time].
The columns were converted to the right datatypes especiall the date column which was converted to the date datatype.
The value of Transaction_result was changed as 0 = Transaction failed and 1 = Transaction Successful.
The value of Transaction Start was changed to Transaction start.
The City['Los Angles'] was changed to City['Los Angeles'] for effective representation of the city on a map chart.
A date table was created using PowerBI date query code.
You can find the code here: PowerBI Date query code

A new table was created by duplicating the main table and the Transaction result was filtered to have just Transaction Successful.
The transformed data was then apllied to the visualization panel.
Data Modelling
New relationships were created between the tables, and date was used as the relationship between the three (3) tables.

Data visualization
A measure table was created and total revenue, number of Successful transactions, number products sold, average daily transactions were all calculated using DAX.
Charts were used to check for:
Expected Revenue by Transaction result
Revenue by City
Revenue by Device Type
Revenue by Date
Revenue by Category
Revenue by Gender
Date and Customer Login type filters were created as well.
Data Publishing
The data was published from the PowerBI environment and a linkn was generated for others to view and interact with the dashboard. Link to my dashboard: E-Commerce Dashboard
