# Data-Driven Strategies for Boosting Customer Retention via ATM Performance Optimization

![Atm_pic.jpeg](Atm_pic.jpeg)

---
## Introduction

In today's dynamic banking landscape, customer retention has emerged as a critical metric defining the success of financial institutions. Recognizing the pivotal role of Automated Teller Machines (ATMs) as key touchpoints, facilitating essential banking transactions, we are embarking on a strategic Business Intelligence and Data Analytics project.

This initiative is driven by the imperative to harness data-driven strategies aimed at optimizing ATM performance, with a direct focus on enhancing customer retention rates. By employing sophisticated data analytics techniques, our objective is to glean actionable insights into customer behavior patterns, thereby enabling us to enhance operational efficiency and cultivate enduring customer relationships.

**_Through this project, we aim to delve deeper into the wealth of data available to us, utilizing advanced analytical tools and methodologies to unlock valuable insights. By doing so, we position ourselves to not only adapt to the evolving banking landscape but also to thrive by delivering enhanced customer experiences and sustained business growth._**

![Data_analyst_board.jpeg](Data_analyst_bpard.jpeg)

## Objectives
---
In the modern financial landscape, customer retention has become a crucial focus for banks aiming to thrive amidst stiff competition. Our project leverages data analytics and a customer-centric approach to empower financial institutions with the insights and tools needed to bolster customer loyalty. By optimizing ATM performance, banks not only enhance operational efficiency but also cultivate a superior customer experience, fostering lasting relationships and positioning themselves for sustained success.

- Identify Factors Affecting Customer Retention: I Analyze transaction data and gather customer feedback to identify factors influencing customer retention. Key metrics use includes transaction success rates, wait times, and overall customer experience.

- Analyze ATM Usage Patterns: I Delve into patterns of ATM usage to uncover peak hours, popular days, and seasonal trends by Understanding customer engagement with ATMs is critical to optimizing service availability and ensuring customer satisfaction.

- Evaluate ATM Performance: Assessing the performance of individual ATMs and conduct comparisons across different locations. I Identify areas for improvement to prioritize resource allocation and enhance overall ATM performance.

- Optimize ATM Servicing and Maintenance: Evaluate existing maintenance schedules and analyze their correlation with ATM performance metrics. I Optimize servicing procedures to minimize 
  downtime and disruptions. This proactive approach ensures that your ATMs are always operational, enhancing the customer experience.

- Detect Fraudulent Activities: This project includes Implement robust fraud detection analysis to identify and mitigate potentially fraudulent activities. Safeguard customer trust and      mitigate financial risks by proactively detecting and addressing fraudulent behavior.


## Tools use
---
 - Microsoft SQL Server
 - Microsoft Power BI Desktop
 - Microsoft Fabric to efficiently manage and analyze data. The primary data source for this project is the datakliq_education_hub specifically, their Cohort 3 project dataset.

## Dataset Description:

The dataset consists of multiple dimension tables and one fact table, providing comprehensive information for analyzing ATM transactions across various states in Nigeria.

1. Customer Table: Contains details about customers, such as customer ID, name, address, and contact information. This table helps identify the individuals involved in ATM transactions.
2. ATM Maintenance Table: Includes information regarding ATM maintenance activities, such as maintenance schedules, service dates, and maintenance types. This table enables tracking of maintenance operations performed on ATMs.
3. Calendar Table: Provides a calendar of dates, including days, months, and years. This table facilitates time-based analysis of ATM transactions, allowing for insights into transaction patterns over different time periods.
4. ATM Location Table: Contains geographical data about ATM locations, including the state, city, and specific location names. This table helps identify the physical locations of ATMs across different states in Nigeria.
5. Hour Table: Specifies hours of the day, ranging from 0 to 23, to denote different time slots. This table enables analysis of transaction volumes and patterns based on the time of day.
6. Transaction Type Table: Describes various types of transactions that can occur at ATMs, such as cash withdrawals, balance inquiries, and fund transfers. This table categorizes transaction activities for further analysis and classification.
7. Transaction Table (Fact Table): The central table containing detailed information about ATM transactions across five different states in Nigeria, namely Lagos, Enugu, FCT (Federal Capital Territory), Rivers, and Kano. Each transaction record includes data such as transaction ID, transaction timestamp, customer ID, ATM location, transaction type, and transaction amount. This fact table serves as the primary source for analyzing transactional data and deriving insights into ATM usage patterns, customer behavior, and performance metrics across different states.

## Data Dictionary

The data dictionary is a valuable resource that offers clear explanations for the structure of tables and columns in our dataset. It provides concise definitions to help understand the organization and meaning of the data, facilitating our data analysis efforts.

## Data Transformation

Most data transformation tasks were conducted using Microsoft SQL Server. These processes involved various operations such as:

1. Appending Data:  Combining or appending data from multiple sources to create comprehensive datasets.

2. Generating New Calendar Tables: Creating new calendar tables to facilitate time-based analysis and reporting.

3. Creating Bridge Tables: Developing bridge tables to establish relationships between different tables, such as linking the transaction table with the maintenance table.

4. Utilizing Alter and Update Functions: Employing the alter and update functions to modify specific tables, allowing for adjustments and enhancements as needed.

These transformation processes were essential for preparing the data for analysis and ensuring its integrity and relevance for our project objectives.

## Data Modelling

Snowflake Model Implementation: I implemented the snowflake model to connect all my facts and dimensions seamlessly. This model organizes data into a structured hierarchy, with the central fact table surrounded by multiple related dimension tables. By utilizing this model, I ensured efficient data organization and simplified analysis workflows.

Import Storage Mode in Power BI: To bring my data into Power BI, I used the import storage mode. This mode allows for faster data retrieval and analysis by loading the entire dataset into memory. It enables seamless interaction with the data and facilitates real-time insights.

Establishing Relationships : In Power BI, I established relationships between various tables to enable smooth data integration and analysis. Most of these relationships have a many-to-one cardinality, indicating that multiple records from the dimension tables can relate to a single record in the fact table. Additionally, a single filter direction was applied to ensure consistent filtering across related tables, enhancing the coherence and accuracy of the analysis.


## Analysis And Visualization 
1. Total Transactions and Record Month: Over a comprehensive two-year analysis spanning 2020 to 2021, a total of 6.52 million ATM transactions were recorded May 2021 emerged as a       
      noteworthy month, setting a record, indicating potential economic or seasonal influences during that period

2. Total Transaction Amount: The total transaction amount over the two-year period amounted to 111.07 billion naira.

3. Transaction Type Distribution: Withdrawals accounted for most transactions at 34.99%, followed by transfers (24.1%), balance inquiries (20.46%), and deposits (20.45%).

4. Cardholder Transaction: Skilled population emerged as the leaders in transactions, totaling 38,139,56 transactions, with an average waiting time of 1.23 minutes.

5. Geographical Distribution: Lagos led in total transaction amount at 44 billion naira, followed by Enugu (21 billion), Rivers (20 billion), Kano (17 billion), and Abuja (9 billion).        Among individual ATMs, Lekki stood out with the highest traffic, recording 3.2 billion naira in transactions, while Garki Recorded the lowest traffic with 1.1 billion naira

6. Efficiency and Waiting Times:- Analysis revealed discrepancies in ATM efficiency, with some exhibiting an average customer waiting time as low as 1.23 minutes, while others extended       up to 9.55 minutes.

7. Maintenance Analysis: In 2021, a maintenance analysis revealed well-maintained ATMs such as Abakpa, Apapa, Lekki, Eleme, Dala, Maitama, and Nkanu, with 5–4-star ratings.  Conversely,     ATMs with lower maintenance ratings included Bonny, Ahoda, Gokana, Surulere, Tarauni, Ungogo, and Udi, with 0–3-star ratings.

Optimization Strategies The analysis emphasizes the importance of enhancing maintenance for less-maintained ATMs and prioritizing those located in skilled environments.  Advocates for adopting data-driven optimization strategies to improve customer experiences and overall efficiency in the realm of ATMs.



## Recommendation

Develop comprehensive maintenance efficiency metrics by setting benchmarks for response time, error rates, and success rates. Regularly monitor these metrics and implement targeted improvements to ensure optimal ATM reliability and user satisfaction.

Implement dynamic location-specific strategies by leveraging data analytics to identify trends and patterns in high-traffic areas like Lekki. Consider innovative solutions such as partnerships with local businesses or community events to attract users to lower-traffic areas like Garki, thereby increasing overall ATM utilization and revenue.

Utilize performance ratings to guide resource allocation and prioritize service enhancements in regions with higher performance ratings, such as Lagos. By focusing efforts in these areas, we can maintain and further elevate overall system performance, enhancing the overall customer experience.

Develop tailored marketing and service plans for different professional categories, including skilled, semi-skilled, and student demographics. Utilize customer segmentation techniques to identify unique preferences and behaviors within each category, allowing for personalized promotions and services that maximize customer engagement and satisfaction.





