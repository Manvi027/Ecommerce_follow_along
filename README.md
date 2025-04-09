# Ecommerce_follow_along

**Milestone 1**: Project Overview 📝

In todays live session our mentor introduced us to the overall structure of MERN Stack.
He taught us the foundational and initial steps to set up the environment for future milestones, we created a new repository for our follow along project.

**Milestone 2**: Dev-Setup and Login Page 📝

***Project Folder Structure*** : Learn to organize your project files into separate frontend and backend directories.
***React Frontend Setup*** : Initialize a React application for building the user interface.
***Node.js Backend Setup*** : Set up a simple Node.js server to prepare for API integration in future milestones.
***Tailwind CSS Configuration*** : Integrate and configure Tailwind CSS to enable modern, responsive, and utility-based styling.
***Login Page Development*** : Create the first user interface of your e-commerce application, focusing on both functionality and styling.

**Milestone 3**: Overview 📝

In this live session led by our mentor we did :
*Setting up backend folders and files.
*Configuring and connecting the server to MongoDB.
*Writing basic error-handling code.

**Milestone 4**: project overview  📝

In this mentor led live session we learned to create a user model(This is like a blueprint for how users' data will be stored in the database).
Then we learned to create a user controller(This will help to manage what happens with user's data (like adding a new user or getting their information)).
*Enable and configure Multer: Multer will allow app to accept and store files (such as images) uploaded by users.At last we pushed the changes into our repository.

**Milestone 5**: Sign-up page 📝

In this milestone with the help of our mentor we created the frontend UI for users to register by filling out their details.
We ensured that user inputs (like email and password) are properly validated before they’re submitted.
✨A sign-up page consists of typically these fields like: username , email ,password.
At the end we have updated the readme.md file summarizing the work done in milestone5.

**Milestone 6**: Backend Endpoint 📝

In this milestone we understood how to encrypt the passwords before saving and how to store complete user data securely in the database.

Why we should use encrypting passwords ?
Protect User Data: Keeps passwords safe if hackers access the database.
Privacy: Ensures user passwords aren’t visible to anyone.
Compliance: Follows security laws like GDPR and PCI-DSS.
Stops Password Theft: Encrypted passwords can’t be easily stolen or guessed.

At the end we just pushed the changes into our github repository and updated the readme file summarizing what was done in the milestone.


**Milestone 7**: User Login Backend 📝

 *Learning Goals*  
- Validate user credentials during login.  
- Compare encrypted passwords securely.  

 *Why Encrypt Passwords?* 
- *Security*: Protects user data if the database is compromised.  
- *Privacy*: Prevents storing passwords in plain text.  
- *Compliance*: Meets security standards (GDPR, PCI-DSS).  
- *Prevention*: Makes password theft harder with hashing.  

 *How Login Authentication Works*  
1. *User Inputs Credentials* → Email/username & password.  
2. *Fetch User Data* → Check if the user exists in the database.  
3. *Validate Password* → Use bcrypt to hash & compare with stored hash.  

   *Steps to Implement*  
1. *Create Login Endpoint* → Accept email/username & password.  
2. *Retrieve User* → Fetch user data from the database.  
3. *Verify Password* → Hash input & compare with stored hash.  

 *Note:* Passwords are hashed (not decrypted). We compare hashes for authentication.

**Milestone 8**: Card Components 📝

*Learning goals* :
-> Learn how to create a card component.
-> Learn how to display those cards on the products page.  
 
 *Why Create Card Components?* 
-> Showcase Products Effectively: Presents product details in a clear and visually appealing way.
-> Reusable Design: Can be used across multiple pages or sections of the app.
-> Improved User Experience: Makes it easy for users to browse and interact with products.
-> Organized Layout: Keeps the homepage clean and structured.

*How to Display a Single Card for Multiple Products?*
-> Create a Dynamic Component: Design a single card component that accepts product details as props.
-> Use Mapping: Use array mapping to iterate over the product list and render a card for each product.
-> Pass Data Dynamically: Pass unique product information (e.g., name, price, image) to each card.
-> Maintain Consistency: Ensure the layout remains uniform for all products.

**Milestone 9** : Frontend Form 📝

*Learning Goals* :
-> Learn how to create a form that will take all the details of product
-> Learn how to take multiple images as input.

*Why Create Product form?* :
-> Here we will create an form to input all the details of product.
-> This details will be eventually saved in database and will be displayed on products home page we created in previous milestone.

This lesson will help us in understanding the basic creating of products please feel free to experiment on adding more features like creating an admin access and allow only admin to upload products or create and shop profile and a user with only shop profile can upload.

**Milestone 10**: 📝

*Learning Goals* :
-> Learn how to write product schema
-> Learn how to create an end point to validate and store product details in mongodb.

*Product Schema* :
-> Define the structure of product data (e.g., name, description, price, image URL) using Mongoose. -Ensure each field has proper validation (e.g., required fields, correct data types).

*Endpoint Creation* :
-> Build a POST endpoint to receive product data.
-> Validate and save the product details to MongoDB.

*Why Validation?* :
-> Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.

This lesson will help us in understanding the basic creating of products please feel free to experiment on adding more features like creating an admin access and allow only admin to upload products or create and shop profile and a user with only shop profile can upload.

**Milestone 11** : 📝

*Learning Goals* :

-> How to write an endpoint that will send data from extract and send data from mongodb.
-> how to receive data at frontend -How to display that data dynamically using product card created earlier.

This lesson will help us in understanding How to send and receive data and how to display that data dynamically using components. Further we pushed the changes to our git repo. using the git commands.

**Milestone 12** : 📝

*Learning Goals* : 

-> How to write an endpoint that will send data by filtering with my mail and send data from mongodb.
-> how to receive data at frontend -How to display that data dynamically using product card created earlier.

This lesson will help us in understanding How to Filter the data with particular constrains and send it to client.

**Milestone 13** :📝 

*Learning Goals* :

-> How to write an endpoint that will update the existing data in MongoDB.
-> how to auto fill the form with previous data and give option to edit.

In frontend we will add an edit button to the product card. When click on edit we will send the data to form and make it auto fill and have option to edit those data and save.

Note:- This lesson will help us in understanding how to perform update operation in detailed.

**Milestone 14** :📝

*Learning Goals* :

-> How to write an endpoint that delete the product with specific ID from MongoDB.

We will write an endpoint that will Delete the data form MongoDB using ID. In frontend we will add an delete button to the product card. 
When click on delete button we will send the product id to server endpoint.

Note:- This lesson will help you in understanding how to perform delete operation in detailed.


**Milestone 15** : 📝

*Learning Goals* :

-> How to create and Nav component.
-> How to reuse the same component in multiple pages.

We will add the nav component to all the pages and make the navigations to all this pages smooth and easy.

This lesson will help us in understanding how to create navbar and help to navigate to multiple pages in application. 

**Milestone 16** : 📝

*Learning Goals* 

-> How to new page to display each product.
-> How to add quantity and add to card button.

Create an new page that display all the product data.



**Milestone 17** : 📝


*Learning Goals*

-> Edit the user schema to store cart products .
-> Write an end point to receive the product details and store in database.

This lesson helped in understanding how to create cart functionality.

**Milestone 18** : 📝

Learning Goals 🎯:

-> Create an endpoint to receive request from cart page.
-> Create an backend endpoint to fetch all the products inside cart with user mail.

This lesson helped in understanding how to create cart functionality.

**Milestone 19** : 📝

Learning Goals 🎯 :

-> Create an cart page that display the products inside cart using endpoint we build in milestone 18.
-> For each product add an option to increase and decrease quantity using + and - buttons.
-> Write an endpoint to increase and decrease the quantity.

**Milestone 20**  📝

Learning Goals 🎯 :

-> Create and backend endpoint that will send all the user data using mail.
-> Create an frontend profile page that will display all the user data
-> display profile photo, name, mail and addresses.

This lesson helped in understanding how to display profile page.

**Milestone 21** : 📝

Learning Goals 🎯:

--> Create an frontend form that will will take address.
--> Take country, city, address1, address2, zip code, address type

Steps for Milestone 21 - 

--> create address form frontend page
--> Create an state that will store input address
--> when we click on add address in profile it should navigate to this form page.

This lesson helped in understanding how to address form.

**Milestone 22** 📝

Learning Goals 🎯:

--> Create an backend endpoint that will store the address inside user profile in database.

Steps for Milestone 22 :

--> You need to create an endpoint that will receive the address from address form in frontend
--> Add the address to the address array inside user collection.

This lesson helped in understanding how to create an endpoint that will store the address.

**Milestone 23** 📝:

Learning Goals 🎯:

--> We will add an button inside cart called "Place order".
--> We will create an select address page where we will display all the address and ask to select delivery address.
--> We will write mongoose schema for storing orders details.

This lesson helped in understanding How to implement place order functionality.

**Milestone 24** 📝:

Learning Goals 🎯

--> We will create an order conformation page.

Steps for Milestone 24 -

--> First we will display all the products we are ordering
--> Next we will display the address user selected to deliver
--> We will display the total value of the cart
--> We will have an place order button at the bottom.

Note:- This lesson helped in understanding How to implement place order functionality.

**Milestone 25** 📝 :

Learning Goals 🎯

--> Create an backend endpoint that will help in placing the order.

Steps for Milestone 25 -

--> We created an endpoint that will receive the products, user, address details.
--> We  will get the mail of the user using that we need to retrive the _id of the user.
--> For each product the order will be different with same address.
--> Using order schema we created earlier , we will store order details in mongodb order collection.

This lesson helped in understanding how to create an endpoint that place order.

**Milestone 26** 📝 :

Learning Goals 🎯

--> Create an backend endpoint that will help getting all the orders of the user.

Steps for Milestone 26 -

--> We need to create an endpoint that will receive the user mail.
--> We will get the mail of the user using that we need to retrive the _id of the user
--> Using that _id we need to get all the orders of that user
--> Send all the users orders in the response.

This lesson helped in understanding how to get all the users orders.

**Milestone 27** 📝 :

Learning Goals 🎯

--> Create an frontend page that will display all the user orders.

Steps for Milestone 27 - 

--> We need to create an my-orders page.
--> We will send an get request to my-orders endpoint that we created in previous milestone.
--> We will send user mail in to endpoint to get all the user orders.
--> Display all the user orders.
--> We will add my-orders page in navbar for better navigation.

This lesson helped in understanding how to get all the users orders.

**Milestone 28** 📝 :

Learning Goals 🎯

--> The user will be able to cancel the placed orders.

Steps for Milestone 28 -

--> In my-orders page for every order add cancel order button.
--> If the order is already canceled this button should not be displayed.
--> We need to create an endpoint that will receive the order-id.
--> Get the order using this id and mark the status canceled and save.

This lesson helped in understanding how to cancel users orders.

**Milestone 29** 📝 :

Learning Goals 🎯

--> Learn how to use PayPal API.
--> Learn how to Integrate online payments.

Steps for Milestone 29 -

--> Created an PayPal account .
--> Once we login we can see an option for an sandbox accounts.
--> Copy the UserID of that account and save it.
--> In this sandbox accounts we can find our client id copy and save it.
--> In our order conformation page we need two options for payment one is COD and another is online payment.
--> Create radio buttons to select COD or online payment and when we click on online payment PayPal buttons need to be displayed.

In next milestone we will write an code to display and use those PayPal online Payments buttons.














