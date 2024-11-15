Team Members 
1)Akash P(Team leader)
2)Aravinth M
3)Kingston I
4)Dilli Babu D


# Flight Booking System for Airlines (Java Web Application) ✈️ 


<a><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=harismuneer&style=flat-square" width="125"/></a>
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Flight-Booking-System-JavaServlets_App.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/Akash8300/Flight-Booking_App_NM/edit/main/README.md)
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Flight-Booking-System-JavaServlets_App.svg?style=flat&label=Issues&maxAge=2592000)](https://github.com/Akash8300/Flight-Booking_App_NM/edit/main/README.md)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)


A **fully responsive** web-based Flight Booking System for Turkish Airlines based on the **Model View Controller (MVC) Architecture** made using **Java Servlets**, **Java Server Pages (JSPs)**. Moreover authentication and authorization for users is implemented using Tomcat Roles. The web-application is also secured against **SQL Injection** and **Cross-Site Scripting** attacks.

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript, Jquery, Bootstrap, Java Server Pages (JSPs), AJAX (for a Flight Search Widget)
* **Backend:** Java Servlets, Java Models, Microsoft Access (Database)
* **Webservices:** SOAP Web Services (to get price and number of seats)
* **Security Features:** SQL Injection, Cross-Site Scripting (XSS), Tomcat Roles

## Roles
Following roles are implemented:
* Airline Admin
* Airline Manager
* Customer

## Workflow (Functionalities)

This is for just one airline who wants to sell seats to their customers via internet. 

Following are the steps of work flow:
1.  Airline Admin will set the prices of the seats. There should be three types of seats:
    *    First Class
    *    Business
    *    Economy
2.  The Airline Admin should be able to create and update the features of each type of seat. 
3.   The Airline Admin should be able to set the total number of seats for each flight.
4.   Airline Manager should see a list of seats which the Admin has added or edited when he/she logs in.
5.   Airline Manager then needs to approve the new price or updates.
6.   When the price and update is approved by the manager only then it should be available for the customer to buy.  
7.   The Customer should be able to buy seats based on availability.
8.   When a customer buys a ticket the system should be able to calculate how many seats are left. If all seats are bought the application should not let the customers buy 
more seats. 
9.   The Customer should be able to select the following, to select a seat:
      *    origin and destination cities
      *    dates of travel
      *    number of people traveling
10.   When the customer selects the seat and confirms the booking flight Itinerary should 
be shown to the customer. 
11.   When the customer approves the itinerary the customer should be taken to a payment page where the total price should be shown. When the customer presses 
the pay button consider the transaction done and mark the seat sold. 
12.   Once the seat is sold, send out an email to the customer with the flight itinerary.

## Interface

#### Home Pages
<p align="middle">
   <img src="Images/main.png" width="400"/>
   <img src="Images/main2.png" width="400"/>
</p>

#### Login Page and Book Flight
<p align="middle">
   <img src="Images/login.png" width="400"/>
   <img src="Images/book.png" width="400"/>
</p>

#### Current Bookings and Itinerary
<p align="middle">
   <img src="Images/current.png" width="400"/>
   <img src="Images/itenary.png" width="400"/>
</p>

#### Seat Features and Approval
<p align="middle">
   <img src="Images/features.png" width="400"/>
   <img src="Images/approve.png" width="400"/>
</p>


## How to Run

1- Install these:
 * [Java SE Development Kit 8 (JDK 8)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
 * After installing JDK 8, install [NetBeans IDE](https://netbeans.org/downloads/) with **all** the features including **Tomcat Apache Server.** 

2- Open Netbeans IDE and go to Services > Servers > Apache Tomcat. Right click "Apache Tomcat" and select Properties. Copy the **Catalina Base Path** and open it. Open the "conf" folder and then the "**tomcat-users.xml**" file there. Copy the following lines and paste them in the tomcat-users.xml file before closing tag </tomcat-users>

```
<role rolename="Manager"/>
<role rolename="Admin"/>
<role rolename="Customer"/>

<user username="akash@admin.com" password="a" roles="Admin"/>
<user username="aravinth@manager.com" password="m" roles="Manager"/>
<user username="kingston@customer.com" password="c" roles="Customer"/>
```

<p align="middle">
   <img src="Images/tomcat.png" width="400"/>
   <img src="Images/tomcat-users-xml.png" width="400"/>
</p>

Morever, open and read the file. Only the users authenticated in this file are allowed to login and use the Booking System. Use above mentioned credentials to login through the Login Page.

3- Restart NetBeans IDE. Click on File -> Open Project and browse to the downloaded folder named "Project". There will be two projects there "Turkish Airlines" and "WSTester" (which is basically a project to test the Web Services). Select both and open them.
Both projects will be loaded. Now first run the Turkish Airlines project, then to test the web services run WSTester project. 



<br>
<hr>


### Creator of <a href="https://github.com/harismuneer/Ultimate-Facebook-Scraper">Ultimate Facebook Scraper</a> (one of the best software to collect Facebook data for research & analysis) 



## 🤝 Consulting / Coaching
Stuck with some problem? Need help in solution development, guidance, training or capacity building? I am a Full Stack Engineer turned Project Manager with years of technical and leadership experience in a diverse range of technologies and domains. Let me know what problem you are facing at <b>aravinthm6382@gmail.com</b> and we can schedule a consultation meeting to help you get through it.

## 👨‍💻 Technical Skills & Expertise

- Development of Web Applications, Mobile Applications, and Desktop Applications
- Development of Machine Learning/Deep Learning models, and deployment 
- Web Scraping, Browser Automation, Python Scripting
<hr>



## ❤️ Support / Donations
If you or your company use any of my projects, like what I’m doing or have benefited from my projects in any way then kindly consider backing my efforts.

For donations, you can follow these simple steps:

<b>1)</b> Free signup at <b>[TransferWise](https://transferwise.com/invite/u/akash)</b> using this link: https://transferwise.com/invite/u/akash</li>. (Signing up through this link will save you from any transcation fee on the donation)

<b>2)</b> Select the amount e.g (15$) and choose the receiving/recipient's currency to be PKR. It supports multiple payment options (credit card, debit card, wire transfer etc)

<b>3)</b> Then it will show my info as the recipient, select it. If my name isn't shown, then type my email akash78@gmail.com in recipients.

<b>4)</b> Choose the reason for transfer to the one that suits you the most (in this case it could be 'General expenses') and in the reference section, you can mention 'Support'
 
If you face any issue in sending donation then feel free to get in touch with me at aravinthm6382@gmail.com
Thank you for your contribution!



## Contributions Welcome
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)

If you find any bug in the code or have any improvements in mind then feel free to generate a pull request.

## Issues
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Flight-Booking-System-JavaServlets_App.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Flight-Booking-System-JavaServlets_App/issues)

If you face any issue, you can create a new issue in the Issues Tab and I will be glad to help you out.

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2024-present, Aravinth,Akash,Kingston,Dilli Babu                                                      
