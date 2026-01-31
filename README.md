#  📚 Book Manager – CRUD API with Node.js & Express
A simple CRUD-based REST API built with Node.js and Express, designed to manage a book collection stored in a JSON file.
This project demonstrates backend fundamentals such as routing, data persistence, and API–frontend interaction.

### 📖 Project overview

The Book Manager API allows users to create, read, update, and delete book records through RESTful endpoints. <br>
The project also includes a basic user interface to interact with the API and manage books visually.

---
### 🎯 Features
- Allows users to create, read, update, and delete book information (CRUD).
- Persistent storage using a JSON file.
- Each book includes the following information:
  - Title
  - Author
  - Genre
  - Language
  - Price
  - Availability
  - Rating.
- Edit and delete actions available from the UI.
- Real-time updates between UI and backend.

---
### 🛠️ Technologies Used
- **Node.js**: Runtime environment used to build the backend.
- **Express.js**: A Node.js framework for handling routes and middleware.
- **JSON**: Used as a database to store and update book information.
- **HTML5**: Structure for the user interface.
- **CSS3**: Visual styling.
- **JavaScript**: Handles logic and user interactions.

---
🧩 Project structure
```
📁 BookManagerAPI
│
├── 📁 assets
│   └── *.png/*.webp        # UI and results screenshots
│
├── 📁 data
│   └── libros.json         # JSON file used as a lightweight database
│
├── 📁 frontend
│   ├── index.html          # Main user interface
│   ├── styles.css          # Frontend styles
│   └── main.js             # Frontend logic and API interaction
│
├── 📁 routes
│   └── userRoutes.js       # CRUD API routes for book management
│
├── .gitignore              # Ignored files and folders
├── index.js                # Express server configuration and entry point
├── package-lock.json       # Dependency lock file
└── package.json            # Project metadata and dependencies
```

---
### 🛣️ API Endpoints (CRUD)
| Method   | Endpoint            | Description                         | Example Usage                                      |
|----------|---------------------|-------------------------------------|--------------------------------------------------|
| **GET**      | `/libros`           | Retrieves all books                 | -                                                |
| **GET**      | `/libros/:id`       | Retrieves a specific book by its ID | `/libros/1`                                      |
| **POST**     | `/libros`           | Creates a new book                  | `{"title": "1984", "author": "George Orwell"}`   |
| **PUT**      | `/libros/:id`       | Updates an existing book by its ID  | `/libros/1` with body `{"title": "New Title"}`   |
| **DELETE**   | `/libros/:id`       | Deletes a book by its ID            | `/libros/1`                                      |

---
### 🟰 User's interface

<img src="assets/Interfaz.png" alt="User Interface">
<img src="assets/ModalEditarInfo.png" alt="Modal Interface" style="width:500px;">

---
### ⚙️ Instalation
1. Clone this repository:
   ```
   git clone https://github.com/DonLuisM/BookManager.git
   cd BookManager
   ```
2. Install dependencies
   ```
   npm install
   ```
3. Start the server
   ```
   npm run dev
   ```

---
### 👨‍💻 Author

Luis Muñoz <br>
🔗 GitHub: [@DonLuisM](https://github.com/DonLuisM)


