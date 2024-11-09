Rest Booking API Testing with Postman Newman
This project demonstrates API testing using Postman, providing a collection of tests to validate various endpoints of the API.

Features :
Tests for GET, POST, PUT, DELETE requests
Collection of tests covering different API endpoints
Environment setup for easy switching between environments
Pre-request scripts for data setup
Test scripts for assertions and validations
API Documentation:
https://documenter.getpostman.com/view/38812065/2sAY4yeLvT#327fa795-7665-4483-a841-290a54b5d995
Technology used:
Postman
Newman
Prerequisite:
Node Js
Newman
Newman Html Report Library
Installation
Postman: If you haven't already, download and install Postman.
Clone the repository:
 git clone https://github.com/Tahsan-sourov1997/Rest-Booking-Api-testing-project.git
Import the Postman collection:
Open Postman.
Click on the Import button.
Select the file from the repository.
Import the Postman environment:
In Postman, click on the gear icon in the top right corner.
Select Import and choose the file.
Newman and Report Installation Process:
Newman Install Command:
 npm install -g newman
Newman Html Report Install Command:
 npm install -g newman-reporter-htmlextra
Usage
Select Environment:
In Postman, select the appropriate environment (e.g., Development, Production) from the top-right dropdown.
Run Collection:
Select the imported collection from the Collections sidebar.
Click on the Runner button to open the collection runner.
Select the desired environment.
Click Start Test to run the collection.
View Results:
Once the tests are complete, view the results in the Runner tab.
Detailed test results can be viewed for each request.
Screenshot of report :
![image](https://github.com/user-attachments/assets/f71c95b4-2686-453f-9b2b-43099d270823)

