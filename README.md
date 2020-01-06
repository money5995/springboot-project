# Getting Started

* This is a spring boot maven based application. Import the project as a Java project into IDE. Run maven clean install.
* To run the application, go to main class 'MainApplication.java' and run it as java application.
* Application will run the tomcat. It runs on port 8081.
* Use Post man to check the working of application. Create a Rest API project in post man.
* Use the URL 'http://localhost:8081/generate-plan' as GET request in post man.
* Create JSON request body '{"loanAmount": "5000","nominalRate": "5.0","duration": 24,"startDate": "2018-01-01T00:00:01Z"}'
* Hit the 'Send' button to see the results on the console.
* Change the request body to see the different results.
