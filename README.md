# lark-health-case-study
Generated a mock dataset of 2000 users to explore analysis, reporting, A/B Testing on realistic data. This case study examines Lark Health - an ai-enabled diabetes and chronic disease management platform. 


## [Mock Data Generator](https://github.com/AlexTeboul/lark-health-case-study/blob/main/Lark_Health_Case_Study_Mock_Data_Generator.ipynb) 

**Output File: [users_ab.csv](https://github.com/AlexTeboul/lark-health-case-study/blob/main/users_ab.csv)**
* In this colab notebook, I create a Users table that seeks to emulate the type of data that might be found at Lark Health. 
* Specifically, I use this notebook to generate 2000 users (male and female) alongside real-world appropriate features like age, height, BMI, a1c, etc.
* The dataset is further split by a cohort column. Cohort A represents a scenario where men are not engaging as much with the features of the app, as indicated by lower total_conversations, total_meals_logged, total_weight_measurements, total_missions_completed, percentage_healthy_meals_consumed, and ultimately a net_promotor_score (How likely you are to recommend the app to someone else on a scale from 1 to 10)

* **Users**
  * userid, name, sex, age, height, start_date, end_date
  * start_weight, goal_weight, end_weight
  * start_BMI, goal_BMI, end_BMI
  * start_BMI_category, goal_BMI_category, end_BMI_category
  * start_a1c, goal_a1c, end_a1c
  * total_conversations
  * total_meals_logged
  * total_weight_measurements
  * total_missions_completed
  * percentage_healthy_meals_consumed
  * net_promoter_score
  * cohort
