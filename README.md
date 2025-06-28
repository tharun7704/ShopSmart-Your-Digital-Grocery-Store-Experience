# 🛒 Grocery Web App

Welcome to the Grocery Web App – your one-stop solution for online grocery shopping! This full-stack application allows users to browse products, manage their carts, place orders, and enjoy doorstep delivery. It features separate dashboards for users and administrators with a seamless and responsive interface.

## 🌟 Features

### 👤 User Features
- User registration and authentication
- Browse and filter grocery products
- Add/remove items from the shopping cart
- Checkout with secure payment options
- Track order status in real-time
- Provide product ratings and reviews
- View order history and manage profile

### 🛠️ Admin Features
- Manage products (CRUD operations)
- View and manage all customer orders
- Manage user accounts and roles
- Monitor inventory and stock levels
- Access analytics and reporting dashboard

## 🏗️ Tech Stack

- **Frontend**: React.js, Bootstrap, React Router, Axios
- **Backend**: Node.js, Express.js, Mongoose
- **Database**: MongoDB
- **Version Control**: Git + GitHub

---

## 📦 Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- Code Editor (e.g., [VS Code](https://code.visualstudio.com/download))

Install global packages:
```bash
npm install -g nodemon
```

---

## 🚀 Getting Started

### Clone and Setup
```bash
git clone <your-repo-url>
cd grocery-web-app
```

### Setup Backend
```bash
cd backend
npm install
node index.js
```

### Setup Frontend
```bash
cd frontend
npm install
npm run dev
```

Visit the frontend: [http://localhost:5173](http://localhost:5173)

---

## 🗂️ Folder Structure

```
/frontend         # React Frontend
  /src
    /components
    /pages
    /services
/backend          # Express + MongoDB Backend
  /models
  /routes
  /controllers
```

---

## 🔐 Authentication

- JWT-based authentication for secure login/signup
- Role-based access for admin and users
- Protected routes for secure access

---

## 🔄 API Overview

| Method | Endpoint           | Description               |
|--------|--------------------|---------------------------|
| POST   | `/api/register`    | Register a new user       |
| POST   | `/api/login`       | User login                |
| GET    | `/api/products`    | Fetch all products        |
| POST   | `/api/order`       | Place a new order         |
| GET    | `/api/orders/:id`  | Track order by user ID    |

---

## 🧪 Milestones

- **Milestone 1**: Project Setup & Configuration
- **Milestone 2**: Backend & API Development
- **Milestone 3**: Database Models (User, Product, Cart, Order)
- **Milestone 4**: Frontend UI with API Integration
- **Milestone 5**: Admin Dashboard & Final Testing

---

## 🧠 ER Diagram & Architecture

The project follows a client-server architecture using RESTful APIs for communication. MongoDB schemas are used to represent Users, Products, Orders, and Cart.

> View the full ER diagrams and project structure in the documentation PDF or source drive link.

---

## 🙋‍♀️ Use Case: Priya's Experience

Meet **Priya**, a busy professional. With our app:
- She registers securely and shops effortlessly.
- She receives personalized recommendations.
- She selects delivery slots based on her schedule.
- She tracks her orders in real-time.

---

## 👩‍💻 Roles & Responsibilities

### User:
- Register/login
- Browse, add to cart, place orders
- Provide reviews
- Track order and history

### Admin:
- Manage inventory and users
- Process and track orders
- Handle returns and support
- Run promotions and view analytics

---

## 🧪 Testing & Deployment

After building the project, test all flows:
- User registration/login
- Product browsing
- Cart operations
- Order placement
- Admin actions

Deployment can be done using platforms like:
- [Vercel](https://vercel.com/) (Frontend)
- [Render](https://render.com/) / [Railway](https://railway.app/) (Backend + MongoDB)

---

## 📌 References

- React Docs: https://react.dev/
- Express.js: https://expressjs.com/
- MongoDB Docs: https://docs.mongodb.com/
- Bootstrap Docs: https://getbootstrap.com/

---

## 🎉 Conclusion

The Grocery Web App offers a comprehensive and modern solution for online grocery shopping. It ensures convenience, security, and a great user experience for both customers and administrators.

---

## 📧 Contact

For any queries or feedback, please contact:  
📬 [tharunarai123@gmail.com]

---

**Happy Coding! 🧑‍💻**