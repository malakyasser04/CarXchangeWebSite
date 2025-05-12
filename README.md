# CarXchange 🚗💡
The Modern Way to Buy & Sell Vehicles

# Project Overview
CarXchange revolutionizes automotive transactions with an AI-powered platform that eliminates fees, delays, and uncertainty. this full-stack application combines intuitive design with cutting-edge technology to create a seamless car trading experience.

# ✨ Key Features

Feature	Description

🤖 AI Car Assistant	24/7 chatbot for vehicle advice 

🔐 Secure Auth	JWT authentication + bcrypt password hashing

📸 Rich Listings	Upload 3-15 images per vehicle with detailed specs

🔍 Smart Search	Filter by make, model and year


#🛠️ Tech Stack

Frontend
→ React.js + Tailwind CSS HTML Javascript


Backend
→ Node.js/Express.js REST API
→ JWT authentication middleware

Database
→ MongoDB 
→ Multer for secure image uploads

AI Integration
→ OpenAI GPT-3.5 Turbo via OpenRouter API


# To Run the Application
Separate Terminal Tabs 

Start the Backend Server:

bash

cd server

npm install express nodemon mongoose bcryptjs jsonwebtoken cors dotenv  multer cloudinary  

npm start

Server will run on http://localhost:5000

Start the Frontend Client (in a new terminal tab):

bash

cd client
npm install axios react-router-dom sweetalert2

npm start



