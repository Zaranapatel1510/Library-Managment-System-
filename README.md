📚 Library Management System
<br>
HTML • CSS • JavaScript • Bootstrap • localStorage
A browser-based Library Management System built with HTML, CSS, JavaScript, and Bootstrap, using localStorage for data persistence. This project provides an efficient platform for managing core library operations, including user authentication, book borrowing/return, payments, and request handling.


✨ Features
🔑 User Authentication
- Secure login and registration system for both users and administrators
- Admin login requires username, password, and PIN
  
👤 User Profiles & Actions
- Register new users automatically if login fails
- Browse books with PDF/Video resources
- Borrow books by selecting a date and completing a payment simulation
- Track borrowed books with due dates, return option, and delete/unborrow functionality
- Request unavailable books
  
📊 Admin Dashboard
- View total books, available count, borrowed count, and payments overview
- Manage books: add/update/delete with resource links
- Review and approve user requests
- Secure logout
  
💻 Responsive UI
- Built with Bootstrap for a clean, modern interface
- Works smoothly across devices

🗄 Storage
- localStorage used for simulating backend operations
- Stores users, books, borrows, payments, and requests



📂 Project Structure
.
├── alllogin.html           # Landing page (Admin/User buttons)
├── admin.html              # Admin login (username, password, PIN)
├── login.html              # User login
├── register.html           # User registration
├── 3.html                  # Admin metrics, book CRUD, requests, payments


└── css/
    ├── 1.css               #Userdashboard
    └── 3.css               # Admin UI

🔒 Security & Validations
- Admin PIN for extra security
- Form validations (required fields, email format, password length)
- Access control: block unauthorized page access
- Data integrity: update availability on borrow/return


🌟 Future Improvements
- Node.js backend with Express + MongoDB/PostgreSQL
- Real payment integration (Stripe/Razorpay)
- Email alerts for due dates & requests
- Role-based RBAC permissions
- Reporting & export (CSV/PDF)

⚠️ Limitations
- Local-only storage (data resets per browser/device)
- Mock payments (no real gateway)
- No server-side authentication (demo/academic use only)

 
🤝 Contributing
- Issues: Bug reports, feature requests
- Pull requests: Fork → branch → commit → PR

🖼 Screenshots
ALL LOGIN 

<img width="2516" height="1308" alt="image" src="https://github.com/user-attachments/assets/d17a62c6-31e9-4536-94cd-173da66edca0" />

USER DASHBOARD

<img width="2498" height="1337" alt="image" src="https://github.com/user-attachments/assets/467c3a0b-aab9-46f2-a7a1-c10cf7ea91eb" />


ADMIN DASHBOARD 
<img width="2534" height="1338" alt="image" src="https://github.com/user-attachments/assets/eeb00f7b-acd4-446b-969c-9911af53a5f9" />




