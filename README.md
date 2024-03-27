## Team 5 Mist 4610 Group Project 1
## Team Name:
47114 Group 5

## Team Members:

Emily McNeice    [@ekmcneice](https://github.com/ekmcneice/MIST4610-Group-5)

Warren Paintsil

Nathan Favors [@Nathanfavors](https://github.com/ekmcneice/MIST4610-Group-5)

Duncan Zeller   @duncanzeller

Jessica Hall @jessicahall57

Owen Goble

## Problem Description

Our task is to develop a relational database system for a tennis club. The primary focus is on managing member information and club operations efficiently. This includes tracking memberships, court bookings, coaching schedules, and program registrations. The central entitiy of the model Members. The members are related to our membership, court usage, programs, events, etc. Our task is to accurately model the relationship between these entities and their relationships, to generate data to populate the model, and to provide querys that would be useful to managers. We are aiming to provide valuable insights to the managers about the Tennis club and its operations. 
The database should accurately represent the club's structure and services, catering to members of skill levels. Additionally, it should support functions like generating reports, analyzing membership trends, and facilitating communication between staff and members.
The ultimate goal is to create a practical database solution that streamlines day-to-day operations and provides valuable insights to club management for informed decision-making.


## Data Model

Here's an overview of the Tennis Club Data Model:

Membership Management: We offer various membership options, including individual, family, and corporate memberships. Each membership type may have different access levels and privileges within the club.

Court Reservation System: Members should be able to easily book tennis courts for their matches or practice sessions. We may also have provisions for non-members to book courts on a pay-per-use basis.

Tennis Programs and Coaching: We provide tennis lessons and coaching sessions for players of all ages and skill levels. This includes group lessons, private coaching, and specialized training programs.

Events and Tournaments: Our club hosts regular events, leagues, and tournaments throughout the year. This includes intra-club competitions, friendly matches, and larger-scale tournaments open to members and non-members alike.

Pro Shop and Equipment Rental: We have a pro shop on-site offering tennis equipment, apparel, and accessories. Additionally, we may provide rental services for tennis racquets, balls, and other gear.

Facilities Management: We maintain our tennis courts, clubhouse, locker rooms, and other amenities to ensure they are clean, safe, and well-equipped for our members and guests.

Billing and Payments: We handle membership fees, court reservations, coaching fees, and other transactions through our billing system. This includes processing payments, issuing invoices, and managing membership renewals.

Member Communication: We communicate with our members through various channels, such as email newsletters, social media, and our club website. We may also have a mobile app for convenient access to club information and updates.

<img width="625" alt="Screenshot 2024-03-27 at 1 25 29 PM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163003449/69526a99-2818-4747-971e-e748ff995fd7">


## Data Dictionary
<img width="690" alt="Screenshot 2024-03-27 at 10 46 28 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/92cd0868-64a3-41db-8e6f-d3ec0c3ab44b">
<img width="685" alt="Screenshot 2024-03-27 at 10 46 51 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/4d8e84eb-84f1-4660-9dff-6e35cc853360">
<img width="681" alt="Screenshot 2024-03-27 at 10 47 08 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/f27b8847-a95d-45fd-a6a5-615bf03009a3">
<img width="677" alt="Screenshot 2024-03-27 at 10 47 22 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/8fc5e2eb-d107-406c-b181-c2aa610a9f39">
<img width="684" alt="Screenshot 2024-03-27 at 10 47 34 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/674e8c94-9a19-4862-b962-53e13ab5acbe">
<img width="673" alt="Screenshot 2024-03-27 at 10 52 18 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/8e4d05db-ad89-4e6a-8ca4-c4d56b5b182a">
<img width="689" alt="Screenshot 2024-03-27 at 10 52 36 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/3dc438c5-b298-4439-9d39-60b65548393a">
<img width="668" alt="Screenshot 2024-03-27 at 10 52 51 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/9e0d1284-f58c-42b7-837f-9627e527e71b">
<img width="641" alt="Screenshot 2024-03-27 at 10 53 05 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/7f4f504f-a981-4a39-810b-9bed8dcf3480">
<img width="688" alt="Screenshot 2024-03-27 at 10 53 19 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/50fd17ef-d16d-4957-84be-33cc5a739221">
<img width="681" alt="Screenshot 2024-03-27 at 10 53 35 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/e2bbdc29-c333-414c-a731-034ab8a9d1de">
<img width="715" alt="Screenshot 2024-03-27 at 10 54 26 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/cddc043a-bc6f-4c53-9401-ba23b8f57ef1">
<img width="681" alt="Screenshot 2024-03-27 at 10 54 42 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/11efb3d3-ece3-46d9-84ba-2593e0a980cf">
<img width="686" alt="Screenshot 2024-03-27 at 10 55 01 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/39bd18c6-8cfb-495b-bf87-ec00a1e116a9">



## Queries

1. Analyzing Average Transaction Amount by Membership Type (Complex) - This query helps the manager understand the spending behavior of different membership types, allowing them to tailor marketing strategies, perks, and offerings to maximize revenue generation.
<img width="798" alt="Screenshot 2024-03-27 at 10 27 12 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/366fbb0f-134a-499b-98c7-945ac6c3925e">

2.  Analyzing Member Reservations (Complex) - This query can help the manager understand which members are utilizing the tennis courts the most and at what times. It provides insights into member activity, allowing the manager to optimize court scheduling and potentially identify trends for targeted promotions or adjustments in offerings.
    
4.  Managing Inventory (Complex) - This query can help the manager understand the frequency with which different items are being rented and when. It provides insight into what items are useful to carry or may not be necessary to carry.
<img width="1069" alt="Screenshot 2024-03-27 at 11 09 31 AM" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002253/8b2de715-6787-4bf4-b6e5-9fbf9ac23eeb">

5. Analyzing Revenue by Program Type (Complex): This query helps the manager understand the revenue generated from different types of programs hosted by the tennis club. It calculates the total revenue earned from each program type from Active Members who have signed up for the program, providing insights into which events contribute most to the club's income. This information can guide decisions on event planning, pricing strategies, and resource allocation.
<img width="749" alt="query4" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002443/b0386afa-0e4e-4e75-bfce-9f71ecba1eba">

6. Analyzing Membership by Program Type (Complex): This query helps the manager understand the presence of nonactive or pending memberships within different types of programs hosted by the tennis club. This query also presents the schedule of these programs and the total members, so the manager can easily guide decisions on program scheduling in the future, understand member involvement, and adequately allocate resources.
<img width="809" alt="query2" src="https://github.com/ekmcneice/MIST4610-Group-5/assets/163002443/7b0ba59f-4587-4531-b3b0-c91a0ffeb9f6">

8. Top Spending Clients (Simple) - This query displays the ID and name for each member who has spent more on average than the total average amount using our various services. This can be useful for target marketing and incentives/ exclusive promotions offered by the club.
![Screenshot 2024-03-26 140114](https://github.com/ekmcneice/MIST4610-Group-5/assets/163003264/8cd73c50-33f2-4613-a879-896eaedf737d)

10.  Analyzing Membership Status (Simple) - This query can help the manager send marketing and renewal offers to the emails of members whose memberships are not currently active. This can help bring in new members and restore old members to increase total revenue for the club.
![Screenshot 2024-03-26 132148](https://github.com/ekmcneice/MIST4610-Group-5/assets/163003264/55c7a31c-49c5-42eb-adf3-fbaed33510eb)

11.  Transaction Revenue Split (Simple) - This query helps break down the total amount of revenue gained for each transaction type charged to our clients. This is useful for the manager to analyze trends and make forecasts using these subtotals.
![Screenshot 2024-03-26 133011](https://github.com/ekmcneice/MIST4610-Group-5/assets/163003264/85df63c7-fba3-454e-995c-daf8792db72f)

13.  Email Inbox (Simple) - This query displays the member name, subject, and message of their email as well as the date and time for the manager. This is useful for organization and staying on task with customer needs/ inquiries.
![Screenshot 2024-03-26 134749](https://github.com/ekmcneice/MIST4610-Group-5/assets/163003264/fc5600a2-b678-40e1-aaea-e374294e5323)

14. Identify the Membership Types of People that Participate in Events(Complex): This query helps the manager identify the membership types of those who are very involved with their membership as well as membership types that may not be involved as well. This is important because it allows the manager to see what these members may want and can potentially cater their packages toward these demands. 
![Screenshot 2024-03-26 140853](https://github.com/ekmcneice/MIST4610-Group-5/assets/150088958/a19d6b79-da41-4de7-a90e-41eea4a18e81)



## Database Information

Name of the database: ns_Sp24_47114_Group5

Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: CALL TP_Q1();
