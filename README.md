# Student Management System

A responsive student management dashboard built with **HTML, CSS, and JavaScript**. It lets an administrator manage students, courses, and marks, and generate printable marksheets. All data is stored in the browser using `localStorage`, so no backend or database is needed.

## Description

The Student Management System is a front-end project that simulates a real admin dashboard for an educational institution. After logging in, the administrator can view student statistics, add and edit student records, enter subject marks, generate marksheets with automatic grading, and manage the list of courses. The project demonstrates DOM manipulation, form handling, and data persistence with `localStorage`.

## Features

- **Authentication**: user registration and login, show/hide password toggle, and a logout page
- **Dashboard**: total, active, and inactive student counts, total courses, quick action cards, and a recent students table
- **Student management**: add, view, edit, and delete students, with search and filter options
- **Course management**: add, view, and delete courses (name, code, duration, department)
- **Marks management**: enter internal and external marks per student and subject, with automatic total and grade
- **Marksheet generation**: select a student and generate a printable marksheet with an overall grade
- **Settings**: change the administrator password and clear all locally stored data
- **Sample data**: preloaded students, courses, and marks so the app is usable right away
- **Print-friendly marksheet** using print styles

## Grading Scale

| Total Marks | Grade |
|-------------|-------|
| 90 and above | A+ |
| 80 – 89 | A |
| 70 – 79 | B |
| 60 – 69 | C |
| 50 – 59 | D |
| 40 – 49 | E |
| Below 40 | F |

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Browser `localStorage` for data persistence

## Project Structure

```
Student_Management_System/
├── login.html          # Login page
├── register.html       # Create account page
├── logout.html         # Logged out confirmation page
├── dashboard.html      # Dashboard with statistics and recent students
├── students.html       # View, search, and filter students
├── add-student.html    # Add / edit student form
├── courses.html        # Manage courses
├── marks.html          # Enter and view marks
├── marksheet.html      # Generate and print marksheets
├── settings.html       # Change password and clear data
├── css/
│   └── style.css       # Styling for all pages
├── js/
│   └── script.js       # Application logic
└── README.md
```

## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/your-username/Student_Management_System.git
```
2. Go to the project folder:
```bash
   cd Student_Management_System
```
3. Open `login.html` in your web browser.

## Demo Login

| Username | Password |
|----------|----------|
| admin    | admin123 |

You can also create your own account from the **Register** page.

## How It Works

1. Log in with the demo admin account or a registered account.
2. Use the sidebar to move between Dashboard, Students, Add Student, Marks, Marksheet, Courses, and Settings.
3. All changes are saved in the browser's `localStorage` and remain after a page refresh.
4. Use **Settings > Clear All Data** to reset the app to its default sample data.

## Notes

- This is a learning/demo project. Data is stored only in your browser, not on a server.
- Passwords are stored as plain text in `localStorage`, so do not use real passwords.
- Clearing your browser data will remove all saved records.

## Future Improvements

- Add a backend (Node.js, Python, or PHP) with a database
- Hash passwords and add secure authentication
- Add attendance tracking
- Export marksheets as PDF
- Add charts to the dashboard

## Author

**Your Name**
GitHub: [@your-username](https://github.com/your-username)
