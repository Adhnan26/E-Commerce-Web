🛒 NeoCart – MERN Stack E-Commerce Web Application

NeoCart is a full-stack MERN e-commerce web application developed as the final project for my Full Stack MERN Development course at Error Makes Academy.
This project demonstrates core full-stack concepts such as authentication, REST APIs, database integration, and frontend–backend communication.

🚀 Features

~ User registration and login using JWT authentication
~ Secure password hashing using bcrypt.js
~ Product listing and product detail pages
~ Cart functionality using localStorage
~ Protected checkout (only logged-in users can place orders)
~ Order creation and storage using MongoDB Atlas
~ Responsive and modern UI using React & Tailwind CSS

🧑‍💻 Tech Stack
Frontend :
~ React.js
~ Vite
~ Tailwind CSS
~ JavaScript (ES6+)

Backend :
~ Node.js
~ Express.js
~ MongoDB Atlas
~ JWT (JSON Web Token)
~ bcrypt.js

Tools :
~ Git & GitHub
~ VS Code
~ Postman
~ Versel
~ Render

📂 Project Structure
NeoCart/
├── Backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── Frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   └── App.jsx
│   └── main.jsx

🔐 Authentication Flow :
~ User registers with email and password
~ Password is hashed using bcrypt
~ On login, backend generates a JWT token
~ Token is stored in localStorage
~ Protected routes check token before allowing access

🛒 Cart & Orders :
~ Cart data is stored in localStorage
~ Users can add, remove, and update cart items
~ Checkout is protected for authenticated users
~ Orders are stored in MongoDB Atlas

⚙️ Environment Variables
Backend .env
PORT=5000
MONGO_URI=your_mongodb_atlas_url

Frontend .env
VITE_API_URL=your_backend_url

▶️ How to Run Locally
Backend :
cd Backend
npm install
npm run dev

Frontend :
cd Frontend
npm install
npm run dev

📌 Future Enhancements :
~ Connect products fully from MongoDB
~ Add admin dashboard
~ Integrate payment gateway
~ Add JWT verification middleware in backend

🎓 Course Information 
This project was developed as the final project of the
Full Stack MERN Development Course at Error Makes Academy.

🙌 Acknowledgements 
Thanks to Error Makes Academy for guidance and support throughout the course.

📬 Contact 
Feel free to connect with me on LinkedIn or check out my other projects on GitHub.

