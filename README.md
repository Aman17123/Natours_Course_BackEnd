<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Natours – Advanced Node.js, Express & MongoDB Project</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 40px;">

    <h1>🌍 Natours – Advanced Node.js, Express & MongoDB Project</h1>

    <p>
        A complete backend travel tour booking application built while learning advanced 
        Node.js concepts including MVC architecture, RESTful APIs, authentication, 
        authorization, security, and deployment.
    </p>

    <hr>

    <h2>🚀 Live Demo</h2>
    <p>(Add your deployed link here after hosting)</p>
    <p>
        🔗 <a href="https://your-live-link.com" target="_blank">
        https://your-live-link.com</a>
    </p>

    <hr>

    <h2>📌 Project Overview</h2>
    <p>Natours is a production-level backend application that allows users to:</p>

    <ul>
        <li>Browse tours</li>
        <li>Filter & sort tours</li>
        <li>View tour details</li>
        <li>Sign up & log in</li>
        <li>Book tours</li>
        <li>Manage user profiles</li>
        <li>Admin manage tours & users</li>
    </ul>

    <p>This project follows <strong>MVC Architecture</strong> and industry best practices.</p>

    <hr>

    <h2>🛠 Tech Stack</h2>
    <ul>
        <li>Node.js</li>
        <li>Express.js</li>
        <li>MongoDB</li>
        <li>Mongoose</li>
        <li>JWT Authentication</li>
        <li>Stripe Payment Integration</li>
        <li>Nodemailer</li>
        <li>Security Packages (Helmet, Rate Limit, xss-clean, etc.)</li>
    </ul>

    <hr>

    <h2>🧠 Features Implemented</h2>

    <h3>✅ Authentication & Authorization</h3>
    <ul>
        <li>User Signup</li>
        <li>Login / Logout</li>
        <li>JWT-based authentication</li>
        <li>Password encryption using bcrypt</li>
        <li>Role-based access (Admin, User)</li>
    </ul>

    <h3>✅ Tour Management</h3>
    <ul>
        <li>CRUD operations</li>
        <li>Advanced filtering</li>
        <li>Sorting</li>
        <li>Pagination</li>
        <li>Aliasing routes</li>
        <li>Aggregation pipelines</li>
    </ul>

    <h3>✅ Security</h3>
    <ul>
        <li>Data sanitization</li>
        <li>NoSQL injection protection</li>
        <li>XSS protection</li>
        <li>HTTP security headers</li>
        <li>Rate limiting</li>
    </ul>

    <h3>✅ Error Handling</h3>
    <ul>
        <li>Global error handling middleware</li>
        <li>Operational vs Programming errors</li>
        <li>Custom error class</li>
    </ul>

    <hr>

    <h2>📂 Project Structure (MVC)</h2>

    <pre>
natours/
│
├── controllers/
│   ├── tourController.js
│   ├── userController.js
│   └── authController.js
│
├── models/
│   ├── tourModel.js
│   └── userModel.js
│
├── routes/
│   ├── tourRoutes.js
│   └── userRoutes.js
│
├── utils/
│   ├── appError.js
│   └── catchAsync.js
│
├── config.env
├── app.js
└── server.js
    </pre>

    <hr>

    <h2>⚙️ Installation & Setup</h2>

    <h3>1️⃣ Clone the repository</h3>
    <pre>git clone https://github.com/your-username/natours.git</pre>

    <h3>2️⃣ Install dependencies</h3>
    <pre>npm install</pre>

    <h3>3️⃣ Create a config.env file</h3>
    <pre>
PORT=3000
DATABASE=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
JWT_EXPIRES_IN=90d
    </pre>

    <h3>4️⃣ Start the development server</h3>
    <pre>npm run dev</pre>

    <hr>

    <h2>🔐 API Endpoints Example</h2>

    <h3>🗺 Tours</h3>
    <ul>
        <li>GET /api/v1/tours</li>
        <li>GET /api/v1/tours/:id</li>
        <li>POST /api/v1/tours</li>
        <li>PATCH /api/v1/tours/:id</li>
        <li>DELETE /api/v1/tours/:id</li>
    </ul>

    <h3>👤 Users</h3>
    <ul>
        <li>POST /api/v1/users/signup</li>
        <li>POST /api/v1/users/login</li>
        <li>GET /api/v1/users/me</li>
    </ul>

    <hr>

    <h2>🧪 Testing</h2>
    <p>You can test APIs using:</p>
    <ul>
        <li>Postman</li>
        <li>Thunder Client</li>
        <li>Insomnia</li>
    </ul>

    <hr>

    <h2>🚀 Deployment</h2>
    <ul>
        <li>AWS</li>
        <li>Render</li>
        <li>Railway</li>
        <li>Heroku (if available)</li>
    </ul>

    <hr>

    <h2>📚 What I Learned</h2>
    <ul>
        <li>Advanced Express architecture</li>
        <li>Middleware chaining</li>
        <li>MongoDB aggregation framework</li>
        <li>Authentication flow with JWT</li>
        <li>Production-level error handling</li>
        <li>API security best practices</li>
        <li>Environment configuration</li>
        <li>Deployment strategies</li>
    </ul>

    <hr>

    <h2>👨‍💻 Author</h2>
    <p>
        <strong>Aman</strong><br>
        Backend Developer | MERN Stack Learner<br>
        GitHub: 
        <a href="https://github.com/Aman17123" target="_blank">
        https://github.com/Aman17123</a>
    </p>

    <hr>

    <h2>⭐ If You Like This Project</h2>
    <p>Give it a ⭐ on GitHub!</p>

</body>
</html>
