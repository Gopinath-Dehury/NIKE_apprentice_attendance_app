# NIKE_apprentice_attendance_app

This is an attendance tracking application designed for NIKE apprentices. It helps manage and monitor attendance records for training programs and workshops.

## How it Works

The application provides a simple web interface for attendance tracking:

1. **Check-in/Check-out**: Apprentices enter their full name and click "CHECK IN" or "CHECK OUT" buttons
2. **Time Recording**: The system automatically captures the current time and sends it to the backend
3. **Data Storage**: Attendance records are stored in a Google Sheets database via Google Apps Script
4. **Admin View**: Authorized administrators can view a monthly attendance grid showing presence/absence for all students
5. **Time Details**: Hovering over "P" (Present) cells shows the exact check-in and check-out times

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Google Apps Script (serverless)
- **Database**: Google Sheets
- **Styling**: Custom CSS with responsive design
- **Deployment**: Static web hosting (can be deployed on any web server or GitHub Pages)

