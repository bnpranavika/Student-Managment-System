📋 Student Management System – Summary
The Student Management System is a client-side web application built using HTML, Bootstrap, and JavaScript, providing a simple and responsive interface for managing student data entirely in the browser.

🧱 Core Features & Structure
HTML (index.html):

Uses Bootstrap for layout and responsiveness.

Contains a top navbar and a dynamic <div id="app"> for loading different views (Home, Add Student, All Students).

Routing (Single Page Navigation):

A routes object defines the HTML for each page.

navigate(page) dynamically switches content without page reload.

Add Student:

The addStudent() function captures form data and saves it to studentList.

Automatically updates localStorage and redirects to the student list.

Display Student Data:

renderStudentTable() reads from studentList and dynamically generates a table.

Updates every time the "All Students" page is loaded.

Delete Student:

deleteStudent(index) removes a student by index, updates storage, and re-renders the list.

💾 Storage & Persistence
LocalStorage:

saveToStorage() stores student data as a JSON string.

loadFromStorage() retrieves the data on page load.

🎨 Styling with Bootstrap
Utilizes Bootstrap 5 for:

Layout grid system

Forms and buttons

Tables and UI components

Delivers a clean, modern, and responsive design with minimal custom CSS.

🌐 Client-Side App (No Backend)
Entirely browser-based:

No server-side scripting or database.

Works offline.

Perfect for demos, practice, or small offline record-keeping systems.

🧩 Extendable Architecture
Easy to expand with:

Edit or Search features

Sorting by name, ID, etc.

Export/Import options
![image](https://github.com/user-attachments/assets/ffd166fe-c232-411f-87a4-0b9bbfc86a83)
![image](https://github.com/user-attachments/assets/4a1141c2-7f93-47c6-ac90-5a8fe9bcaf8a)
