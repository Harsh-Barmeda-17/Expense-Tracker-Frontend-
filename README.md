Frontend Internship Project Documentation
Expense Tracker – Personal Finance Web App
________________________________________
1. Introduction
The Expense Tracker is a fully frontend web application built using HTML, CSS, and JavaScript. It allows users to track their income, expenses, and budgets in a clean and interactive interface.
Core Features
•	✅ Interactive Dashboard
•	✅ Transaction Management
•	✅ Budget Tracking
•	✅ Visual Reports (Pie, Bar, Line Charts)
•	✅ Dark/Light Mode Toggle
•	✅ Fully Responsive Design

________________________________________
2. Project Structure (Frontend Only)
The app includes four static HTML pages, each sharing styling and scripting for a cohesive experience:
              Page	Description	Key Features
Dashboard (index.html)	Financial overview	Balance summary, recent transactions, pie chart
Add Transaction (add-transaction.html)	Input new records	Form validation, category dropdown, sound feedback
Transactions (transactions.html)	View/edit history	Filtering, search, undo delete, budget management
Reports (reports.html)	Data visualization	Pie/bar/line charts for spending insights
________________________________________


3. Key Frontend Features
3.1 Dashboard (index.html)
•	Real-time balance calculation (Income - Expenses)
•	Monthly summary (Income vs. Expenses)
•	Quick action buttons (Add, View Reports)
•	List of recent transactions (last 3 entries)
•	Expense breakdown using Chart.js (pie chart)
 
3.2 Add Transaction (add-transaction.html)
•	Validated form (required fields, numeric input)
•	Dynamic category dropdown
•	Recurring transaction toggle switch
•	Audio feedback (separate sounds for income & expense)
         
3.3 Transactions (transactions.html)
•	Filter by type, category, and date
•	Live search (instant results while typing)
•	Edit/Delete with undo toast
•	Budget Manager with progress bars per category
 
3.4 Reports (reports.html)
•	Pie Chart – Expense distribution by category
•	Bar Chart – Monthly income vs. expenses
•	Line Chart – Net balance trend
•	Responsive and adaptive charts
 
________________________________________



4. Technical Implementation (Frontend Focus)
4.1 Core Technologies Used
Technology	             Usage
HTML5	             Semantic structure, forms, modals
CSS3	             Flexbox, Grid, theme variables, animations
JavaScript (ES6+)	             Dynamic UI, localStorage, Chart.js integration
Chart.js	             Visual reports – pie/bar/line charts
Font Awesome	             Icons for UI elements
Google Fonts	             Rubik (UI text) + Quicksand (headings)
4.2 Dynamic UI Features
•	Dark/Light Mode Toggle
o	Uses CSS variables
o	Saves preference to localStorage
•	Toast Notifications
o	Animated alerts for actions
•	Modals
o	For budget setup, help guide, category manager
•	Responsive Layouts
o	Mobile-first design using Flexbox/Grid


4.3 JavaScript Highlights
 
4. Chart.js Integration
 


________________________________________




5. Responsive Design Approach
Mobile-First Design
•	One-column layout on small screens
•	Grid/Flex layouts adapt to tablets and desktops
Adaptive Charts
•	Legends reposition for smaller viewports
•	Charts scale without distortion
Touch-Friendly UI
•	Large tap targets
•	Vertical lists optimized for mobile gestures
________________________________________


6. User Interaction Flow
•	Add a Transaction
Fill form → Play sound → Show toast → Redirect to Dashboard
•	Edit/Delete
Edit opens modal → Save changes
Delete triggers undo toast (visible for 5 seconds)
•	Set Budgets
Open modal → Select category → Set amount → Updates progress bars
•	View Reports
Navigate to reports → Charts update with real-time data
________________________________________
7. What Makes This Project Stand Out?
✨ No Backend Required – All logic runs on the frontend via localStorage
✨ Polished UX – Audio feedback, modals, undo actions
✨ Professional Data Visualization – Built with Chart.js
✨ Fully Responsive – Works seamlessly on mobile, tablet, and desktop devices
________________________________________
8. Future Frontend Improvements
•	Export data to CSV
•	Offline functionality with Service Worker (PWA)
•	Weekly spending trend charts
•	Accessibility improvements (screen reader & keyboard navigation)
________________________________________
9. Final Notes
This project demonstrates strong frontend capabilities in:
•	✔ DOM Manipulation
•	✔ Responsive Web Design
•	✔ Data Visualization
•	✔ User-Centered Design
________________________________________
10. Project Links
•	🔗 Hosted Link: https://expense-tracker-h.netlify.app
•	💻 GitHub Repository: https://github.com/Harsh-Barmeda-17/Expense-Tracker-Frontend-
