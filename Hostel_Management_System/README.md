# Hostel Management System

A responsive college mini project built with HTML, CSS, and vanilla JavaScript. It runs in a web browser and stores records in `localStorage`; no backend, database, framework, or package installation is required.

## Run the project

1. Extract the repository ZIP.
2. Open the `Hostel_Management_System` folder.
3. Double-click `index.html`, or open the folder in Visual Studio Code and open `index.html` in a browser.

The dashboard starts with sample records. Changes are saved in the browser automatically. Clearing browser storage removes saved changes and restores the sample records on the next load.

## Features

- Dashboard summaries for students, rooms, occupied beds, available beds, room occupancy, and pending fees.
- Student create, view, update, delete, search, and room/course filtering.
- Room create, view, update, delete, capacity tracking, and occupied-bed validation.
- Fee balances calculated from monthly fees and payments for the current month.
- Complaint logging, editing, deletion, search, category and status filters, and Open / In progress / Resolved tracking.
- Payment recording with date and method, plus a recent transaction list.
- Responsive layout for desktop and mobile.

## Project files

- `index.html` — page structure and application sections.
- `style.css` — responsive layout, components, and visual styling.
- `script.js` — sample data, localStorage persistence, validation, complaint status handling, and interactions.

## Notes

This is a front-end academic demonstration. Data is stored only in the current browser on the current device. For a multi-user hostel system, authentication, server-side validation, and a shared database would be needed.
