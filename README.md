# AI Chatbot Web Application

## Overview
This is a full-stack AI-powered chatbot web application that allows users to interact with an 
intelligent assistant through a chat interface. The application uses an AI API to generate 
human-like responses.

## Features
- Secure user authentication using JWT
- Real-time chat interface
- AI-powered responses
- Session-based message handling
- Clean and responsive UI

## Tech Stack
Frontend:
- React.js
- HTML, CSS, JavaScript

Backend:
- Node.js
- Express.js

Database:
- MongoDB (Atlas)

AI Integration:
- OpenAI API (can be replaced with mock responses if key is unavailable)

## How It Works
- User sends a message from the frontend
- Backend processes the request
- Message is sent to AI API
- AI-generated response is returned and displayed

## How to Run the Project

### Backend
1. Go to backend folder
2. Install dependencies:
   npm install
3. Create `.env` file:
   PORT=5000  
   MONGO_URI=your_mongodb_connection_string  
   JWT_SECRET=your_secret_key  
   OPENAI_API_KEY=your_api_key
4. Start server:
   npm start

### Frontend
1. Go to frontend folder
2. Install dependencies:
   npm install
3. Start app:
   npm start

## Learning Outcomes
- API integration
- Authentication and authorization
- Full-stack application development
- Understanding AI-based systems
