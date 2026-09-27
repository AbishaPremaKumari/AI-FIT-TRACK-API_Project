# Risk Management

| Risk | Possible Effect | Mitigation |
|---|---|---|
| Missing API key | AI requests fail | Store key in `.env` and never commit it |
| MongoDB unavailable | Database requests fail | Start MongoDB before backend |
| AI service temporary overload | 503 response | Retry request later |
| Port 5000 already in use | Backend cannot start | Use the existing server or stop duplicate process |
| Incorrect npm command in PowerShell | Command fails | Use `npm.cmd` when PowerShell policy blocks npm.ps1 |
| Frontend/backend mismatch | UI requests fail | Verify base URL and API routes |
| Accidental secret upload | Security risk | Use `.gitignore` and `.env.example` |

## Important
Never upload real Gemini API keys, JWT secrets, passwords, or database credentials to GitHub.
