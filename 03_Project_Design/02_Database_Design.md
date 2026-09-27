# Database Design

## Main User Data
- User ID
- Name
- Email
- Password information managed by the authentication system

## Main Workout Data
- Workout ID
- User reference
- Workout name
- Category
- Duration
- Calories burned
- Workout date

## AI Request Data
Workout recommendation inputs:
- Age
- Fitness goal
- Experience level

Fitness insight inputs:
- Total workouts
- Average workout duration
- Total calories burned

## Data Relationship
One user can have multiple workout records.

```text
User
 |
 +---- Workout
 |
 +---- Workout
 |
 +---- Workout
```
