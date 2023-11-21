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
	
## Code documentation - Release 0.1.0 - date
* feature 1
* feature 2
* feature 3
  

# Run Instructions

To run our project, first install mySQL on the system. Install mySQL workbench and create a connection with a username and password.
Open our project and go to application.properties and change the spring.datasource.username and spring.datasource.password to the username and password that you have set before in the mySQL workbench
Run the superPrice Application in the backend folder and then run the homepage.html in the frontend folder.
Type any one of the following products (milk,apple,bread,banana,cheese,beef,eggs,chicken,fish,rice) in the search bar as these are the only items we have in our database in the current implementation.



# Initial Setup

## Setup your environment 
You will need to have in your system

- Java 17.0 or higher
- Node and npm
- Apache Maven
- IDE or Editor

Other tools will be required to complete the project (e.g., Docker)

## Backend

- Delete any unused services (i.e. backend/movies). They are there only for an initial reference.
- Use [Spring initializr](https://start.spring.io/) to create your (micro)services
- Place any new backend service in its own directory (i.e., backend/<service-name>)
- Confirm you can run your applicaiton (./mvnw package && java -jar target/[microservice]-0.0.1-SNAPSHOT.jar)

## Frontend
- cd into frontend/
- Install dependencies "npm install"
- Run the app with "npm run dev"




