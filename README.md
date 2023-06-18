# Fun:P
A Web Application used to transfer money between multiple users.

1. Introduction
  Front-end: HTML, CSS, Bootstrap, NodeJS & Javascript
  Back-end: PHP
  Database: MySQL   
  Technical Implementation:

    PHP: The PHP code starts with an include statement to import a config.php file, which likely contains database connection details and settings.

    Database Interaction: The code then performs database operations using MySQL. It retrieves information about the sender and recipient from the users table using their respective IDs. It also performs checks to ensure that the transfer amount is valid, including checking for negative values and insufficient balance.

    Transfer Validation: If the transfer amount is valid, the code updates the sender's and recipient's account balances in the user's table, deducting the amount from the sender's balance and adding it to the recipient's balance. It also inserts a record of the transaction into the transaction table.

    It's important to note that this code snippet assumes the existence of a config.html file, a database with appropriate tables (users and transactions), and an understanding of security considerations such as input validation and sanitization. Additionally, the code only handles the back-end logic of the transfer feature. It would require integration with front-end code and proper UI design to create a complete user experience.

3. Testing Methodologies:
    Functional Testing: Functional testing is performed to verify that the software meets the specified functional requirements. It involves testing the software's features and functionality to ensure they work as expected. Test cases are designed based on the requirements and user expectations.

4. Limitations and Future Enhancements:
    It may occur to miscalculate the operation cost including handling fee. 



