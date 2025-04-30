# ebay-database
database modeling project for eBay as part of my coursework. This project aimed to design and implement a database to support eBay's online marketplace and auction services. The database was designed to handle a large volume of user accounts, specifically 1.8 million, enabling efficient buying and selling of items through both auction bidding and fixed-price transactions. Key aspects of the project included:
1.	Database Design: I created a comprehensive relational schema that captured the complex relationships between users, items, auctions, orders, and payments within the eBay ecosystem.
2.	Procedure Development: I developed 3 critical procedures for the auction system:
•	A procedure to determine the winner of an auction for an auction-item before the auction ends.
•	A procedure to calculate average marketplace item rating based on user feedback.
•	A procedure to determine the next minimum bid price for auction items.
3.	Trigger Implementation: I created 2 triggers to enhance the system's functionality:
•	A trigger to compute average item ratings from user feedback
•	A trigger to validate the new bid price against the minimum bid price for that item.
4.	SQL Proficiency: The project required extensive use of SQL for creating tables, implementing constraints, and writing queries to manage the database effectively.
This project not only strengthened my database design and SQL skills but also gave me practical experience in modeling real-world business processes and implementing automated systems to support e-commerce operations. It demonstrated my ability to handle complex data relationships and create efficient database solutions for large-scale platforms like eBay.
