# Simple ToDoList Web Application

This is a responsive **Simple ToDoList Web Application** that allows users to log in, view their daily tasks, mark tasks as completed, and receive feedback for completing tasks. The app is designed with modern web technologies such as **HTML**, **CSS**, **JavaScript**, and **Bootstrap** for a user-friendly interface.

---

## **Features**

1. **Login Authentication:**
   - Users can log in with the predefined credentials:
     - **Username:** `admin`
     - **Password:** `12345`
   - Validates login details and redirects to the ToDo page upon successful login using callback functions.

2. **ToDo List Management:**
   - Retrieves tasks from an external API (`https://jsonplaceholder.typicode.com/todos`).
   - Displays tasks in a clean and responsive layout.
   - Allows users to mark tasks as completed. 
   - Alerts the user with a **"Congrats! 5 Tasks have been Successfully Completed"** message using **Promises**.

3. **Responsive Design:**
   - Built with **Bootstrap** to ensure compatibility across devices.
   - Modern design with gradient backgrounds and card-based layouts.

4. **Logout Functionality:**
   - Logs the user out and redirects them back to the login page.

5. **Local Data Option:**
   - Optionally, the app can load tasks from a local JSON file instead of the external API.

---

## **Screenshots**

### **Login Page**
![Login Page Screenshot](path-to-your-login-page-image)

### **ToDo List Page**
![ToDo List Page Screenshot](path-to-your-todo-page-image)

---

## **Technologies Used**

- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript (ES6+)
  - Bootstrap 5

- **Backend (for local file handling):**
  - Node.js (optional)
  - `fs` module for reading JSON files

---

## **Installation and Setup**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/simple-todolist-app.git
   cd simple-todolist-app