# Development Environment Setup

## Backend
```bash
npm install
npm.cmd start
```

## Frontend
```bash
npm install
npm.cmd run dev
```

## Environment File Example
Create `.env` locally:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/fittrack
JWT_SECRET=your_local_secret
GEMINI_API_KEY=your_gemini_api_key
GEMINI_MODEL=your_supported_gemini_model
```

Do not commit the real `.env` file.
