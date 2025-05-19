# 📝 Permalist – The Persistent To-Do List

**Permalist** is a simple yet powerful to-do list web application that helps you stay organized by allowing you to create, edit, and delete tasks. Built with Node.js, Express.js, and PostgreSQL, Permalist ensures your tasks are always saved and accessible.

![image](https://github.com/user-attachments/assets/4fd35ad2-0980-4ce6-980a-d8c4a31226f3)


---

## ✨ Features

- ✅ **Create Tasks**: Add new tasks to your to-do list.
- ✏️ **Edit Tasks**: Modify existing tasks to keep them up to date.
- 🗑️ **Delete Tasks**: Remove tasks that are no longer needed.
- 💾 **Persistent Storage**: All tasks are stored in a PostgreSQL database, ensuring data is saved even after server restarts.

---

## 🛠 Technologies Used

- **Backend**: Node.js with Express.js
- **Database**: PostgreSQL
- **Templating Engine**: EJS (Embedded JavaScript)
- **Middleware**: Body-parser for handling form data

---

## 📁 Project Structure

```
Permalist/
├── public/
│ └── styles/
│ └── style.css
├── views/
│ ├── index.ejs
│ └── partials/
│ └── header.ejs
├── index.js # Main server file
├── package.json # Project metadata and dependencies
└── README.md # Project documentation
```

## ⚙️ Setup Instructions

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [PostgreSQL](https://www.postgresql.org/)

### 1. Clone the Repository

```bash
git clone https://github.com/aryan-0069/Permalist.git
cd Permalist
```

### 2. Install Dependencies
```bash
npm install
```
### 3. Set Up PostgreSQL Database
Create a new database named permalist.

Run the SQL script schema.sql in the repository to create the necessary table.

### 4. Configure Database Connection
Open index.js and update the database configuration details (user, host, password) to match your PostgreSQL database settings.

### 5. Start the Server
```bash
npm start
```

### 6. Access the Application
- Open your web browser and navigate to http://localhost:3000 to access the application.

