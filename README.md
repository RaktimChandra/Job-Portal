# Job Portal

A full-featured Job Portal built with PHP and MySQL, providing separate interfaces for Admin, Employers, and Jobseekers.

## Features

### Admin
- Manage job categories
- Manage employers and jobseekers
- View and filter applied jobs
- Generate reports (date-wise, employer-wise, candidate-wise)
- Handle forgotten admin password

### Employers
- Register and manage employer profile
- Post new jobs and edit existing postings
- Search, filter, and view candidate profiles
- Shortlist, hire, or reject candidates
- View reports on candidates and applications

### Jobseekers
- Register and manage profile
- Upload and update resume
- Search and apply for jobs
- View history of applied jobs
- Update profile picture and account password

## Tech Stack

- **Backend:** PHP (procedural) with PDO (MySQL)
- **Database:** MySQL
- **Frontend:** HTML5, CSS3, Bootstrap, jQuery
- **Admin Template:** Codebase admin theme
- **Other:** Font Awesome, DataTables, FullCalendar, CKEditor, and various JS plugins

## Project Structure

```text
Job Portal PHP V2/
├── jobportal/              # Main application
│   ├── admin/              # Admin panel (Codebase template)
│   ├── employers/          # Employer dashboard
│   ├── includes/           # Shared config, header, footer
│   ├── css/, js/, images/, fonts/  # Assets
│   └── *.php               # Front-facing pages (home, search, auth, etc.)
├── SQL File/jobportal.sql  # Database schema & sample data
├── Readme.txt              # Original setup notes
└── .gitignore              # Git ignore rules
```*
