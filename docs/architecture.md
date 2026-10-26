\# E-Commerce Marketplace Data Engineering Platform



\## 1. Project Objective



Build a company-style batch data engineering platform using Google Cloud Platform, Python, PySpark, Dataproc, Cloud Storage, BigQuery, Airflow, and Cloud Functions.



\## 2. Data Sources



The project uses synthetic e-commerce data containing:



\- Customers

\- Products

\- Orders

\- Order items



\## 3. Architecture



1\. Python generates synthetic source files.

2\. Google Cloud Storage stores the raw source files in the Bronze layer.

3\. Dataproc runs PySpark batch jobs.

4\. PySpark validates, cleans, joins, and transforms the data.

5\. Silver contains validated and standardized data.

6\. Gold contains business-ready analytical data.

7\. BigQuery stores analytical tables for SQL queries and reporting.

8\. Airflow orchestrates batch processing and validation.

9\. Cloud Functions provides an optional event-triggered integration for new GCS files.



\## 4. Engineering Practices



\- Git branching and pull requests

\- Data quality checks

\- Incremental processing and idempotency

\- Logging and error handling

\- IAM least privilege

\- Secure credential management

\- Automated testing

\- Cloud cost management



\## 5. Scope



This version focuses on batch processing. Streaming and Pub/Sub are outside the project scope.



