# Random-User-API-Performance-Test

## Technology and Tool Used
- Apache JMeter
- Java

## Scenerio
Find out the actual TPS for if 120000 user can give load for 12 hour. \
Perform load test on this URL: https://random-data-api.com/api/v2/users
1. You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS (10)

2. Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project
- Clone this project
- Run the .jmx file on jmeter

## Prerequisite
- Java & Jmeter must be installed


## Load & Stress Test Strategy Excel File: 
https://docs.google.com/spreadsheets/d/1uc5QR2TqVggm4Tj9obFHu9KHoB6qU7uY0DXiQ8zbu9w/edit?usp=sharing

## Screenshot of Load Test Strategy Report
![Screenshot (52)](https://user-images.githubusercontent.com/29010350/194127363-13e37d33-355e-4376-acf9-06a7d2543588.png)

## Screenshot of Stress Test Strategy Report
![Screenshot (51)](https://user-images.githubusercontent.com/29010350/194126580-58b36426-2aec-475f-905a-21347faed9a1.png)
