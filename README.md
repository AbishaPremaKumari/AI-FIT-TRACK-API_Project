# AI FitTrack

## Project Title
**AI FitTrack – AI-Powered Fitness Tracking and Recommendation System**

## Project Domain
Full Stack Web Development with Artificial Intelligence

## Project Description
AI FitTrack is a fitness tracking application designed to help users record workouts, view workout history, receive AI-generated workout recommendations, and obtain fitness insights from logged activity.

The project currently contains:
- Node.js and Express.js REST API backend
- MongoDB database
- Google Gemini integration for AI recommendations and fitness insights
- React + Vite frontend foundation
- Postman collection for API testing
- Phase-wise project documentation

## Technology Stack
- Frontend: React, Vite, HTML, CSS/SCSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- AI: Google Gemini API
- API Testing: Postman
- Development Environment: Visual Studio Code
- Browser: Google Chrome

## Main Features
1. User Registration
2. User Login
3. User Profile
4. Add Workout
5. Add Strength Training Workout
6. Get All Workouts
7. Search Workouts by Name
8. Search Workouts by Date
9. Get Workout by ID
10. Update Workout
11. Delete Workout
12. AI Workout Recommendation
13. AI Fitness Insights

## Repository Structure
```text
AI-FitTrack/
├── 01_Brainstorming_and_Ideation/
├── 02_Requirement_Analysis/
├── 03_Project_Design/
├── 04_Project_Planning/
├── 05_Project_Development/
├── 06_Project_Testing/
├── 07_Project_Documentation/
├── 08_Project_Demonstration/
├── README.md
└── .gitignore
```

## Important Security Note
Do NOT upload `.env`, API keys, JWT secrets, passwords, or other credentials to GitHub.

Use `.env.example` with placeholder values instead.

## Current Implementation Status
- Backend REST APIs: implemented and tested
- MongoDB connection: tested successfully
- Authentication APIs: tested successfully
- Workout APIs: tested successfully
- AI Workout Recommendation: tested successfully
- AI Fitness Insights: tested successfully after retrying a temporary AI service availability error
- React frontend: Vite/React foundation created; basic AI FitTrack interface created
- Frontend-to-backend API integration: further implementation required

## How to Run the Backend
1. Open the backend project folder.
2. Install dependencies:
   `npm install`
3. Configure environment variables in `.env`.
4. Start the server:
   `npm.cmd start`
5. Backend runs on:
   `http://localhost:5000`

## How to Run the Frontend
1. Open the frontend folder.
2. Install dependencies:
   `npm install`
3. Start Vite:
   `npm.cmd run dev`
4. Open:
   `http://localhost:5173/`

## Academic Note
This repository is organized phase-wise so that brainstorming, requirements, design, planning, development, testing, documentation, and demonstration evidence can be submitted separately.
