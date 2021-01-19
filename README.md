## OAuth2 Security Workshop Reference (Step 2)

* product: Spring boot application providing a rest api for products: http://localhost:8081/products
* ui: A Spring boot application providing thymeleaf based html frontend to display products
* authorizationserver: A Spring boot based OAuth2 authorization server

In this step user credentials are stored in a relational database with encrypting the passwords.
Here the authorization server uses form based authentication as login type. 

**Standard user:**  
Username: user@example.com  
Password: secret

**Administrative user:**  
Username: admin@example.com
Password: geheim

