StackStories 📚
StackStories is a dynamic and responsive full-stack blogging application built using the MERN (MongoDB, Express.js, React, Node.js) stack. It provides a platform for users to write, edit, and explore blog posts with a seamless user experience and modern UI.

🚀 Features
🔐 User Authentication: Secure sign-up and login using JWT.

✍️ Create/Edit/Delete Blogs: Write rich blog posts using a Markdown editor.

🧾 View Blog Posts: Browse through all user blogs or filter by specific users.

💬 Comment System: Engage with content through comments (basic feature).

🎨 Responsive UI: Built with Tailwind CSS for mobile-friendly performance.

🌗 Dark Mode Support: Toggle between light and dark themes.

📦 RESTful APIs: Clean and scalable backend design.

🛠️ Tech Stack
Frontend:

React.js

Tailwind CSS

React Router

Markdown Editor

Backend:

Node.js

Express.js

MongoDB & Mongoose

JWT for Authentication

🧑‍💻 Getting Started
🔧 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/stackstories.git
Navigate to the project:

bash
Copy
Edit
cd stackstories
📦 Start Backend
bash
Copy
Edit
cd api
npm install
nodemon index.js
🎨 Start Frontend
bash
Copy
Edit
cd client
npm install
npm start
📁 Folder Structure
bash
Copy
Edit
stackstories/
│
├── api/              # Express backend
│   ├── routes/       # API routes
│   ├── models/       # Mongoose schemas
│   └── controllers/  # Logic handlers
│
├── client/           # React frontend
│   ├── components/   # UI components
│   ├── pages/        # Page views
│   └── utils/        # Helpers
💡 Future Enhancements
Profile image uploads

Blog search & tags

Like & bookmark features

Admin panel for moderation

Comment threading

🙌 Authors
Amit Garg

📃 License
This project is licensed under the MIT License.
