# API Design

Base URL:
`http://localhost:5000`

## Authentication
- POST `/api/auth/register`
- POST `/api/auth/login`
- GET `/api/auth/profile`

## Workouts
- POST `/api/workouts`
- POST `/api/workouts/strength`
- GET `/api/workouts`
- GET `/api/workouts/search?q=...`
- GET `/api/workouts/:id`
- PUT `/api/workouts/:id`
- DELETE `/api/workouts/:id`

## AI Assistant
- POST `/api/ai/workout-recommendation`
- POST `/api/ai/fitness-insights`

Exact route names should be verified against the current source code before final academic submission if routes are changed later.
