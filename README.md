Architecture:
![alt text](image.png)
APIs and Methods
1.	Authentication Routes:
○	POST /api/auth/login: Allows users to log in using their credentials (e.g., email and password).
○	POST /api/auth/register: Allows users to create an account by providing necessary details (e.g., email, password, etc.).
2.	Customer Routes:
○	GET /api/customers: Retrieves a list of all customers.
○	GET /api/customers/:id: Retrieves details of a specific customer by their unique ID.
○	POST /api/customers: Creates a new customer by providing relevant data (e.g., first name, last name, phone number, etc.).
○	PUT /api/customers/:id: Updates customer information (e.g., phone number, notes) for a specific customer.
○	DELETE /api/customers/:id: Deletes a customer from the database.
3.	GET /api/search/customers: Allows searching for customers based on a prefix-matched first name, last name, or phone number.
4.	Security and Authorization:
○	Implement middleware to ensure that only authenticated users can access certain routes (e.g., customer creation, creating new users to the database).
○	Use appropriate security rules to restrict access to sensitive data.
