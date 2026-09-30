# Phase 6 – Project Testing

## Testing Tool
Postman was used to test the backend REST APIs.

## Authentication Testing

### Register
Test data:
```json
{
  "name": "Test User",
  "email": "testuser123@gmail.com",
  "password": "Test@12345"
}
```
Result: Passed.

### Login
Used the registered test credentials.
Result: Passed.

### Profile
Retrieved the authenticated user's profile.
Result: Passed.

## Workout Testing

### Add Workout
Tested with an Evening Jog workout.
Result: Passed.

### Add Strength Training Workout
Tested with an Upper Body Strength workout.
Result: Passed.

### Get All Workouts
Verified workout records were returned.
Result: Passed.

### Search by Name
Verified search using a workout-related query.
Result: Passed.

### Search by Date
Verified search using a workout date.
Result: Passed.

### Get Workout by ID
Verified a specific workout could be retrieved.
Result: Passed.

### Update Workout
Changed workout name, duration, and calories.
Result: Passed.

### Delete Workout
Verified workout removal.
Result: Passed.

## AI Assistant Testing

### Workout Recommendation
Input included age, fitness goal, and experience.
After configuring the Gemini API/model correctly, the endpoint generated a recommendation.
Result: Passed.

### Fitness Insights
Input included total workouts, average duration, and total calories burned.
A temporary 503 high-demand response occurred, and a later retry succeeded.
Result: Passed after retry.

## Testing Status
All currently implemented backend API groups have been manually tested using Postman.
