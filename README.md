ExpediaApp
==========

To install the application on local server please follow steps given below:-
1. Clone the application
2. go to root directory
3. Run mvn clean install command
4. hit target\bin\webapp.bat
5. browse localhost:8080 in the browser
6. select hotel city and hotel class


About Application:-
Application displays the hotels based on the selected city and hotel class. Application shows the hotel deals by taking summation of movingAverageScore,rawAppealScore,relevanceScore,starRating,guestRating into account.

It displays the original price per night and discouunted price per night.

Application is deployed on Heroku

https://expediaapp.herokuapp.com/

Known Bugs:-
Checkin Date and Checkout Date is shown on UI but no implementation has been done.

Technologies Used :-
JAVA, Tomcat, Spring MVC, JSON, JQuery, Maven

Thought process:-
To keep the application quite simple and make use of maximum technologies, basically developed a framework whether more functionality can be added.




