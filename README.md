# data-interview-qs
My solutions to the daily problem sets sent via email (free version) by https://www.interviewqs.com/

Questions:
2-19-2020
Suppose you work for a conglomerate that is constantly acquiring new companies. 
You're working with the human resource team to understand how many new employees you're taking on. 
Each of the companies you are acquiring has the following organization structure:

<img src="https://ci6.googleusercontent.com/proxy/213CoF0yNnNQ8lhLU0nYjmZA5Sxj5ScszkMgJ-O4wD2DAfQ3sCvYXZIJC477f98m3VV2TFzH2chzMg=s0-d-e1-ft#https://www.interviewqs.com/q157_p1.png" data-canonical-src="https://ci6.googleusercontent.com/proxy/213CoF0yNnNQ8lhLU0nYjmZA5Sxj5ScszkMgJ-O4wD2DAfQ3sCvYXZIJC477f98m3VV2TFzH2chzMg=s0-d-e1-ft#https://www.interviewqs.com/q157_p1.png" width="100" height="200" />

You can assume that you have all this information in the following table:


Table: allCompanyEmployees

chief_executive_officer | vice_president | director | manager | individual_contributor | company_code
----------------------- | -------------- | -------- | ------- | ---------------------- | ------------
johnny|tammy|lenny|penny|jim|abc
johnny|tammy|lenny|penny|tim|abc
johnny|tammy|lenny|penny|pam|abc
michael|pam|jerry|jimmy|timmy|def


You can also assume that each individual's name is unique in the table for simplicity (similar to an employee ID or user name). 
Given the table, can you write a SQL query to print the 
  1. company_code, 
  1. CEO name (or ID), 
  1. total number of vice presidents, 
  1. total number of directors, 
  1. total number of managers, and 
  1. total number of individual contributors?
