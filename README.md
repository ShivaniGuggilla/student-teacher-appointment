## 🗓️ Student-Teacher Appointment Booking System
A web-based application that allows students to book appointments with teachers, and provides admin functionalities to manage teacher profiles and approve appointments. Built using HTML, CSS, and JavaScript, with localStorage for data persistence.

## 🔧 Features
# 🔑 Login Portal
Login options for Admin, Student, and Teacher roles via a dropdown.

# 👨‍🏫 Admin Panel
Approve Appointments: View and approve pending appointment requests from students.

Manage Teachers: Add, update, and delete teacher records.

# 👩‍🎓 Student Interface
Book an appointment by selecting a teacher, specifying date/time, and providing a reason.

Teachers are dynamically listed from admin entries.

# 🧑‍🏫 Teacher Dashboard
Login by name.

Schedule new appointments manually.

View all appointments assigned to the teacher.

View student messages (if messaging is integrated).

# 🧱 Project Structure

📁 project-folder/
├── index.html                 # Main login selector (Admin/Student/Teacher)
├── admin.html                 # Admin dashboard to select student/teacher
├── adminstudent.html          # Admin view to approve appointments
├── adminteacher.html          # Admin view to manage teacher data
├── student.html               # Student view for booking appointments
├── teacher.html               # Teacher login and dashboard
├── style.css                  # Reusable global and component styling
## 🖥️ Tech Stack
Frontend: HTML, CSS, JavaScript

Storage: Browser's localStorage

## ⚠️ No backend or database is used. All data is stored in the browser and will reset on clearing site data.

## 🧪 How to Run
Download or clone the repository.

Open index.html in your browser.

Select a role to navigate to its respective dashboard.

Interact with forms to test functionality.
