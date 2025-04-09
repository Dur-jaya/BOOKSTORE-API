# BOOKSTORE-API

---
 📚 Book Store API

A fully functional **Book Store API** built using Node.js, Express.js, and MongoDB. This project is a RESTful API that supports user authentication, secure password handling, data validation, and full CRUD functionality for managing books.

---

 🚀 Features

- User Authentication: Secure registration and login with JSON Web Tokens (JWT).
- Password Hashing: Secure passwords using bcryptjs.
- Data Validation: Robust input validation with Joi and joi-password-complexity.
- Error Handling: Simplified async error handling via express-async-handler.
- Environment Configuration: Use dotenv to handle sensitive configuration securely.
- Database: Integrated with MongoDB, modeled with Mongoose.
- Auto Server Restart: Uses nodemon for automatic restarts during development.

---

## 🛠️ Technologies Used

- Node.js – JavaScript runtime
- Express.js M – Web framework for routing and middleware
- MongoDB – NoSQL database
- Mongoose – ODM for MongoDB
- JWT – Authentication using JSON Web Tokens
- bcryptjs – Password encryption
- Joi– Schema-based request validation
- dotenv – Manage environment variables
- nodemon – Auto-restart server during development

---

🧑‍💻 Getting Started

1. Clone the Repository

```bash
git clone https://github.com/onepiece-coding/book-store-api.git
cd book-store-api
```

2. Install Dependencies

```bash
npm install
```

 3. Setup Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
MONGO_URI=mongodb://localhost/booksStoreDB
PORT=5000
NODE_ENV=Development
JWT_SECRET_KEY=secretkey
USER_EMAIL=your_gmail
USER_PASS=your_gmail_app_password
```

> ⚠️ Make sure to use a Gmail App Password, not your actual Gmail password.

---

### 4. Run the Server

```bash
npm start
```

The API will be running at: `http://localhost:5000`
