```
                                    KULLIYYAH OF INFORMATION & COMMUNICATION TECHNOLOGY
                                    WEB APPLICATION DEVELOPMENT (INFO 3305), SECTION 3
                                                   SEMESTER 1, 2021/2022
                                   Web Application Proposal: Flight Reservation Website

                                          Hareez Sidqi Bin Mohd Fuad (2015199)
                                        Nik Nurul Fakhriwani bt Nik Azlan (1911480)
                                        Muhammad Naim Imran bin Mohd Nizar (1917173)
                                                  Syahmi Amin (1918793)
                                          Mohammed Sadeq Ahmed Alward (1734825)
                                          
                                          Lecturer: MOHD KHAIRUL AZMI BIN HASSAN

```
## Presentation Link
www.youtube.com/watch?v=VoQxAIEADS8

## Introduction
Air transport has been one of the most demanded modes of transportation in Malaysia. In addition to that, a flight reservation system is crucial, especially in today’s busy world. It is a system that helps in consolidating flight data which include flight schedules, seat availability, flight fares, reservations from different airlines for customers and travel agents to book flight tickets. For this web application development project, our group has decided to develop a flight reservation web application. 

## Objectives
The main objective of this flight reservation application is to ease the flight reservation process for our users. This project is intended for our users and customers who use airline websites to make flight reservations. 

## Features and Functionalities
  In the project, the main objective of the system is to ease the process of booking. Thus, we will create a systematic online booking system that consists of the registration for new users, purchasing the ticket and checking the details of the flight. The system is expected to provide consumers with the ideal experience in booking their flight ticket and for admin to do CRUD operations for the detailed flights available. The system also will be able to store data of the registered users, the available flights in the airports and also the details of the booked tickets. Thus,consumers can view their tickets and flights and make adjustments on their purchases.

Apart from that, we will ensure that the booking system is able to accept the registration of new users and the post method will be implemented in the system to ensure the confidentiality of data for each user.

1. **CREATE** procedures: Performs the INSERT statement to create a new record.
2. **READ** procedures: Reads the table records based on the primary key within the input parameter, which is set ready to view.
3. **UPDATE** procedures: Executes an UPDATE statement on the table based on the specified primary key within the WHERE clause of the statement.
4. **DELETE** procedures: Deletes a specified row in the WHERE clause.
5. The user can view the details of the tickets.


## Model-View-Controller-Routes
### Routes
The function of routes is routing to a particular controller which are the admin and
user controller, and from there the controllers take the place of managing the requests
and directing procedures.

### Controllers
Controllers are the brain of the web application, where they can control which
views to present and deal with the CRUD operations performed by the admin and
communicate with the models to update the database. The admin controller, though it
the web application directing the admin to different views and updates the database.
Also, that happens on the user’s controllers where they handle the requests logic and
present the desired view by using the view global helper. In brief, the controllers are
routed by post and get methods.

### Views
The views of the web application are divided into two parts the admin views and
the user's views. The admin views are allowing the admin to surf the web
application from the admin perspective, as it allows the admin to perform the CRUD
operations within these views. Such as creating, reading, updating, and deleting
(CRUD) candidates for the election. On the other hand, the users' views, the users are allowed to book a flight, to check the flight available and to view the booked flight details.

### Model
Model–view–controller (MVC) is commonly used for developing user interfaces that divide the related program logic into three interrelated and connected elements which are model, view and controller. This is done to separate the sections of a system so it will be more organized and easy to monitor by the admin

## Entity Relationship Diagram (ER Diagram)
![Flight Reservation ERD](https://i.imgur.com/5nGH48Z.png)
The figure details the Entity Relationship Diagram for the Flight reservation system. The relationship between tables is as follows:
- **One** _User_ registers **None or One or Many** _Bookings_. 
- **None or One or Many** _Airlines_ will standby at **None or One** _Gate_. 
- **One** _Flight_ prepares for **None or One or Many** _Bookings_ 
- **One** _Gate_ reserves **One or Many** _Booking_ 
- **One** _Flight_ selects **One** _Airline_
## Sequence Diagram
The sequence Diagram shows one event from the web application where the admin requests to move to the candidate's view and update information. Then the database is updated, and the admin is notified.
![Flight Reservation Sequence Diagram](https://i.imgur.com/KmqXczL.png)

## Mockup
### Sign Up Page
![Sign Up Page](https://i.imgur.com/O8Jhvsy.jpg)
### Log In Page
![Log In Page](https://i.imgur.com/fb8Ci8E.png)
### Homepage
![Homepage](https://i.imgur.com/7vc3rLz.png)
### Flight Details Page
![Flight Details Page](https://i.imgur.com/pmrEGn1.jpg)
### Ticket Page
![Ticket Page](https://i.imgur.com/oO99OON.jpg)

## References
1. AirAsia, https://www.airasia.com/ 
2. https://laravel.com/docs/8.x/routing
