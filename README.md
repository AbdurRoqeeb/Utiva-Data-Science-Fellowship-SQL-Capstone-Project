# Exploratory Data Analysis in Postgresql.
----
## Introduction
This project is an exploratory analysis of International Breweries Data in West Africa between 2017 and 2019. It is the castone project of the SQL section of [Utiva](https://utiva.io/) Data Science Feloowship programme.

----
## Project Requirement
The requirement is to carry out
- Profit analysis
- Brand analysis and
- Countries analysis.
The goal of this exploratory analysis is to help the company in making better decisions in order to maximize profit and reduce loss to the lowest minimum.

----
## Data Sourcing and Importating into Postgresql
The dataset was provided by Utiva for the purpose of the project and it is in .csv format. The dataset can be accessed [here](https://drive.google.com/file/d/11riatqD-uRa98TsCk2xqOBnlr3rzxsS_/view)

Before importing into pgadmin, a table was created in the database with the syntax below:
![image](https://user-images.githubusercontent.com/101981141/179999642-886aa394-edd1-4528-ab39-1ea8dea971b3.png)

The dataset was then imported into the table created
![image](https://user-images.githubusercontent.com/101981141/180005280-42f6c3b1-2ed5-4e9a-b668-cacd0ff55fa0.png)

A quick look at the table after importing
![image](https://user-images.githubusercontent.com/101981141/180000502-5244e943-0ef1-43b3-822a-b56c3fa15278.png)

----
## Exploratory Data Analysis
### Section A: Profit Analysis
#### 1. Within the space of the last three years, what was the profit worth of the breweries, inclusive of the anglophone and the francophone territories?
![image](https://user-images.githubusercontent.com/101981141/180001292-2c3b5fba-436a-416e-83da-b3c17c005851.png)
#### 2.  Compare the total profit between these two territories in order for the territory manager, Mr. Stone made a strategic decision that will aid profit maximization in 2020. 
_For this particular question, a CASE WHEN statement is needed to categorize the countires in West Africa into Anglophone and Francophone._
![image](https://user-images.githubusercontent.com/101981141/180002153-e86889f5-68c0-42c8-972a-17cec04bff96.png)
#### 3. Country that generated the highest profit in 2019
![image](https://user-images.githubusercontent.com/101981141/180002575-0c7caf90-92fb-4ca3-8670-65805f95bdd5.png)
#### 4. Help him find the year with the highest profit. 
![image](https://user-images.githubusercontent.com/101981141/180002950-3ead7216-50d8-4088-8de8-3725b6531e77.png)
#### 5. Which month in the three years was the least profit generated?
![image](https://user-images.githubusercontent.com/101981141/180003447-d5a9564e-83fb-48df-b11f-758ae0b5cdd2.png)
#### 6. What was the minimum profit in the month of December 2018?
![image](https://user-images.githubusercontent.com/101981141/180003902-b282f171-2017-4c99-85e5-9ef8b5787b88.png)
#### 7. Compare the profit in percentage for each of the month in 2019
![image](https://user-images.githubusercontent.com/101981141/180004306-9ccf6b90-75a5-4f37-9d09-3713cd387f5c.png)
#### 8. Which particular brand generated the highest profit in Senegal?
![image](https://user-images.githubusercontent.com/101981141/180004585-c8783022-3d6f-4ab5-8754-e4c54c5da60c.png)

### Section B: Brand Analysis
#### 1. Within the last two years, the brand manager wants to know the top three brands consumed in the francophone countries
![image](https://user-images.githubusercontent.com/101981141/180006390-3a7296a7-e4cd-47bf-8c04-1909752bb4c0.png)
#### 2. Find out the top two choice of consumer brands in Ghana 
![image](https://user-images.githubusercontent.com/101981141/180006589-85c58cb5-dd3b-4228-9323-56594a6d39ed.png)
#### 3. Find out the details of beers consumed in the past three years in the most oil riched country in West Africa.
_The most oil riched country in West Africa is Nigeria_
![image](https://user-images.githubusercontent.com/101981141/180007441-2a5ec06a-5d0d-4efb-b6f8-89bd1239da5a.png)
#### 4. Favorite malt brand in Anglophone region between 2018 and 2019 
![image](https://user-images.githubusercontent.com/101981141/180007795-da8dacfb-9988-4642-88fb-e69012f84211.png)
#### 5. Which brands sold the highest in 2019 in Nigeria? 
![image](https://user-images.githubusercontent.com/101981141/180008050-32e1378a-0653-41d1-aa28-d8f9151511c0.png)
#### 6. Favorite brand in South_South region in Nigeria
![image](https://user-images.githubusercontent.com/101981141/180008431-74db389d-3c59-41a6-ab86-92f416d48203.png)
#### 7. Beer consumption in Nigeria
![image](https://user-images.githubusercontent.com/101981141/180008695-13a12132-ac1d-4dae-a706-58f03a2b1b37.png)
#### 8. Level of consumption of Budweiser in the regions in Nigeria
![image](https://user-images.githubusercontent.com/101981141/180009076-082538c4-60b9-4fc0-937e-66d0f3e7aaf6.png)
#### 9. Level of consumption of Budweiser in the regions in Nigeria in 2019
![image](https://user-images.githubusercontent.com/101981141/180009413-8c01edd7-da0d-4bb0-8825-a96b63d88b65.png)

### Section C: Countries Analysis
#### 1. Country with the highest consumption of beer.
![image](https://user-images.githubusercontent.com/101981141/180010029-b77e90cd-48d5-473c-9620-4b0d28803a4b.png)
#### 2. Highest sales personnel of Budweiser in Senegal
![image](https://user-images.githubusercontent.com/101981141/180010219-32081f08-ef78-47cb-bb75-6106f47d54db.png)
#### 3. Country with the highest profit of the fourth quarter in 2019
![image](https://user-images.githubusercontent.com/101981141/180010444-0b523a85-786d-460d-865a-2f6a59817ee6.png)
