👨‍💼 Employee Management System  

This project is a React-based Employee Management System with role-based login functionality, designed to manage and track tasks between managers and employees. It follows a clean component-based architecture and provides a smooth user experience without requiring a backend.

🚀 Overview    

The system includes two main roles — Manager and Employee.
Managers can assign and monitor tasks, while employees can accept and track their task progress. A role-based login system ensures that each user accesses only their respective panel. All data is stored using localStorage, enabling persistence across sessions.

🛠️ Tech Stack  

React.js – For building reusable UI components  
JavaScript (ES6+) – Core logic and interactivity  
HTML5 & CSS3 – Layout and styling  
Local Storage API – Client-side data persistence  

✨ Features  

🔐 Role-Based Login
Separate login system for Manager and Employee  
Access control based on user role  
Session-like behavior using localStorage  

👨‍💼 Manager Panel
Assign tasks to employees    
Track task status  
Monitor employees performance and progress  

👨‍🔧 Employee Panel
View assigned tasks  
Track task status  

<img width="1914" height="944" alt="Screenshot 2026-03-22 072430" src="https://github.com/user-attachments/assets/97522e64-d931-4c27-8a28-0471ffde5475" />
<img width="1892" height="936" alt="Screenshot 2026-03-22 072406" src="https://github.com/user-attachments/assets/273e49e4-0931-4e88-ae42-37642ff47061" />
<img width="1899" height="1019" alt="Screenshot 2026-03-22 074022" src="https://github.com/user-attachments/assets/0f0792e6-a837-4ef3-9b8a-6e2f9a414cdc" />


🌟 General Features  

Two-panel system (Manager & Employee)  
Persistent data without backend  
Real-time UI updates using React state  
Clean and responsive design  

📚 What I Learned  

Implementing role-based access in frontend applications  
Managing complex state and data flow in React  
Designing multi-user interfaces with different permissions  
Handling CRUD operations and task workflows  
Using localStorage for maintaining application state  

▶️ Getting Started  
# Clone the repository
git clone https://github.com/bharat258025/employee-management-system.git

# Navigate into the project directory
cd ems

# Install dependencies
npm install

# Run the app
npm run dev

The application will run at: http://localhost:5173

📌 Future Improvements    
Backend integration for secure authentication  
Database support (MongoDB / Firebase)  
Real-time updates using APIs  
Advanced dashboard with analytics and reports  
