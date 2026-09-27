# Phase 3 – Project Design

## System Architecture

```text
+-----------------------+
|   React Frontend      |
|   (Vite Development)  |
+-----------+-----------+
            |
            | HTTP/REST API
            v
+-----------------------+
| Node.js + Express API |
+-----+------------+----+
      |            |
      |            |
      v            v
+-----------+   +----------------+
| MongoDB   |   | Gemini AI API  |
| Database  |   | Recommendations|
+-----------+   | & Insights     |
                +----------------+
```

## Main Layers
1. Presentation Layer – React frontend
2. API Layer – Express.js routes
3. Controller Layer – request/response handling
4. Service Layer – business logic and Gemini integration
5. Model/Data Layer – MongoDB models and persistence
6. External AI Service – Google Gemini

## Design Principle
The frontend communicates with the backend through REST APIs. The backend manages authentication, workout data, database operations, and AI requests.
