# DmoneyAPI-Jmeter-Project
This is a Jmeter Project where the DmoneyAPI is tested by creating test cases for Login , Creating users , Searching users and also performing Update and Delete operations. The ramp-up and the number of threads were kept as 1.

Steps to run this project:
- Clone this project or download the .jmx file in the project directory.
- You can generate your own HTML summary report by running the following code in the terminal:

````
jmeter -n -t DmoneyAPI.jmx -l DmoneyAPI.csv -e -o Reports

````

# Summary Report
![Statistics_report](https://user-images.githubusercontent.com/10103397/193884787-37aa9f1d-bfb4-446e-a648-3e4999a659e3.png)

## Whole project structure in Jmeter
![project-structure](https://user-images.githubusercontent.com/10103397/193884869-f5657aa4-fa9a-48c9-91a9-17b1e8fded21.png)

## All test cases passed can be viewed from Jmeter result tree:
![Viewing_result_tree](https://user-images.githubusercontent.com/10103397/193884958-4edd69dd-7acb-473d-a2c6-d36a315d62e4.png)

## Summary report in Jmeter
![summary-report](https://user-images.githubusercontent.com/10103397/193885020-800ef053-eb4f-4cbb-84c5-c9b930923c1c.png)
