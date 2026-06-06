# auth-service

Handles user authentication, including login and logout.

## Getting Started

```bash
npm install
npm start
```

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `PORT` | HTTP port (default: 3002) | No |

## API

- `POST /login` — Authenticate with username and password
- `POST /logout` — End the current session
