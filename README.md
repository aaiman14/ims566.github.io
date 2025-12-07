Library System README & Instructions
1. Project Overview
This project is a simple web-based Library System consisting of login, dashboard, eBooks, journals, and articles pages. It includes dark mode, charts, and basic navigation.
2. File Structure
• login.html – Login page for users
• index.html – Main dashboard/homepage
• ebooks.html – E‑Books collection page
• journals.html – Journal listings + chart
• articles.html – Articles page with search
• style.css – Shared styling
• image/ – Folder for book images
3. How to Run the Project
1. Download or extract the project folder.
2. Make sure all HTML files, CSS, and images stay inside the same directory.
3. Open Visual Studio Code.
4. Go to File → Open Folder → select the project folder.
5. Right‑click index.html → Open With Live Server (recommended).
6. If Live Server is not installed, open each HTML with your browser manually.
4. How Login Works
The login page checks for a fixed Student ID and Password:
• ID: 20220001
• Password: 123456

You can update these inside login.html under the login() function.
5. Features
• Mobile‑responsive layout
• Sidebar navigation menu
• Dark Mode toggle (saved using localStorage)
• Visitor bar chart (Chart.js)
• E‑Books grid display
• Journal pie chart
• Search filter for articles
6. Editing or Adding Content
• Add new eBooks → edit ebooks.html
• Add new journals → edit journals.html
• Add new articles → edit articles.html
• Change design → edit style.css
