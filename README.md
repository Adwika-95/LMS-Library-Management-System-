📚 Smart College Library Management System – Frontend
🧠 Overview
This is the frontend interface for my C++-based Library Management System (LMS) project.
It provides a visual representation of how different users — students, faculty, research scholars, and the library dean — interact with the digital library.
* While the backend (C++) manages actual data and file handling, this frontend made with HTML and CSS helps present the project attractively and clearly during demonstrations.

💻 Tech Stack
HTML5 – Structure & content
CSS3 – Styling, layout & animations
(Backend logic implemented separately in C++)

🌟 Key Features (Frontend + Backend Integration)
Multi-User Login Interface
Supports four roles: Student, Faculty, Research Scholar, and Library Dean.
Each role has different access rights.
Book Management System
View available books with details (Title, Author, Subject, Availability).
Issue Book feature — generates automatic due date (7 days).
Return Book system with fine calculation (₹2 per late day).
Auto popularity tracker for “Most Issued” books.
Reference Books Section
Subject-wise list of reference books with their floor locations.
Helps users quickly find assigned textbooks for each course.
Best-Selling Books
Displays top 5 most borrowed books.
Based on popularity data tracked in the backend.
Fine Calculator
Simple calculator for delayed returns.
Interactive design to show fines in real-time.
Admin (Dean) Controls
Add, update, or remove books directly from the system.
Monitor book trends and user activity.

🧩 Folder Structure
Frontend/
├── index.html
├── login.html
├── dashboard.html
├── best_sellers.html
├── reference.html
├── fine_calculator.html
├── style.css
└── Libraryaes.jpg 
🧰 How to Run
Clone or download this repository.
Open index.html in your web browser.
Explore pages like Dashboard, Best-Selling Books, and Fine Calculator to visualize backend functionalities.
Run the C++ backend program (main.cpp) in Dev C++ to see real-time data management, file handling, and book issue/return simulation.
🧩 Backend Summary (C++)
The backend handles:
Book data storage using file handling
Issue/return logic
Fine calculation
Popularity tracking
Admin privileges for managing inventory
All data is stored in .txt files, ensuring information is persistent across runs.

🚀 Future Scope
Connect frontend and backend via a web API or local database.
Add JavaScript for dynamic updates (fine calculation, live issue list).
Enable real login authentication and cloud book storage.
