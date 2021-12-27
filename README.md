# Task_Jira
For Final practical Examination for Agile Software Engineering, Using Jira I will create a Scrum team that will be building an open-source project 

# 1) Name of chosen product
* Online Shopping
# 2) The members of your team
* We will have 3 cross functional teams in our Scrum Team (Front-End,Back-End and Testing) teams. Each member is applying the T-shaped skills concept which means that He has   broad skills to work outside his area as well as Deep skills and . Our teams composed of:

## 1) Front-End Team
* 1.1 Name: Kevin
  * Role: UI/UX Designer
  * Expertise: Photoshop PS, React JS, JavaScript,.. etc.

* 1.2 Name: Dennis
  * Role: Pages and Applications Responsivness
  * Expertise: Dart, React Js, CSS, HTML,.. etc.

* 1.3 Name: Antonella
  * Role: Backend Integration
  * Expertise: Node Js, APIs and Restful APIs, React Js,..etc.

## 2) Back-End Team
* 2.1 Name: Bernardo
  * Role: Data collection and filtering
  * Expertise: Data acquisition, Python, …etc.

* 2.2 Name: John
  * Role: Initiating Database
  * Expertise: MySQL,PHP,Perl,..etc.

* 2.3 Name: Robert
  * Role: Database Modification and filteration
  * Expertise: MySQL, python, PHP, Firebase...etc
* 2.4 Name: David
  * Role: Back-End Security
  * Expertise: PHP, Javascript,..etc

## 3) Testing Team
* 3.1 Name: Tam
  * Role: Security and Penetration Testing
  * Expertise: Ethical Hacking,python,..etc
* 3.2 Name: Sabrina
  * Role: Acceptance and regression testing
  * Expertise: Selenium,Java,..etc
* 3.3 Name: Julia
  * Role: Functional and API Testing
  * Expertise: RapidAPI, Java,..etc
* 3.4 Name: Gabi
  * Role: Integration Testing
  * Expertise: Kantalon, smart bear, Java,..etc
  
# 3) Possible Stakeholders
* I will represent the possible stakeholders by Stakeholders Matrix

| Name        | Role        | Availability| Influence   | Engagement |
| ----------- | ----------- | ----------- | ----------- | ---------- |
| Mats John   | Stakeholder | High          | High          | Actively engaged |
| Mahdi Benatia   | Stakeholder | High    | High   | Actively Engaged |
| Alphonso Davies | Stakeholder | High  | Low   | Keep informed    |
| Youssef Mohamed | Sponsor     | Low    | High   | Keep Satisfied   |
| Ashraf Hakimi   | Subject Matter Expert | Low | Low    | Monitor          |

# 4) First sprint Near vision
* Our initial goal of the first sprint is to create an account page after making UI designs for create account page by the front-end team with intiaition and modification of Database with some insertions as well as Acceptance and regression testing for the developed part.

# 5) Second sprint Near vision
* Our initial goal of the second sprint is to create login page after making UI designs for login page with collection of data and modification of Database. Also, Adding security for the login page for verification by Two-factor authentication as well as Acceptance and regression testing and security testing for the developed part with integrating the front end with the backend.

# 6) Rationale Product Backlog Order
We have to epics the first one is **Database Development with verification** and the second one is **Payment and Cart**, They are ordered like this because we need to develop the database with its dependents such as login then after that we can focus on the payment methods and cart.

* In the first Epic: The order start with the PBIs that have high buisness value to customer, We started with Database Development PBI then Database modifications PBI as the database is the heart of our online shopping system because all the next items in the backlog definitly depend on the database such as create account PBI which store the account created in the database then login which should come after create an account and need to compare the data written in the login with the stored ones in the database. After that we put The Two-factor authentication item due to the dependency of this item on login. After all these PBIs, We put the show available products PBI as it get the available products from the database and require the user to be logged in first.

* In the second Epic:  The first PBI we put is Categorized Cart beacuse this is the most important PBI in this epic because all the PBIs after it depend totally on it so we put after that the Add to cart PBI to add items then we put Modify Cart to be abl to modify the items added to cart. After that we put Check offers PBI thenwe start putting the payment options PBIs such that Visa Payment PBI then Visa payment Rejection PBI to reject any payment if wrong Visa data is added. Moreover, we put the Fawry payment PBI then Fawry Payment Rejection PBI in case of adding wrong Fawry number, Error handling of each payment method should be implemented after each payment method of them then we put Apple Pay PBI. Additionally, The print Reciept PBI is added because it should be printed after payment process is finished it is considered the last step in payment. Finally, We put the order notification PBI to notify the user whether the order placed succeffully or not as a final step.
