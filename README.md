Team Members 
1)Akash P(Team leader)
2)Aravinth M
3)Kingston I
4)Dilli Babu D
Flight Booking System for Airlines (Java Web Application) ✈️
views Open Source Love svg1 GitHub Forks GitHub Issues contributions welcome

A fully responsive web-based Flight Booking System for Turkish Airlines based on the Model View Controller (MVC) Architecture made using Java Servlets, Java Server Pages (JSPs). Moreover authentication and authorization for users is implemented using Tomcat Roles. The web-application is also secured against SQL Injection and Cross-Site Scripting attacks.

Technologies Used
Frontend: HTML, CSS, JavaScript, Jquery, Bootstrap, Java Server Pages (JSPs), AJAX (for a Flight Search Widget)
Backend: Java Servlets, Java Models, Microsoft Access (Database)
Webservices: SOAP Web Services (to get price and number of seats)
Security Features: SQL Injection, Cross-Site Scripting (XSS), Tomcat Roles
Roles
Following roles are implemented:

Airline Admin
Airline Manager
Customer
Workflow (Functionalities)
This is for just one airline who wants to sell seats to their customers via internet.

Following are the steps of work flow:

Airline Admin will set the prices of the seats. There should be three types of seats:
First Class
Business
Economy
The Airline Admin should be able to create and update the features of each type of seat.
The Airline Admin should be able to set the total number of seats for each flight.
Airline Manager should see a list of seats which the Admin has added or edited when he/she logs in.
Airline Manager then needs to approve the new price or updates.
When the price and update is approved by the manager only then it should be available for the customer to buy.
The Customer should be able to buy seats based on availability.
When a customer buys a ticket the system should be able to calculate how many seats are left. If all seats are bought the application should not let the customers buy more seats.
The Customer should be able to select the following, to select a seat:
origin and destination cities
dates of travel
number of people traveling
When the customer selects the seat and confirms the booking flight Itinerary should be shown to the customer.
When the customer approves the itinerary the customer should be taken to a payment page where the total price should be shown. When the customer presses the pay button consider the transaction done and mark the seat sold.
Once the seat is sold, send out an email to the customer with the flight itinerary.
