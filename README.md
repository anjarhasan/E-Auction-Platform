# 🧾 E-Auction Platform

A full-stack web application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) to host and manage online auctions. It supports user authentication, product listing, bidding functionality, and payment integration using Stripe.

<img width="1895" height="910" alt="Screenshot 2025-04-24 092951" src="https://github.com/user-attachments/assets/d9093597-d662-42f2-b23c-b1cfced30844" />


<img width="752" height="699" alt="Screenshot 2025-04-24 024814" src="https://github.com/user-attachments/assets/f02e6c8b-4525-4920-a78c-88681ae5a41a" />


<img width="742" height="620" alt="Screenshot 2025-04-24 024852" src="https://github.com/user-attachments/assets/aa5ee078-faec-406d-ab01-32ba686b2dc7" />


<img width="1899" height="885" alt="Screenshot 2025-05-15 002941" src="https://github.com/user-attachments/assets/2733b81a-d0a3-4ae1-a8e3-085c5441271a" />


<img width="1885" height="895" alt="Screenshot 2025-05-15 002327" src="https://github.com/user-attachments/assets/09808cd5-956d-4669-b3d5-19ddaa5832d4" />


<img width="1890" height="900" alt="Screenshot 2025-05-15 002401" src="https://github.com/user-attachments/assets/06fc9037-5b46-49ab-99ec-1216fa7288fb" />


<img width="1883" height="897" alt="Screenshot 2025-05-15 002511" src="https://github.com/user-attachments/assets/5bd4eabd-ddca-4178-ad25-579bdf11a483" />



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

## 📁 Folder Structure

E-Auction-Platform/

├── backend/

│   ├── config/

│   ├── controllers/

│   ├── models/

│   ├── routes/

│   ├── middleware/

│   └── server.js

├── frontend/

│   ├── src/

│   │   ├── components/

│   │   ├── pages/

│   │   ├── App.js

│   │   └── index.js

├── .env

└── README.md


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

LinkedIn: [https://www.linkedin.com/in/anjar-hasan-b6925223a/]

⭐ Star This Repo
If you found this project helpful or learned something from it, please give it a ⭐ to support the work.

