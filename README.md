# Web Application Boilerplate Code


# RMIT COSC2299 SEPT Major Project

# Group Information

## Group-P7-05

## Members
* Lakindu Bandara Dissnayake (s3847576)
* Vishwas Aggarwal (s3859098)
* Xuan Tuan Kiet Trinh (s3873634)
* Kushagra Baghel (s3882120)
* Ahnaf Tausif (s3890097)
* Huynh Pham (s3946066)

## Records

* Github repository: https://github.com/cosc2299-sept-2023/team-project-group-p07-05
* Github Project Board : https://github.com/orgs/cosc2299-sept-2023/projects/50/views/1
* Milestone 2 Video Link - https://rmiteduau-my.sharepoint.com/:v:/r/personal/s3882120_student_rmit_edu_au/Documents/GROUP-P7-05%20COSC2299-23s2%20Milestone%202%201.mp4?csf=1&web=1&e=eCmhnf&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19
* Milestone 3 Video Link - https://rmiteduau-my.sharepoint.com/:v:/r/personal/s3882120_student_rmit_edu_au/Documents/GROUP-P7-05%20COSC2299-23s2%20Milestone%203.mp4?csf=1&web=1&e=4JHhZh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19
	
## Code documentation - Release 0.1.0 - date
* feature 1 - Search Bar
* feature 2 - Product Display
* feature 3 - Log in
* feature 4 - Sign Up
* feature 5 - Check out
* feature 6 - Order history
  

# Run Instructions

MILESTONE 2(To run our project, first install mySQL on the system. Install mySQL workbench and create a connection with a username and password.
Open our project and go to application.properties and change the spring.datasource.username and spring.datasource.password to the username and password that you have set before in the mySQL workbench
Run the superPrice Application in the backend folder and then run the homepage.html in the frontend folder.
Type any one of the following products (milk,apple,bread,banana,cheese,beef,eggs,chicken,fish,rice) in the search bar as these are the only items we have in our database in the current implementation.)


FOR THE FINAL IMPLEMENTATION
# Initial Setup

## Setup your environment 
You will need to have in your system

- Java 17.0 or higher
- Node and npm
- Apache Maven
- IDE or Editor

Other tools will be required to complete the project (e.g., Docker)

**Instructions to run the program(without docker):**
- Start the superPriceApplication.properties file to start the back end and to populate the database.
- On the terminal cd into the frontend file
- run the following commands:
- "npm install"
- "npm run build"
- "npm run dev"
- Go to localhost:3000 to see the deployed website

**Instructions to run the program(with docker):** (IMPORTANT NOTE: AFTER BUILDING THE PROGRAM THE FIRST TIME, IT WILL FAIL TO RUN. WHEN IT FAILS, PLEASE PUT IN THE BUILD COMMAND AND RUN IT AGAIN)
- cd into the backend/superprice/ file
- run the command "docker build --platform linux/amd64 -t springboot-docker-testbackend ." in the terminal
- cd into the frontend/ file
- run the following command on the terminal : "docker build --platform linux/amd64 -t springboot-docker-testfrontend ."
- cd into the root directory
- run the following command : "docker-compose build"
- then after it is finished building put in the following command: "docker-compose -f docker-compose-mysql.yml --env-file compose-vars.env up"
- after it runs go to localhost:3000 to see the deployed website

To run the docker-compose-ecr.yml file:
- cd into the root directory
- enter the following command on the terminial : "docker-compose -f docker-compose-ecr.yml --env-file compose-vars.env up"



  






