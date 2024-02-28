# Students-Details_REST_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/28551469/2s9XxtyvzB


## Test case list:
1. ### Create Student
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Student Details
	> Get all the students details.And In the test case you need to validate the following field values:
 	1.  >Only Message 

3. ### Verify a Specefic Student Details
	> In the test case you need to validate the following field values:
   1. > Id
   2. > First Name 
   3. > Middle Name 
   4. > Last Name 
   5. > Date of Birth 
 	

4. ### Create Technical skills 
	> In the test case you need to validate the following field values:
	1. > Only Message

5. ### Create a Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Get the Student's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth
	5. > Language
	6. > Year Of Experience
	7. > Last Used Date
	8. > House Number
	9. > City
	10. > State
	11. > Country
	12. > Std Code
	13. > Home Address
	14. > Mobile


