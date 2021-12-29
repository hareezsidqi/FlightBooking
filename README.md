```
                                KULLIYYAH OF INFORMATION & COMMUNICATION TECHNOLOGY
                                WEB APPLICATION DEVELOPMENT (INFO 3305), SECTION 3
                                               SEMESTER 1, 2021/2022
                               Web Application Proposal: Flight Reservation Website
                               
                                      Hareez Sidqi Bin Mohd Fuad (2015199)
                                  Nik Nurul Fakhriwani bt Nik Azlan (1911480)
                                  Muhammad Naim Imran bin Mohd Nizar (1917173)

```
## Introduction
## Objectives
## Features and Functionalities
  In the project, the main objective of the system is to ease the process of booking. Thus, we will create a systematic online booking system that consists of the registration for new users, purchasing the ticket and checking the details of the flight. The system is expected to provide consumers with the ideal experience in booking their flight ticket and for admin to do CRUD operations for the detailed flights available. The system also will be able to store data of the registered users, the available flights in the airports and also the details of the booked tickets. Thus,consumers can view their tickets and flights and make adjustments on their purchases.

Apart from that, we will ensure that the booking system is able to accept the registration of new users and the post method will be implemented in the system to ensure the confidentiality of data for each user.

1. **CREATE** procedures: Performs the INSERT statement to create a new record.
2. **READ** procedures: Reads the table records based on the primary key within the input parameter, which is set ready to view.
3. **UPDATE** procedures: Executes an UPDATE statement on the table based on the specified primary key within the WHERE clause of the statement.
4. **DELETE** procedures: Deletes a specified row in the WHERE clause.
5. The user can view the details of the tickets.


## Model-View-Controller-Routes
## Entity Relationship Diagram (ER Diagram)
![Flight Reservation ERD](https://i.imgur.com/XrllqyM.png)
The figure details the Entity Relationship Diagram for the Flight reservation system. The relationship between tables is as follows:
- **One** _User_ registers **None or One or Many** _Bookings_. 
- **None or One or Many** _Airlines_ will standby at **None or One** _Gate_. 
- **One** _Flight_ prepares for **None or One or Many** _Bookings_ 
- **One** _Gate_ reserves **One or Many** _Booking_ 
- **One** _Flight_ selects **One** _Airline_
## Sequence Diagram
## References
