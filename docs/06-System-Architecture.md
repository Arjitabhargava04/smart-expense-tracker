# High Level System Architecture

```
                User
                  │
                  ▼
        React Frontend (TypeScript)
                  │
          Axios (HTTP Requests)
                  │
                  ▼
      Node.js + Express REST API
                  │
        ┌─────────┴─────────┐
        │                   │
        ▼                   ▼
 MongoDB Database      Cloudinary
        │             (Receipt Images)
        │
        ▼
     Stored Data
```

---

## Components

### Frontend

- React
- TypeScript
- Tailwind CSS
- Redux Toolkit

---

### Backend

- Node.js
- Express
- JWT Authentication
- REST APIs

---

### Database

- MongoDB
- Mongoose

---

### External Services

- Cloudinary
- Google OAuth
- Email Service