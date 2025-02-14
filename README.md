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
-> <u>Showcase Products Effectively</u>: Presents product details in a clear and visually appealing way.
-> <u>Reusable Design</u>: Can be used across multiple pages or sections of the app.
-> <u>Improved User Experience</u>: Makes it easy for users to browse and interact with products.
-> <u>Organized Layout</u>: Keeps the homepage clean and structured.

*How to Display a Single Card for Multiple Products?*
-> <u>Create a Dynamic Component</u>: Design a single card component that accepts product details as props.
-> <u>Use Mapping</u>: Use array mapping to iterate over the product list and render a card for each product.
-> <u>Pass Data Dynamically</u>: Pass unique product information (e.g., name, price, image) to each card.
-> <u>Maintain Consistency</u>: Ensure the layout remains uniform for all products.



