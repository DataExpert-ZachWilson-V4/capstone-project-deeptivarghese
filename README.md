[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/1lXY_Wlg)
Capstone Project Proposal:

The Amazon data set is a free streaming dataset which has several GB of data, hence was selected for the capstone
The technologies were mostly selected for learning purposes.
Steps of the project:
1.	Extract real time Amazon data from https://rapidapi.com/letscrape-6bRBa3QguO5/api/real-time-amazon-data
2.	Load data into AWS S3
3.	Use Kafka to stream data from S3 to dbt
4.	Transform using dbt 
5.	Load transformed data to S3
6.	Create Tableau Dashboard
7.	Orchestrate with Airflow in Docker
   
Conceptual Data Model:

![image](https://github.com/DataExpert-ZachWilson-V4/capstone-project-deeptivarghese/assets/31417684/6327726c-4070-4c00-912b-7ec92118d631)

 
Output:
Live tableau dashboard that refreshes on a daily cadence and displays 
1.	products with max reviews, 
2.	top rated products, 
3.	products marked as best sellers, 
4.	products with best deals and corresponding savings (discount %), 
5.	new products added under each category etc.


 



