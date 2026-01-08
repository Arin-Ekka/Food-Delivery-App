README
🚚 Food Ordering Web App (MERN Stack)
✨ Table of Contents
Introduction
Features
Technologies Used
Installation
Usage
Screenshots
API Documentation
Contributing
Contact
📊 Introduction
This is a full-stack food ordering web application built using the MERN stack (MongoDB, Express, React, Node.js). The application consists of a customer-facing app for ordering food and an admin app for managing orders, menu items, and more.

🚀 Features
User authentication and authorization
Browse food items
Add items to the cart and place orders
Stripe Payment Integration: Secure and reliable payment processing using Stripe.
Order tracking
Admin panel to manage menu items, orders
🛠️ Technologies Used
Frontend: React.js, React Context API, React Router
Backend: Node.js, Express.js
Payment Gateway: Stripe
Database: MongoDB
Authentication: JWT (JSON Web Tokens)
Styling: CSS
Installation
Prerequisites
Node.js
MongoDB
🚀 Run Locally — Step-by-step
Make sure you have Node.js (v20+ recommended) and npm installed.

Clone the Repository
cd mern-food-delivery-app
Backend Setup
Navigate to the backend directory:

cd backend
Install dependencies:

npm install
Create a .env file in the backend directory and add the following:

JWT_SECRET = "random#secret"
STRIPE_SECRET_KEY = "your_stripe_secret_key_here" 
⚠️ Note: Do not commit your .env file. Create your own keys from Stripe Dashboard and use them locally.
Start the backend server:

npm run server
Frontend Setup
Navigate to the frontend directory:

cd frontend
Install dependencies:

npm install
Start the frontend server:

npm run dev
Admin App Setup
Navigate to the admin directory:

cd admin
Install dependencies:

npm install
Start the admin app :

npm run dev
Usage
Access the customer-facing app at http://localhost:5173. Access the admin app at http://localhost:5174. Register as a new user or log in with existing credentials. Browse the menu, add items to the cart, and place an order. Pay using dummy visa card Use the admin panel to manage orders, menu items.

📸 Screenshots
🏠 Home:<img width="1036" height="449" alt="home" src="https://github.com/user-attachments/assets/460e4337-0c97-409e-8925-82708d88b5a9" />

🔐 Login :
<img width="1030" height="454" alt="login" src="https://github.com/user-attachments/assets/5823b071-205d-422a-9d34-0862c892adf6" />

🔐 Signup :
<img width="1039" height="447" alt="signup" src="https://github.com/user-attachments/assets/cbdaf767-a054-44db-8356-e2d6f7a977cb" />

🍔 Menu:
<img width="1034" height="473" alt="menu" src="https://github.com/user-attachments/assets/a396d1bb-df8c-4a36-9e4b-08fe4215e537" />

🍱 Menu Food :
<img width="1034" height="465" alt="menu food" src="https://github.com/user-attachments/assets/860bf99f-b28b-4caa-911d-294ab6c29b64" />

ℹ️ App Download: 
<img width="1037" height="476" alt="app download" src="https://github.com/user-attachments/assets/372eedf4-b68c-4cb8-aaf2-c07f2fd84f47" />

🛒 Cart: 
<img width="1031" height="457" alt="cart" src="https://github.com/user-attachments/assets/ff2581c2-5824-4b8a-812a-d507b3f2a92a" />

📞 Contact :
<img width="1031" height="460" alt="contacts" src="https://github.com/user-attachments/assets/7a461aa7-94af-4dea-a4ed-9b8c10059b9f" />

📜 API Documentation
The API endpoints for the backend can be documented using tools like Postman or Swagger. Include endpoints for user authentication, menu items, orders, and more.

🤝 Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and include relevant tests.

👨‍💻 Contributor

Arin Ekka — Project Owner.
Reg.no:22MIM10138



