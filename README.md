# Cartify - E-commerce Web App

**Cartify** is a full-stack e-commerce web application built with the **PERN Stack** — PostgreSQL, Express.js, React.js, and Node.js. It provides a smooth and secure shopping experience with essential features like product browsing, user authentication, and cart management.

---

## Features

- Product catalog with search and filter
- Secure JWT-based authentication and protected routes
- User profile and address book management
- Add-to-cart and order tracking
- Admin dashboard for managing products and users
- Responsive design for all devices

---

## Tech Stack

- **Frontend**: React.js, CSS  
- **Backend**: Node.js, Express.js  
- **Database**: PostgreSQL  
- **Other Tools**: JWT, bcrypt, dotenv, Axios

---

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/routh-vishal/cartify-app.git
   cd cartify-app
   ```

2. **Client Setup**
   ```bash
   cd client
   npm install
   ```

3. **Server Setup**
   ```bash
   cd server
   npm install
   ```

4. **Environment Variables**
   - Rename `.env.example` to `.env` in both client and server folders.
   - Add your database connection string and secret keys.

5. **Database Setup**
   - Create a PostgreSQL database.
   - Run the `schema.sql` script to set up tables:
     ```bash
     psql -U your_username -d cartify_db -f schema.sql
     ```

6. **Run the App**
   ```bash
   cd server && node index.js      # starts backend
   cd client && npm start          # starts frontend
   ```

---

## Project Structure

```
cartify-app/
├── client/     # React frontend
├── server/     # Node + Express backend
├── schema.sql  # Database schema
```

---

## Notes

Cartify demonstrates how to build a scalable, secure, and feature-rich web application using modern JavaScript technologies. It's ideal for learning full-stack development, API design, and database integration.

