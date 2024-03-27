## Team 5 Mist 4610 Group Project 1
## Team Name:
47114 Group 5

## Team Members:

Emily McNeice    [@ekmcneice](https://github.com/ekmcneice/MIST4610-Group-5)

Warren Paintsil

Nathan Favors

Duncan Zeller   @duncanzeller

Jessica Hall @jessicahall57

Owen Goble

## Problem Description

Our task is to develop a relational database system for a tennis club. The primary focus is on managing member information and club operations efficiently. This includes tracking memberships, court bookings, coaching schedules, and program registrations. The central entitiy of the model Members. The members are related to our membership, court usage, programs, events, etc. Our task is to accurately model the relationship between these entities and their relationships, to generate data to populate the model, and to provide querys that would be useful to managers. We are aiming to provide valuable insights to the managers about the Tennis club and its operations. 
The database should accurately represent the club's structure and services, catering to members of skill levels. Additionally, it should support functions like generating reports, analyzing membership trends, and facilitating communication between staff and members.
The ultimate goal is to create a practical database solution that streamlines day-to-day operations and provides valuable insights to club management for informed decision-making.


## Data Model

Here's an overview of our business operations:

Membership Management: We offer various membership options, including individual, family, and corporate memberships. Each membership type may have different access levels and privileges within the club.

Court Reservation System: Members should be able to easily book tennis courts for their matches or practice sessions. We may also have provisions for non-members to book courts on a pay-per-use basis.

Tennis Programs and Coaching: We provide tennis lessons and coaching sessions for players of all ages and skill levels. This includes group lessons, private coaching, and specialized training programs.

Events and Tournaments: Our club hosts regular events, leagues, and tournaments throughout the year. This includes intra-club competitions, friendly matches, and larger-scale tournaments open to members and non-members alike.

Pro Shop and Equipment Rental: We have a pro shop on-site offering tennis equipment, apparel, and accessories. Additionally, we may provide rental services for tennis racquets, balls, and other gear.

Facilities Management: We maintain our tennis courts, clubhouse, locker rooms, and other amenities to ensure they are clean, safe, and well-equipped for our members and guests.

Billing and Payments: We handle membership fees, court reservations, coaching fees, and other transactions through our billing system. This includes processing payments, issuing invoices, and managing membership renewals.

Member Communication: We communicate with our members through various channels, such as email newsletters, social media, and our club website. We may also have a mobile app for convenient access to club information and updates.

## Data Dictionary



## Queries

1. Analyzing Average Transaction Amount by Membership Type (Complex) - This query helps the manager understand the spending behavior of different membership types, allowing them to tailor marketing strategies, perks, and offerings to maximize revenue generation.
<img width="798" alt="Screenshot 2024-03-27 at 10 27 12 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/366fbb0f-134a-499b-98c7-945ac6c3925e">

2.  Analyzing Member Reservations (Complex) - This query can help the manager understand which members are utilizing the tennis courts the most and at what times. It provides insights into member activity, allowing the manager to optimize court scheduling and potentially identify trends for targeted promotions or adjustments in offerings. 
3.  Managing Inventory (Complex) - This query can help the manager understand the frequency with which different items are being rented and when. It provides insight into what items are useful to carry or may not be necessary to carry. 
4.  Analyzing Revenue by Program Type (Complex): This query helps the manager understand the revenue generated from different types of programs hosted by the tennis club. It calculates the total revenue earned from each program type from Active Members who have signed up for the program, providing insights into which events contribute most to the club's income. This information can guide decisions on event planning, pricing strategies, and resource allocation.

5.  Analyzing Membership by Program Type (Complex): This query helps the manager understand the presence of nonactive or pending memberships within different types of programs hosted by the tennis club. This query also presents the schedule of these programs and the total members, so the manager can easily guide decisions on program scheduling in the future, understand member involvement, and adequately allocate resources. 
[!Picture](https://private-user-images.githubusercontent.com/163002443/317116786-082d3241-c53d-4630-ae02-9cad2717ec88.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTE1NDc4NzYsIm5iZiI6MTcxMTU0NzU3NiwicGF0aCI6Ii8xNjMwMDI0NDMvMzE3MTE2Nzg2LTA4MmQzMjQxLWM1M2QtNDYzMC1hZTAyLTljYWQyNzE3ZWM4OC5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMyN1QxMzUyNTZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wYzJjMjJhZTMxOTFkMTNjZDYyYTI0MjhiOGViMDFiNjMzYTVhM2M4OTc3NjM2MDYyN2JhNmIxZjM1Njk3MDBlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.9ibGK09EitC7p95HdlJK7esa5RUWUmqJlyFkkNvl9CI)
6. Top Spending Clients (Simple) - This query displays the ID and name for each member who  has spent more on average than the total average amount using our various services. This can be useful for target marketing and incentives/ exclusive promotions offered by the club.
7.  Analyzing Membership Status (Simple) - This query can help the manager send marketing and renewal offers to the emails of members whose memberships are not currently active. This can help bring in new members and restore old members to increase total revenue for the club.
8.  Transaction Revenue Split (Simple) - This query helps break down the total amount of revenue gained for each transaction type charged to our clients. This is useful for the manager to analyze trends and make forecasts using these subtotals.
9.  Email Inbox (Simple) - This query displays the member name, subject, and message of their email as well as the date and time for the manager. This is useful for organization and staying on task with customer needs/ inquiries. 
10. Identify the Membership Types of People that Participate in Events(Complex): This query helps the manager identify the membership types of those who are very involved with their membership as well as membership types that may not be involved as well. This is important because it allows the manager to see what these members may want and can potentially cater their packages toward these demands. 



## Database Information

Name of the database: ns_Sp24_47114_Group5
Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: CALL TP_Q1();
