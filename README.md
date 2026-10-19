# StudentSphere | Student Information Management Portal

A mobile-friendly student portal demo with sign in, student registration, generated permanent Student IDs, student dashboards, academic details, attendance, and an admin record manager.

## Quick demo accounts

- **Student ID:** `STU20260001`  
  **Password:** `student123`
- **Admin ID:** `ADMIN001`  
  **Password:** `admin123`

A second sample student is also included: `STU20260002` / `student123`.

## Deploy on GitHub Pages using an Android phone

1. Download and extract `student-management-system.zip`.
2. Open GitHub and create a repository named `student-management-system`.
3. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. Wait a minute or two and open the Pages URL shown in Settings → Pages.

You can also test it before publishing by opening `index.html` in a browser that allows local files, or use a static HTML preview service.

## What works

- Student sign in with ID or email
- Student sign up with automatically assigned unique ID
- Student and admin demo roles
- Student dashboard, personal profile, course details, attendance and subject marks
- Admin student search, view, edit and delete
- Responsive layout for phones
- Browser LocalStorage persistence

## Important limitations

This is a **front-end demonstration**, not a secure production system. Demo passwords are stored in browser LocalStorage and the admin role can be inspected or altered by a technically capable user. Data exists only in the current browser on the current device; it is not shared between users or devices. Do not use real passwords, medical records, or sensitive personal data.

GitHub Pages serves static files. It cannot compile or run Java backend code. A real multi-user portal needs a Java backend (for example Spring Boot), server-side authentication, and a hosted database.

## Java source

`StudentManagementSystem.java` is a simple console-based Java companion version. It can be run in an online Java compiler, but it is separate from the GitHub Pages web interface.
