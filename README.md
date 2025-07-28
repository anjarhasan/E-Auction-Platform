# 🧾 E-Auction Platform

A full-stack web application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) to host and manage online auctions. It supports user authentication, product listing, bidding functionality, and payment integration using Stripe.

---

## 🚀 Features

- 🧑 User Registration & Login (JWT-based)
- 🔒 Role-based authentication (Admin / User)
- 📦 Product listing with image upload
- 🛎️ Real-time bidding updates
- ⏳ Auction timer logic
- 🏆 Automatic winner selection
- 💳 Stripe Payment Gateway (Test Mode)
- 📊 Admin dashboard with analytics
- 🗃️ MongoDB-based storage

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js
- Axios
- Tailwind CSS or Bootstrap (if used)
- Context API / Redux (if state management is added)

### 🔹 Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- Stripe API
- Multer (for image uploads)
- JSON Web Tokens (JWT)

---

## 📁 Folder Structure

E-Auction-Platform/
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.js
│ │ └── index.js
├── .env
└── README.md

yaml
Copy
Edit

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/anjarhasan/E-Auction-Platform.git
cd E-Auction-Platform
2. Set Up Backend
bash
Copy
Edit
cd backend
npm install
Create a .env file in backend/:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_key
Run backend server:

bash
Copy
Edit
npm start
3. Set Up Frontend
bash
Copy
Edit
cd ../frontend
npm install
npm start
🧪 Testing the App
Register a new user

Upload a product as admin

Start bidding from other accounts

Observe winner selection after auction end

Proceed to payment (Stripe test mode)

Use test cards from Stripe:

yaml
Copy
Edit
Card Number: 4242 4242 4242 4242
MM/YY: 12/34
CVC: 123
🧰 APIs Available (Backend)
Method	Route	Description
POST	/api/auth/register	Register new user
POST	/api/auth/login	Login
POST	/api/product	Create new auction product
GET	/api/product	Get all products
POST	/api/bid/:productId	Place a bid
POST	/api/payment	Process payment

🔐 Security
API keys are managed through .env file

Push protection enabled to prevent secret leaks

JWT-based authentication for users and admins

📸 Screenshots
Add screenshots of:

Login/Register page

Product listing

Bidding in action

Payment screen
(Optional but recommended)

🤝 Contributing
Contributions are welcome! Follow these steps:

Fork the repo

Create your feature branch (git checkout -b feature/my-feature)

Commit your changes (git commit -m 'Add my feature')

Push to the branch (git push origin feature/my-feature)

Create a Pull Request

📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

🙋‍♂️ Author
Anjar Hasan

GitHub: @anjarhasan

LinkedIn: [Add your LinkedIn link here]

⭐ Star This Repo
If you found this project helpful or learned something from it, please give it a ⭐ to support the work.

yaml
Copy
Edit

---

Would you like me to:
- Add badges (e.g. `License`, `Tech Used`, `Made with MERN`)?
- Generate a version that includes deploy instructions (Heroku/Vercel)?
- Help add real screenshots to embed?

Let me know!
