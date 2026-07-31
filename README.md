# Full-Stack Web Application

A full-stack web application built following modern web development practices. This project includes user authentication, custom CSS/SCSS styling, RESTful API endpoints tested via Postman, and environment configuration for secure credentials.

---

## 🛠️ Tech Stack

* **Front-end**: HTML5, CSS3 / SCSS, JavaScript
* **Back-end**: Node.js, Express.js (or equivalent framework)
* **Database / Services**: Environment configurations (`.env`)
* **API Testing**: Postman

---


# Screenshots


<img width="1920" height="1080" alt="Screenshot (166)" src="https://github.com/user-attachments/assets/77df2a40-6b16-4d86-aaf6-494593a3763d" />
#


<img width="1920" height="1080" alt="Screenshot (167)" src="https://github.com/user-attachments/assets/82e457b1-9488-4096-803b-d1b82026e047" />

#

<img width="1920" height="1080" alt="Screenshot (168)" src="https://github.com/user-attachments/assets/76f889fc-ea61-4c98-8ba1-4b4a590727f8" />

#

## 📁 Project Structure

```text
.
├── css/                  # Custom CSS / SCSS styling
├── js/                   # Front-end JavaScript files
├── routes/ / controllers/# API routing and backend logic
├── .env.example          # Template for environment variables
├── .gitignore            # Files ignored by git (e.g., .env, node_modules)
├── index.html            # Primary entry HTML file
├── server.js             # Main backend server entry point
└── README.md             # Project documentation
⚙️ Environment Variables (.env)
To run this project locally, you need to configure your environment variables:

1. Create a .env file in the root directory.

2. Add your credentials (refer to .env.example if available):
PORT=5000
DATABASE_URL=your_database_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_gmail_id@gmail.com
EMAIL_PASS=your_gmail_app_password

🚀 Getting Started Locally
1. Clone the Repository
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
2. Install Dependencies
npm install
3. Start the Server

npm start
# or for development mode:
npm run dev

📮 API Testing with Postman
You can test the backend endpoints using Postman:

BASE URL: http://localhost:5000

Authentication: Send JWT token in Headers if required (Authorization: Bearer <TOKEN>).

Sample Endpoints:

POST /api/auth/register - Create a new account.

POST /api/auth/login - Authenticate user & receive token.

GET /api/data - Fetch protected resource data.

💡 Key Learnings & Challenges
Environment Setup: Configured .env variables securely for service credentials (Gmail, API keys).

API Testing: Used Postman to construct and verify HTTP requests, headers, and JSON payloads.

UI Styling: Structured custom CSS to ensure consistent layouts across screen sizes.
