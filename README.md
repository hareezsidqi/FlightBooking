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

### Controllers

### Views

### Model

## Entity Relationship Diagram (ER Diagram)
![Flight Reservation ERD](https://i.imgur.com/XrllqyM.png)
The figure details the Entity Relationship Diagram for the Flight reservation system. The relationship between tables is as follows:
- **One** _User_ registers **None or One or Many** _Bookings_. 
- **None or One or Many** _Airlines_ will standby at **None or One** _Gate_. 
- **One** _Flight_ prepares for **None or One or Many** _Bookings_ 
- **One** _Gate_ reserves **One or Many** _Booking_ 
- **One** _Flight_ selects **One** _Airline_
## Sequence Diagram
The sequence Diagram shows one event from the web application where the admin requests to move to the candidate's view and update information. Then the database is updated, and the admin is notified.
![Flight Reservation Sequence Diagram](https://i.imgur.com/KmqXczL.png)
## References
