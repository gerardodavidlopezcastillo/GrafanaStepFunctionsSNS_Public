# GrafanaStepFunctionsSNS_Public
## **Streaming Data Engineering Project with Apache Druid and Grafana**

This repository contains the code and configuration needed for a streaming data engineering project that enables real-time data processing and provides valuable insights through Grafana. The project uses a combination of technologies and services, including Confluent, Apache Druid, AWS SNS, EC2, Athena, S3, Glue, StepFunctions, and EventBridge, to achieve a comprehensive streaming data processing solution.

## **Key Features:**
**Real-Time Data Ingestion:** The project utilizes Confluent to receive events from the topic named **topic_GrafanaStepFunctionsSNS**, ensuring real-time data capture.

**Data Processing with Apache Druid:** An Ubuntu instance on EC2 is utilized to deploy Apache Druid, a highly efficient real-time database and advanced analytics platform, for processing and storing data.

**Interactive Visualization with Grafana:** Processed information is effectively presented in Grafana, allowing the creation of interactive dashboards and charts for real-time data analysis.

**Advanced Alerts and Notifications:** Alerts are configured through AWS SNS, enabling email notifications in response to specific events, ensuring rapid detection of critical data changes.

**Automation and Scheduled Queries:** AWS Lambda is combined with S3 to automate periodic queries in Athena, ensuring constant access to updated data. These processes are orchestrated using StepFunctions, enabling the creation of organized workflows.

**Scheduled Notifications:** EventBridge is used to schedule notifications every 3 hours using a cron, facilitating continuous data tracking and data-informed decision-making.

This project represents a complete and scalable solution for real-time data processing and analysis. Feel free to contribute and customize this solution to meet the specific needs of your organization.
