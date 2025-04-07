# E-Commerce Application (MERN Stack)

This is a mentor-guided project to build a full-fledged **E-commerce application** using the **MERN stack** (**MongoDB, Express.js, React.js, and Node.js**). The application includes features such as **user authentication, product management, order handling, and secure payment processing**.

## Tech Stack

### Frontend
- React.js  
- Tailwind CSS  
- Axios (for API calls)  
- React Router (for navigation)  
- Context API (for global state management)  

### Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose for database handling)  
- Multer (for file uploads)  
- JWT (JSON Web Tokens for authentication)  
- bcrypt (for password hashing)  

## Project Milestones  

### Milestone 1: Project Overview

- Understood the MERN project structure and key functionalities.  
- Explored core e-commerce features:  
  - User Authentication (Login & Registration)  
  - Product Management (Add, update, and retrieve products)  
  - Order Handling (Manage customer orders)  
- Discussed REST API structure and MongoDB schema design.  
- Set up the GitHub repository and planned the project workflow.  

### Milestone 2: Frontend & Backend Setup

- Organized frontend and backend into separate directories.  
- **Frontend**:  
  - Created a React app and configured Tailwind CSS.  
  - Built the login page with user authentication.  
- **Backend**:  
  - Set up a Node.js server using Express.  
  - Connected the backend to MongoDB.  
- The first user-facing feature (Login Page) is complete.  

### Milestone 3: Backend Development & Database Connection

- Implemented a structured backend with routes, controllers, models, and middleware.  
- Configured the Node.js server to handle API requests.  
- Connected MongoDB for efficient data storage.  
- Added basic error handling to improve debugging and user experience.  

### Milestone 4: User Management & File Uploads

- Introduced user management in the backend.  
  - Created a user model using MongoDB schemas.  
  - Implemented a user controller to handle user-related requests.  
- Configured Multer for file uploads, allowing users to upload images.  
- Updated the project repository with these features and documented them in the README.  

### Milestone 5: Creating the Signup Page

- Built the signup page where users can register with:  
  - Full name  
  - Email  
  - Password  
- Implemented form validation:  
  - Proper email format  
  - Strong password validation  
  - Matching password confirmation  
- **Next Steps**: Connecting frontend with backend for authentication.  

### Milestone 6: Connecting Frontend with Backend & User Sessions

- Integrated signup and login pages with backend APIs using Axios.  
- Implemented JWT-based authentication to securely store and manage user sessions.  
- Used localStorage and Context API to maintain login state across sessions.  
- Created protected routes to restrict unauthorized access.  
- Implemented role-based access control (e.g., Admin vs. Regular Users).  

### Milestone 7: User Login API with Secure Authentication

- Created a login API endpoint (`POST /api/auth/login`).  
- Retrieved user data from the database based on the provided email.  
- Validated user credentials:  
  - Used bcrypt to compare entered password with the stored hashed password.  
  - If the password matches, authentication is successful.  
  - If not, an error message is returned.  
- Implemented JWT token generation for secure authentication.  
- Tested the API using Postman and Thunder Client.  

### Milestone 8: Product Cards and Homepage Layout

- Designed and built a **reusable product card component** that accepts product details via props.
- Created a **responsive homepage layout** using Tailwind CSS grid to display multiple cards efficiently across different screen sizes.
- Used mock product data to dynamically generate product cards.

### Milestone 9: Create Product Form

- Built a frontend **Create Product Form** to take product details as input.
- Implemented an image upload feature allowing multiple image selection.
- Ensured the form is responsive and user-friendly using Tailwind CSS.
- **Next Steps**: Connecting form submissions with backend API.

### Milestone 10: Writing Mongoose Schema & API Endpoint

- Created a **Mongoose schema** for storing product details in MongoDB.
- Defined fields like name, description, price, images, and category with proper validation.
- Built a **POST endpoint** to receive and validate product data before storing it in MongoDB.
- Ensured data integrity by implementing validation checks.
- **Next Steps**: Connecting frontend product form with the backend API.

### Milestone 11: Fetching & Displaying Products 

- Added a **GET API endpoint** `/api/products` to retrieve all stored products from MongoDB.
- Used **Axios** to fetch product data in the frontend.
- Passed the retrieved data to the **Product Card Component** for dynamic display.

### Milestone 12: Fetching & Displaying User-Specific Products

- Created an endpoint `/api/products/my-products` to fetch products added by the logged-in user.
- Used **JWT authentication** to filter products based on the user's email.
- Updated the frontend to fetch and display only the logged-in user's products.



### Milestone 13 :  Writing endpoint for mongoDB for Updating

 - How to write an endpoint that will update the existing   data in MongoDB.
 - how to auto fill the form with previous data and give option to edit.


### Milestone 14 : Writing endpoint for mongoDB for deleting

 - How to write an endpoint that delete the product with specific ID from MongoDB.


### Milestone 15 : Creating nav component

 - How to create and Nav component.
 - How to reuse the same component in multiple pages.

### Milestone 16 : Displaying product and Quantity button

 - How to new page to display each product.
 - How to add quantity and add to card button.

### Milestone 17 : Editing User Schemas

 - Edit the user schema to store cart products .
 - Write an end point to receive the product details and store in database.


### Milestone 18 : Backend Endpoints

 - Create an endpoint to receive request from cart page.
 - Create an backend endpoint to fetch all the products inside cart with user mail.

### Milestone 19 : Adding buttons of increase and decrease

 - Create an cart page that display the products inside cart using endpoint we build in milestone 18.
 - For each product add an option to increase and decrease quantity using + and - buttons.
 - Write an endpoint to increase and decrease the quantity

### Milestone 20 : Profile page

 - Create and backend endpoint that will send all the user data using mail.
 - Create an frontend profile page that will display all the user data
 - display profile photo, name, mail and addresses.


### Milestone 21 : Input Address

 - Create an frontend form that will will take address.
 - Take country, city, address1, address2, zip code, address type

### Milestone 22 : Backend to store data

 - Create an backend endpoint that will store the address inside user profile in database.

### Milestone 23 : Product schema

 - We will add an button inside cart called "Place order"
 - We will create an select address page where we will display all the address and ask to select delivery address.
 - We will write mongoose schema for storing orders details.

### Milestone 22 : Confirmation page

 - We will create an order confirmation page.
---

# E-Commerce Application (MERN Stack)

This is a mentor-guided project to build a full-fledged **E-commerce application** using the **MERN stack** (**MongoDB, Express.js, React.js, and Node.js**). The application includes features such as **user authentication, product management, order handling, and secure payment processing**.

## Tech Stack

### Frontend
- React.js  
- Tailwind CSS  
- Axios (for API calls)  
- React Router (for navigation)  
- Context API (for global state management)  

### Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose for database handling)  
- Multer (for file uploads)  
- JWT (JSON Web Tokens for authentication)  
- bcrypt (for password hashing)  

## Project Milestones  

### Milestone 1: Project Overview

- Understood the MERN project structure and key functionalities.  
- Explored core e-commerce features:  
  - User Authentication (Login & Registration)  
  - Product Management (Add, update, and retrieve products)  
  - Order Handling (Manage customer orders)  
- Discussed REST API structure and MongoDB schema design.  
- Set up the GitHub repository and planned the project workflow.  

### Milestone 2: Frontend & Backend Setup

- Organized frontend and backend into separate directories.  
- **Frontend**:  
  - Created a React app and configured Tailwind CSS.  
  - Built the login page with user authentication.  
- **Backend**:  
  - Set up a Node.js server using Express.  
  - Connected the backend to MongoDB.  
- The first user-facing feature (Login Page) is complete.  

### Milestone 3: Backend Development & Database Connection

- Implemented a structured backend with routes, controllers, models, and middleware.  
- Configured the Node.js server to handle API requests.  
- Connected MongoDB for efficient data storage.  
- Added basic error handling to improve debugging and user experience.  

### Milestone 4: User Management & File Uploads

- Introduced user management in the backend.  
  - Created a user model using MongoDB schemas.  
  - Implemented a user controller to handle user-related requests.  
- Configured Multer for file uploads, allowing users to upload images.  
- Updated the project repository with these features and documented them in the README.  

### Milestone 5: Creating the Signup Page

- Built the signup page where users can register with:  
  - Full name  
  - Email  
  - Password  
- Implemented form validation:  
  - Proper email format  
  - Strong password validation  
  - Matching password confirmation  
- **Next Steps**: Connecting frontend with backend for authentication.  

### Milestone 6: Connecting Frontend with Backend & User Sessions

- Integrated signup and login pages with backend APIs using Axios.  
- Implemented JWT-based authentication to securely store and manage user sessions.  
- Used localStorage and Context API to maintain login state across sessions.  
- Created protected routes to restrict unauthorized access.  
- Implemented role-based access control (e.g., Admin vs. Regular Users).  

### Milestone 7: User Login API with Secure Authentication

- Created a login API endpoint (`POST /api/auth/login`).  
- Retrieved user data from the database based on the provided email.  
- Validated user credentials:  
  - Used bcrypt to compare entered password with the stored hashed password.  
  - If the password matches, authentication is successful.  
  - If not, an error message is returned.  
- Implemented JWT token generation for secure authentication.  
- Tested the API using Postman and Thunder Client.  

### Milestone 8: Product Cards and Homepage Layout

- Designed and built a **reusable product card component** that accepts product details via props.
- Created a **responsive homepage layout** using Tailwind CSS grid to display multiple cards efficiently across different screen sizes.
- Used mock product data to dynamically generate product cards.

### Milestone 9: Create Product Form

- Built a frontend **Create Product Form** to take product details as input.
- Implemented an image upload feature allowing multiple image selection.
- Ensured the form is responsive and user-friendly using Tailwind CSS.
- **Next Steps**: Connecting form submissions with backend API.

### Milestone 10: Writing Mongoose Schema & API Endpoint

- Created a **Mongoose schema** for storing product details in MongoDB.
- Defined fields like name, description, price, images, and category with proper validation.
- Built a **POST endpoint** to receive and validate product data before storing it in MongoDB.
- Ensured data integrity by implementing validation checks.
- **Next Steps**: Connecting frontend product form with the backend API.

### Milestone 11: Fetching & Displaying Products 

- Added a **GET API endpoint** `/api/products` to retrieve all stored products from MongoDB.
- Used **Axios** to fetch product data in the frontend.
- Passed the retrieved data to the **Product Card Component** for dynamic display.

### Milestone 12: Fetching & Displaying User-Specific Products

- Created an endpoint `/api/products/my-products` to fetch products added by the logged-in user.
- Used **JWT authentication** to filter products based on the user's email.
- Updated the frontend to fetch and display only the logged-in user's products.



### Milestone 13 :  Writing endpoint for mongoDB for Updating

 - How to write an endpoint that will update the existing   data in MongoDB.
 - how to auto fill the form with previous data and give option to edit.


### Milestone 14 : Writing endpoint for mongoDB for deleting

 - How to write an endpoint that delete the product with specific ID from MongoDB.


### Milestone 15 : Creating nav component

 - How to create and Nav component.
 - How to reuse the same component in multiple pages.

### Milestone 16 : Displaying product and Quantity button

 - How to new page to display each product.
 - How to add quantity and add to card button.

### Milestone 17 : Editing User Schemas

 - Edit the user schema to store cart products .
 - Write an end point to receive the product details and store in database.


### Milestone 18 : Backend Endpoints

 - Create an endpoint to receive request from cart page.
 - Create an backend endpoint to fetch all the products inside cart with user mail.

### Milestone 19 : Adding buttons of increase and decrease

 - Create an cart page that display the products inside cart using endpoint we build in milestone 18.
 - For each product add an option to increase and decrease quantity using + and - buttons.
 - Write an endpoint to increase and decrease the quantity

### Milestone 20 : Profile page

 - Create and backend endpoint that will send all the user data using mail.
 - Create an frontend profile page that will display all the user data
 - display profile photo, name, mail and addresses.


### Milestone 21 : Input Address

 - Create an frontend form that will will take address.
 - Take country, city, address1, address2, zip code, address type

### Milestone 22 : Backend to store data

 - Create an backend endpoint that will store the address inside user profile in database.

### Milestone 23 : Product schema

 - We will add an button inside cart called "Place order"
 - We will create an select address page where we will display all the address and ask to select delivery address.
 - We will write mongoose schema for storing orders details.

### Milestone 24 : Confirmation page

 - We will create an order confirmation page.



### Milestone 25 : Backend endpoint

 - Create an backend endpoint that will help in placing the order. 

### Milestone 26 : Backend endpoint For User Orders

 - Create an backend endpoint that will help getting all the orders of the user.

 - Steps : -
  -  You need to create an endpoint that will receive the user mail
  - You will get the mail of the user using that you need to retrive the _id of the user
  - Using that _id you need to get all the orders of that user

### Milestone 27 : Frontend Page to display Orders

 - Create an frontend page that will display all the user orders.
 - Steps : -
  - You need to create an my-orders page
  - You will send an get request to my-orders endpoint that we created in previous milestone.
  - We will send user mail in to endpoint to get all the user orders
  - Display all the user orders
  - We will add my-orders page in navbar for better navigation.

### Milestone 28 :- Cancel products
 - The use will be able to cancel the placed orders.
  
   - In my-orders page for every order add cancel order button
   - If the order is already canceled this button should not be displayed
   - You need to create an endpoint that will receive the order-id
   - Get the order using this id and mark the status canceled and save

### Milstone 29 :- PayPl API

 - Learn how to use PayPal API.
 - Learn how to Integrate online payments.

  - Please create an PayPal account first PayPal developer dashboard
  - Once you login you can see an option for an sandbox accounts.
  - Copy the UserID of that account and save it.
  - In this sandbox accounts you can find your client id copy and save it.
  - In your order conformation page you need two options for payment one is COD and another is online payment.
  - Create radio buttons to select COD or online payment and when we click on online payment PayPal buttons need to be displayed.
  - In next milestone we will write an code to display and use those PayPal online Payments buttons.
---

