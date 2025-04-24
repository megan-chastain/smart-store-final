# smart-store-final
BI Final Project
This project will demonstrate how to effectively analyze data for a business goal.

1. Business Goal:
I want to know what the top product at the lowest revenue store is.

2. Data Sources:
I will use data collected from the course that includes customer data, product data, and sales data.

Customers_data.csv

Sales_data.csv

Product_data.csv

3. Tools:
I will use VS Code, Python, SQL, and PowerBI to analyze the data.

4. Workflow and Logic:
4.1 VS Code:
I will use VS Code to set up my workspace. I will clone a GitHub repository where my project will be located.

git clone https://github.com/megan-chastain/smart-store-final

I will add basic data files in .csv format:

Customers_data.csv

Products_data.csv

Sales_data.csv

I will add requirements.txt and .gitignore to finish setting up what my workspace will need to create a data warehouse.

I will create and activate a virtual environment.

py -m venv .venv

.venv\Scripts\Activate

I will prepare and clean the data from its raw form to a prepared form using a data scrubber script. When the data is neat, with no outliers, no repeat entries, and no empty spaces, I will add it to a data warehouse.

First, I will create the warehouse using a script:

Py Scripts\create_dw.py

Then, I will add my cleaned and prepared data to the data warehouse with a script that uses SQLite:

Py Script\etl_to_dw.py

If everything works correctly, tables should populate.
BI Final Project
This project will demonstrate how to effectively analyze data for a business goal.

1. Business Goal:
I want to know what the top product at the lowest revenue store is.

2. Data Sources:
I will use data collected from the course that includes customer data, product data, and sales data.

Customers_data.csv

Sales_data.csv

Product_data.csv

3. Tools:
I will use VS Code, Python, SQL, and PowerBI to analyze the data.

4. Workflow and Logic:
4.1 VS Code:
I will use VS Code to set up my workspace. I will clone a GitHub repository where my project will be located.

git clone https://github.com/megan-chastain/smart-store-final

I will add basic data files in .csv format:

Customers_data.csv

Products_data.csv

Sales_data.csv

I will add requirements.txt and .gitignore to finish setting up what my workspace will need to create a data warehouse.

I will create and activate a virtual environment.

py -m venv .venv

.venv\Scripts\Activate

I will prepare and clean the data from its raw form to a prepared form using a data scrubber script. When the data is neat, with no outliers, no repeat entries, and no empty spaces, I will add it to a data warehouse.

First, I will create the warehouse using a script:

Py Scripts\create_dw.py

Then, I will add my cleaned and prepared data to the data warehouse with a script that uses SQLite:

Py Script\etl_to_dw.py

If everything works correctly, tables should populate.

![image](https://github.com/user-attachments/assets/6e631cb4-30db-4fc8-af02-3c2a903b41e0)
![image](https://github.com/user-attachments/assets/a5e865ba-2bc2-4095-8f9c-0f8caa1b6326)
![image](https://github.com/user-attachments/assets/89cf9e99-3342-41cc-af1a-b36acc9ad7e3)

I will use git commit -m, git add ., and git push -u origin main to save and update my work to the github repository.

4.2 PowerBI:
PowerBI is how I will visualize my data. I have to create a DSN to link what I did in VS Code to PowerBI. I will use M code to create data tables to help visualize the data analysis.

The descriptive dimensions I will use are product ID and store ID. The numeric metric I will use is sale amount. A bar graph will help me identify both the lowest revenue store and the top product at that store.

5. Results:
What I've found is that store 403 had the lowest revenue for the duration of the collected data. At that store, product 101, or laptops, had the most sales revenue. I sliced and diced the data by total spent for each product and store.

![image](https://github.com/user-attachments/assets/20882356-cf08-4610-96e3-c28068e4bbd9)

![image](https://github.com/user-attachments/assets/bd700a46-b268-4b42-bbb7-98a329ab78ec)


6. Suggested Business Action:
What I've found is that store 403 had the lowest revenue for the duration of the collected data. At that store, product 101, or laptops, had the most sales revenue. I would suggest this store try focusing on selling more electronics to boost sales; however, it might be best to reduce staff and/or stop selling product 103 (cable) and 106 (controller).

7. Challenges:
I found getting everything to follow the correct pathway in VS Code a challenge. Also, writing the M code in PowerBI. AI helped quite a bit to solve these issues.

8. Ethical Considerations:
Collecting data over a longer period of time would always be better, but a year is sufficient to calculate store performance. Hopefully, reducing employees does not create hardships, and closing a store does not create a desert in that location. It's important to view how the customers will be affected by changes to business plans.
4.2 PowerBI:
PowerBI is how I will visualize my data. I have to create a DSN to link what I did in VS Code to PowerBI. I will use M code to create data tables to help visualize the data analysis.

The descriptive dimensions I will use are product ID and store ID. The numeric metric I will use is sale amount. A bar graph will help me identify both the lowest revenue store and the top product at that store.

5. Results:
What I've found is that store 403 had the lowest revenue for the duration of the collected data. At that store, product 101, or laptops, had the most sales revenue. I sliced and diced the data by total spent for each product and store.

6. Suggested Business Action:
What I've found is that store 403 had the lowest revenue for the duration of the collected data. At that store, product 101, or laptops, had the most sales revenue. I would suggest this store try focusing on selling more electronics to boost sales; however, it might be best to reduce staff and/or stop selling product 103 (cable) and 106 (controller).

7. Challenges:
I found getting everything to follow the correct pathway in VS Code a challenge. Also, writing the M code in PowerBI. AI helped quite a bit to solve these issues.

8. Ethical Considerations:
Collecting data over a longer period of time would always be better, but a year is sufficient to calculate store performance. Hopefully, reducing employees does not create hardships, and closing a store does not create a desert in that location. It's important to view how the customers will be affected by changes to business plans.
