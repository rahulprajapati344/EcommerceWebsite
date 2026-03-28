# Forever Full Stack E-Commerce

A full-stack e-commerce application built with Node.js, Express, MongoDB, and a modern frontend (React or similar). This project supports user authentication, product management, and payment integrations (Stripe, Razorpay).

---

## Features

- User authentication (JWT)
- Admin dashboard
- Product CRUD operations
- Image uploads via Cloudinary
- Payments via Stripe and Razorpay
- Responsive frontend

---

## Project Structure

```
forever-full-stack/
├── backend/         # Node.js/Express API
│   ├── .env
│   ├── package.json
│   └── ...
└── frontend/        # React (or other) frontend
    ├── package.json
    └── ...
```

---

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB Atlas account
- Cloudinary account
- Stripe & Razorpay accounts

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/forever-full-stack.git
cd forever-full-stack
```

### 2. Setup Backend

```bash
cd backend
npm install
```

- Create a `.env` file in `/backend`:

  ```
  JWT_SECRET=your_jwt_secret
  ADMIN_EMAIL=your_admin_email
  ADMIN_PASSWORD=your_admin_password

  MONGODB_URI=your_mongodb_connection_string

  CLOUDINARY_API_KEY=your_cloudinary_api_key
  CLOUDINARY_SECRET_KEY=your_cloudinary_secret
  CLOUDINARY_NAME=your_cloudinary_name

  STRIPE_SECRET_KEY=your_stripe_secret_key

  RAZORPAY_KEY_SECRET=your_razorpay_secret_key
  RAZORPAY_KEY_ID=your_razorpay_key_id
  ```

- Start the backend server:

  ```bash
  npm start
  ```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm start
```

---

## Deployment

### Frontend (Netlify)

1. Build the frontend:
   ```bash
   npm run build
   ```
2. Deploy the `build` folder to [Netlify](https://netlify.com/).

### Backend (Render/Railway/Heroku)

1. Push your backend code to GitHub.
2. Deploy using [Render](https://render.com/), [Railway](https://railway.app/), or [Heroku](https://heroku.com/).
3. Set environment variables in the dashboard.

### Update API URLs

- In your frontend, update API endpoints to point to your deployed backend.

---

## Environment Variables

See `.env.example` for all required environment variables.

---

## License

MIT

---

## Author

[Prateek Arora](https://github.com/aprateek29)
