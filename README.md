# Glue-Athena-QuickSight Data Analytics Pipeline

## Project Diagram
![Project Workflow](/superStore/StoreAnalysisStructure.PNG)

## Project Overview
This project demonstrates a complete data analytics pipeline leveraging AWS services to process, query, and visualize data. The pipeline integrates Python, AWS S3, AWS Glue, AWS Athena, and AWS QuickSight to build a seamless workflow for extracting insights from raw data.

## Workflow
1. **Data Preparation with Python**  
   Raw data is processed using Python and uploaded to Amazon S3 for storage.  

2. **Data Transformation with AWS Glue**  
   AWS Glue is used to create ETL (Extract, Transform, Load) scripts that clean and transform the data for analysis.

3. **Cataloging with AWS Glue Data Catalog**  
   Transformed data is registered in the AWS Glue Data Catalog for seamless integration with Athena.

4. **Data Querying with AWS Athena**  
   AWS Athena is used to perform SQL-like queries on the processed data stored in S3.

5. **Data Visualization with AWS QuickSight**  
   Insights generated from Athena queries are visualized in AWS QuickSight to create interactive dashboards and reports.

## Key Features
- Automated ETL process using AWS Glue.  
- Serverless SQL querying with AWS Athena.  
- Scalable and interactive dashboards in AWS QuickSight.  

## Benefits
- Fully serverless and highly scalable architecture.  
- Cost-efficient querying and visualization tools.  
- Real-time insights into data with minimal operational overhead.

---

> **Note:** Replace `path/to/your/image.png` with the actual file path or URL of your diagram.
