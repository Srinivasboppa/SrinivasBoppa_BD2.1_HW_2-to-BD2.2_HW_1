BD2.2 HW-1
Steps to follow:

Create a new Repl and rename it as <YourName_[Ex Name]>. 

Choose NodeJS as your template. 

In the file named “index.js”, write the code to solve the following tasks.

Question 1:

Write an Express code snippet to filter temperatures above 25 degrees Celsius.

Define an endpoint /high-temperatures using the get method.

Implement a function filterHighTemperatures that returns true if the temperature is above 25 degrees Celsius.

Inside the endpoint, use the filter method to filter temperatures above 25 degrees Celsius.

Send the filtered temperatures as a JSON response.

Given Data: [22, 26, 19, 30, 23, 28, 17, 31]

API Call: <http://localhost:3000/high-temperatures>

Expected Output: [26, 30, 28, 31]

Answer: 
![image](https://github.com/user-attachments/assets/a3b80584-065c-4948-a849-7c75024636b2)
Question 2:

Write an Express code snippet to filter prices less than or equal to 100 rupees.

Instructions:

Define an endpoint /low-prices using the get method.

Implement a function filterLowPrices that returns true if the price is less than or equal to 100.

Inside the endpoint, use the filter method to filter prices less than or equal to 100.

Send the filtered prices as a JSON response.

Given Data: [80, 120, 95, 150, 60, 110]

API Call: <http://localhost:3000/low-prices>

Expected Output: [80, 95, 60]

Answer: 
![image](https://github.com/user-attachments/assets/ace08ca8-7f32-4d0e-b1c2-11abcba2146f)
Question 3:

Write an Express code snippet to filter product ratings greater than 3.5.

Instructions:

Define an endpoint /high-ratings using the get method.

Implement a function filterHighRatings that returns true if the rating is greater than 3.5.

Inside the endpoint, use the filter method to filter product ratings greater than 3.5.

Send the filtered ratings as a JSON response.

Given Data: [4.2, 3.8, 2.5, 4.7, 3.0, 4.9, 3.6]

API Call:<http://localhost:3000/high-ratings>

Expected Output: [4.2, 3.8, 4.7, 4.9, 3.6]

Answer:
![image](https://github.com/user-attachments/assets/695dea33-c017-438d-8d6b-c6aba69544cd)
Question 4:

Write an Express code snippet to filter Indian names longer than 6 characters.

Instructions:

Define an endpoint /long-indian-names using the get method.

Implement a function filterLongIndianNames that returns true if the name length is greater than 6 characters.

Inside the endpoint, use the filter method to filter Indian names longer than 6 characters.

Send the filtered names as a JSON response.

Given Data: ['Akshay', 'Priyanka', 'Arjun', 'Anushka', 'Rajesh', 'Kavita']

API Call: <http://localhost:3000/long-indian-names>

Expected Output: ['Priyanka', “Anushka“]

Answer:
![image](https://github.com/user-attachments/assets/8826e721-0d1e-4efc-8515-86ac7fc2471e)
Question 5:

Write an Express code snippet to filter products cheaper than a certain price.

Instructions:

Define an endpoint /cheaper-products using the get method.

Implement a function filterCheaperProducts that takes a query parameter filterParam and returns true if the product price is less than the provided parameter.

Inside the endpoint, extract the query parameter filterParam and use it to filter products cheaper than that price.

Send the filtered products as a JSON response.

Given Data: [10, 25, 50, 75, 100, 150, 200]

API Call: http://localhost:3000/cheaper-products?filterParam=100

Expected Output: [10, 25, 50, 75]

Answer:
![image](https://github.com/user-attachments/assets/d6fca95e-cee3-4ffd-915b-4317c237bb93)





