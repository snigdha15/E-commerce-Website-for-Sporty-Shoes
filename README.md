Make an E-commerce Website for Sporty Shoes .


Sporty Shoes is a company that manufactures and sells sports shoes. They have a walk-in store, and now, they wish to launch their e-commerce portal sportyshoes.com.
● Manage the products in the store including categorizing them
● Browse the list of users who have signed up and be able to search users
● See purchase reports filtered by date and category
16 directories, 13 files

## Project Structure
This project uses Spring Boot for Model and Controller Implementation
Availaible apis are -
  - /shoe (CRUD)
  - /purchaseReport (CRUD)
  - /shoe/all
  - /purchaseReport/(category|all|dop)

Current Implementation relies simply on String for storing order list.
It can be extended to utilize many-to-many relationship b/w Shoe and PurchaseReport Entities.
Also for admin authentication spring-security-starter has been used with credentials saved in `application.properties` file.
