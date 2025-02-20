# React-Store
# **Cashify Clone - Full Stack Application**

## **Project Overview**

This project is a **Cashify-like** website built using **React.js, Node.js, Express, MongoDB, and Tailwind CSS**. The platform allows users to sell old devices, manage products, process payments, optimize SEO, and includes features like an AI chatbot and a referral program.

## **Tech Stack**

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT-based authentication & Role-Based Access Control (RBAC)
- **Payment Gateway:** Razorpay (or Stripe)
- **SEO Optimization:** React Helmet, Sitemap Generator
- **Additional Features:** AI-Powered Chatbot, Referral Program
- **Deployment:** Netlify (Frontend), Heroku (Backend), MongoDB Atlas

## **Features**

1. **Product Management** ✅
2. **Payment Gateway Integration** ✅
3. **SEO Optimization** ✅
4. **User Authentication & Role-Based Access Control (RBAC)** ✅
5. **Live Price Calculator** ✅
6. **Order Management System** ✅
7. **AI-Powered Chatbot** ✅
8. **Referral & Affiliate Program** ✅

## **Project Setup**

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/cashify-clone.git
cd cashify-clone
```

### **2. Install Dependencies**

#### **Frontend**

```bash
cd frontend
npm install
```

#### **Backend**

```bash
cd backend
npm install
```

### **3. Environment Variables (.env)**

Create a `.env` file in the backend directory:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY=your_razorpay_key
OPENAI_API_KEY=your_openai_api_key
```

### **4. Run the Project**

#### **Backend**

```bash
cd backend
npm start
```

#### **Frontend**

```bash
cd frontend
npm start
```

## **API Endpoints**

### **Authentication**

| Method | Endpoint             | Description         |
| ------ | -------------------- | ------------------- |
| POST   | `/api/auth/register` | Register a new user |
| POST   | `/api/auth/login`    | Login user          |
| GET    | `/api/auth/profile`  | Get user profile    |

### **Product Management**

| Method | Endpoint            | Description       |
| ------ | ------------------- | ----------------- |
| GET    | `/api/products`     | Get all products  |
| POST   | `/api/products/add` | Add a new product |
| PUT    | `/api/products/:id` | Update a product  |
| DELETE | `/api/products/:id` | Delete a product  |

### **Order Management**

| Method | Endpoint                 | Description         |
| ------ | ------------------------ | ------------------- |
| POST   | `/api/orders/create`     | Create an order     |
| GET    | `/api/orders`            | Get all orders      |
| PUT    | `/api/orders/update/:id` | Update order status |

### **Referral System**

| Method | Endpoint                 | Description                 |
| ------ | ------------------------ | --------------------------- |
| POST   | `/api/referral/generate` | Generate referral code      |
| POST   | `/api/referral/track`    | Track referral registration |

## **Deployment Guide**

### **1. Frontend Deployment (Netlify/Vercel)**

- Push frontend code to GitHub
- Sign in to **Netlify/Vercel** and import the project
- Select branch and deploy
- Set environment variables in dashboard

### **2. Backend Deployment (Heroku/DigitalOcean)**

- Create a Heroku app
- Add `MONGO_URI` and other environment variables in Heroku settings
- Deploy using Git:
  ```bash
  git push heroku main
  ```

## **Future Enhancements**

- Add AI-based **Device Value Estimation**
- Implement **PWA Support**
- Introduce **Multi-Language Support**

## **Contributors**

- **Your Name** - Full Stack Developer
- **Other Contributors (if any)**

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

