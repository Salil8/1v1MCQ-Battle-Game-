# Realtime 1v1 MCQ Battle Arena

## Project Overview

This project is a real-time multiplayer MCQ (Multiple Choice Questions) battle game developed as part of the Algozenith Quarterly Hackathon [May '24 - Jun '24]. It combines Django for the backend and React for the frontend, with real-time interactions handled using Pusher WebSockets.

## Features

- Real-time multiplayer MCQ battles
- Secure user authentication and registration
- CRUD functionalities for MCQs
- Modular game engine with robust state management
- Game lobby system for managing sessions and real-time user interactions
- Responsive and intuitive UI using React and CSS
- Data integrity and validation

## Technologies Used

- **Backend:** Django, Django REST Framework, djangorestframework-simplejwt, SQLite (or other SQL database)
- **Frontend:** React, CSS
- **Real-time Communication:** Pusher WebSockets
  

## Setup Instructions

### Prerequisites

- Python 3.x
- Node.js
- npm or yarn
- Pusher account for WebSockets

## Usage

- Register a new user at http://127.0.0.1:8000/register.
- Login using the registered credentials at http://127.0.0.1:8000/login.
- Access the game lobby and start a real-time MCQ battle.
- API Endpoints
- Authentication
- POST /register: Register a new user
- POST /login: Login and obtain JWT tokens
- MCQ Management
- GET /mcqs: List all MCQs
- POST /mcqs: Create a new MCQ
- GET /mcqs/<uuid:pk>: Retrieve a specific MCQ
- PUT /mcqs/<uuid:pk>: Update a specific MCQ
- DELETE /mcqs/<uuid:pk>: Delete a specific MCQ
- Protected View (Optional)
- GET /protected: Access a protected view

## Contributions

-Contributions are welcome! Please fork the repository and create a pull request with your changes.


## Acknowledgements

- Algozenith for organizing the hackathon
- Django, React, and Pusher communities for their excellent documentation and support

