🛒 Ecom Dashboard Backend

This is the backend server for the Ecom Dashboard project.
It is built with Node.js, Express.js, and MongoDB Atlas, providing RESTful APIs to manage products (create, read, and delete).

🚀 Features

Add Product → Insert new products into MongoDB.

Get All Products → Fetch all product data.

Delete Product → Delete products by ID.

Environment Variables → Securely handle sensitive data using .env.

CORS Enabled → Supports cross-origin requests for frontend apps.

🛠️ Tech Stack
Backend Framework: Express.js
Database: MongoDB


📂 Project Structure
ecom-dashboard-backend/
│-- index.js          # Main server file
│-- package.json      # Dependencies and scripts
│-- .env.example      # Example environment variables
│-- README.md         # Project documentation

⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/your-username/ecom-dashboard-backend.git
cd ecom-dashboard-backend

2. Install Dependencies
npm install

3. Setup Environment Variables
Create a .env file in the project root with the following:
PORT=5000
DB_USERNAME=your-mongodb-username
DB_PASS=your-mongodb-password

4. Run the Server

🤝 Contributing

Fork the repository

Create your feature branch (git checkout -b feature/new-feature)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature/new-feature)

Open a Pull Request

