# 📊 Reddit Data Pipeline with Apache Airflow & AWS 🚀  

![Data Pipeline](https://img.shields.io/badge/Data%20Pipeline-ETL-blue)  
![Apache Airflow](https://img.shields.io/badge/Orchestration-Apache%20Airflow-orange)  
![AWS](https://img.shields.io/badge/Cloud-AWS-yellow)  
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)  
![Amazon Redshift](https://img.shields.io/badge/Warehousing-Redshift-red)  

## 🔥 Overview  
This project implements an **ETL pipeline** that extracts data from **Reddit API**, processes it using **Apache Airflow & Celery**, and stores it in **Amazon Redshift** for analytics.  

## 🛠️ Tech Stack  
- **🔗 Data Source:** Reddit API  
- **⚙️ Orchestration:** Apache Airflow & Celery  
- **🗄️ Temporary Storage:** PostgreSQL  
- **📦 Raw Data Storage:** Amazon S3  
- **🛠️ ETL & Metadata Management:** AWS Glue  
- **📊 Querying & Analysis:** Amazon Athena, Amazon Redshift  

## 🚀 Features  
✅ **Automated ETL Workflow:** Managed by Apache Airflow  
✅ **Scalable Data Processing:** Task distribution via Celery  
✅ **Metadata Storage:** PostgreSQL for temporary storage  
✅ **Cloud Storage & Processing:** AWS services for scalability  
✅ **SQL-based Analytics:** Query data with Amazon Athena & Redshift  

## 📌 Architecture  

![Reddit Data Pipeline](RedditDataEngineering.png)  

## 📦 Installation & Setup  
### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/reddit-data-pipeline.git
cd reddit-data-pipeline
