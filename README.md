# NCAA Men's Division 1 College Basketball Statistics & Information Database

A data engineering/analytics project to learn to scrape (Extract), pre-process (Transform), and make available for analysis (Load) statistics and information about men's NCAA Division 1 college basketball teams. The goals of this project include the following:

- Use a webscraping application/library in Python (e.g. BeautifulSoup) to scrape data from websites containing required information (e.g. sports-reference, NCAA website, ESPN etc.)
- Pre-process and build a relational database using SQL (or Python/pandas + SQL?) and following database construction guidelines (e.g. normal forms)
- Load data into a local cloud via LocalStack to emulate cloud storage; alternatively, use Docker + MongoDB to set up a local database
- Access data from the cloud to perform EDA and train machine learning algorithms with Apache Spark 
- Access data from dashboard interface (e.g. Tableau, streamlit) using SQL queries
- Separately, consider doing this all using orchestration technologies such as Airflow or Snowflake

## Webscraping with BeautifulSoup
