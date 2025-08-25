<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>📚 Library Management System</h1>
<!-- Sidebar Navigation -->
<nav>
  <h2>📑 Contents</h2>
  <ul>
    <li><a href="#overview">📝 Project Overview</a></li>
    <li><a href="#features">✨ Features</a></li>
    <li><a href="#tech-stack">🛠 Tech Stack</a></li>
    <li><a href="#getting-started">🚀 Getting Started</a></li>
    <li><a href="#scripts">📜 Scripts</a></li>
    <li><a href="#structure">📂 Structure</a></li>
    <li><a href="#config">⚙️ Configuration</a></li>
    <li><a href="#api">🔗 API Endpoints</a></li>
    <li><a href="#contribute">🤝 Contributing</a></li>
  </ul>
</nav>

<!-- Main Content -->
<main>
  <p>
    <span>⚛️ React</span> |
    <span>🟢 Node.js</span> |
    <span>🔐 Passport.js</span> |
    <span>🌐 REST API</span>
  </p>

  <p>
    A modern web-based <b>Library Management System</b> designed for efficient management of 📖 books and 👤 users. 
    Built with <strong>⚛️ React</strong> frontend and <strong>🟢 Node.js</strong> backend, 
    featuring CRUD operations, 🔐 authentication, and 🕒 activity tracking.
  </p>

  <h2 id="overview">📝 1. Project Overview</h2>
  <p>
    Initialized with <b>Create React App</b>, this system provides a user-friendly interface connected 
    to a backend service. It manages 📚 library resources, 👥 users, and integrates secure authentication with 🔐 Passport.
  </p>

  <h2 id="features">✨ 2. Features</h2>
  <ul>
    <li>🎨 Responsive React frontend</li>
    <li>📝 CRUD operations for 📖 books & 👤 users</li>
    <li>🔐 Authentication via Passport.js</li>
    <li>🕒 Recent activity logging</li>
    <li>🆔 Unique ID generation for records</li>
    <li>💾 Database integration</li>
    <li>🧪 Testing with React Testing Library</li>
    <li>🚀 Production-ready builds</li>
  </ul>

  <h2 id="tech-stack">🛠 3. Tech Stack</h2>
  <table>
    <tr><th>⚙️ Layer</th><th>🔧 Technology</th></tr>
    <tr><td>💻 Frontend</td><td>⚛️ React (JavaScript, HTML, CSS)</td></tr>
    <tr><td>🔐 Authentication</td><td>Passport.js</td></tr>
    <tr><td>💾 Database</td><td>🟢 Node.js with DB connection</td></tr>
    <tr><td>🔗 API Clients</td><td>📖 bookAPI.js, 👤 userAPI.js</td></tr>
    <tr><td>🧪 Testing</td><td>React Testing Library, Jest</td></tr>
    <tr><td>🚀 Deployment</td><td>Create React App</td></tr>
  </table>

  <h2 id="getting-started">🚀 4. Getting Started</h2>
  <h3>✅ Prerequisites</h3>
  <ul>
    <li>🟢 Node.js (LTS)</li>
    <li>📦 npm</li>
  </ul>
  <h3>⚡ Installation</h3>
  <pre><code>git clone https://github.com/Kruparani08/library-management-system.git
cd library-management-system
npm install
npm start</code></pre>

  <h2 id="scripts">📜 5. Available Scripts</h2>
  <ul>
    <li><code>npm start</code> – ▶️ Start dev server</li>
    <li><code>npm test</code> – 🧪 Run tests</li>
    <li><code>npm run build</code> – 🏗 Build for production</li>
    <li><code>npm run eject</code> – ⚠️ Eject configuration</li>
  </ul>

  <h2 id="structure">📂 6. Directory Structure</h2>
  <pre><code>/public
/src
 ├── App.js
 ├── bookAPI.js
 ├── userAPI.js
 ├── db_connection.js
 ├── passportConfig.js
 ├── generateUID.js
 ├── recentActivity.js
 └── ...
.env
package.json</code></pre>

  <h2 id="config">⚙️ 7. Configuration</h2>
  <ul>
    <li><b>🌍 .env</b> – Environment variables</li>
    <li><b>💾 db_connection.js</b> – DB configuration</li>
    <li><b>🔐 passportConfig.js</b> – Auth strategies</li>
    <li><b>📖 bookAPI.js</b>, <b>👤 userAPI.js</b> – API handlers</li>
  </ul>

  <h2 id="api">🔗 8. API Endpoints (Proposed)</h2>
  <h3>📖 Books</h3>
  <ul>
    <li>GET /api/books – 📚 List all books</li>
    <li>POST /api/books – ➕ Add new book</li>
    <li>PUT /api/books/:id – ✏️ Update book</li>
    <li>DELETE /api/books/:id – 🗑 Delete book</li>
  </ul>
  <h3>👤 Users</h3>
  <ul>
    <li>GET /api/users – 👥 List users</li>
    <li>POST /api/users – 🆕 Register user</li>
    <li>PUT /api/users/:id – ✏️ Update user</li>
    <li>DELETE /api/users/:id – 🗑 Delete user</li>
  </ul>
  <h3>🔐 Authentication</h3>
  <ul>
    <li>POST /api/auth/login – 🔑 Login</li>
    <li>POST /api/auth/register – 🆕 Register</li>
  </ul>

  <h2 id="contribute">🤝 9. Contributing</h2>
  <ol>
    <li>🍴 Fork repository</li>
    <li>🌿 Create branch <code>feature/xyz</code></li>
    <li>💾 Commit changes</li>
    <li>📤 Push branch & open PR</li>
  </ol>

  <footer>
    <p>© 2025 📚 Library Management System | 📖 Documentation</p>
  </footer>
</main>

</body>
</html>
