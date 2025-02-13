# HRMS Website

This repository contains a simple HRMS (Human Resource Management System) website built with HTML, CSS, and JavaScript. The site allows employees to log their punch-in, lunch, and punch-out times, and it provides an admin view to see all employee logs and export the data to Excel.

## Features

- **Employee View:**
  - Enter your name and log your punch times.
  - The log for the current day is displayed in a table.
  
- **Admin View:**
  - Accessible by clicking the **Admin** link.
  - Requires a passkey (`135520`) to access.
  - Displays logs for all employees.
  - Option to export data as an Excel file using the XLSX library.

## How to Use

1. **Employee View:**
   - Open `index.html` in your browser.
   - Enter your name and start logging your punch times.
  
2. **Admin View:**
   - Click on the **Admin** link in the navigation bar.
   - Enter the passkey `135520` when prompted.
   - View all records and export data as needed.

## Hosting on GitHub Pages

1. Create a GitHub repository and add these files.
2. In your repository, navigate to **Settings > Pages**.
3. Select the branch (e.g., `main`) and the root directory for publishing.
4. GitHub Pages will provide a URL where your site is live.

## License

This project is licensed under the [MIT License](LICENSE).
