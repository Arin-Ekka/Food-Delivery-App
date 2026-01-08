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
git clone https://github.com/DulanjaliSenarathna/mern-food-delivery-app.git
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
🏠 Home :
1

🔐 Login :
2

🔐 Signup :
3

🍔 Menu :
Capture2

🍱 Menu Food :
Capture3

ℹ️ App Download :
Capture4

🍱 Menu Food :
Capture5

🛒 Cart :
Capture6

📞 Contact :
Capture7

❤️ Payment :
Capture8

📜 API Documentation
The API endpoints for the backend can be documented using tools like Postman or Swagger. Include endpoints for user authentication, menu items, orders, and more.

🤝 Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and include relevant tests.

👨‍💻 Contributors

Arin Ekka — Project Owner.
Reg.no:22MIM10138



