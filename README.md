# 🎓 University Events and Clubs Management System

This project is a **SQL Server-based database system** designed to manage university events, student clubs, user interactions, and communications. It supports user roles (students, club leaders, admin), event organization, club enrollments, chats, and more.

---

## 📌 Features

- User and role management (Admin, Club Leaders, Students)
- Student club creation and enrollment
- Event management with participant tracking
- Private and group chat messaging
- Friend requests between users
- Feedback and ratings for events
- Club announcements via chat
- Ban and report system for moderation
- Notifications and activity logs
- Reminders for upcoming events

---

## 🧱 Database Schema Overview

**Main Tables:**
- `Users` — user info (name, contact, location)
- `UsersRoles` — role assignment (admin, student, club leader)
- `Clubs` — student organizations with leaders
- `ClubsEnrollment` — user memberships in clubs
- `Events` — organized by clubs, with start/end dates and location
- `EventParticipants` — tracks users attending events
- `EventFeedback` — users can leave comments on events
- `Notification` — user notifications with message and link
- `UserActivityLog` — logs user actions like joining events
- `Chat` — private messaging between users
- `ClubChat` — group messaging within clubs
- `Reminder` — user reminders for upcoming events
- `Report` — users reporting others
- `Bans` — ban records for moderation
- `FriendRequest` — friend request status between users

---

## ⚙️ Setup Instructions

1. Open **SQL Server Management Studio (SSMS)**.
2. Create a new database (e.g., `UniversityManagement`).
3. Run the provided `.sql` script to create tables and insert sample data.
4. Modify or extend the database as needed for your application.

---

## 📂 File Structure

- `schema.sql` — SQL script to create all tables.
- `sample_data.sql` — SQL script to insert sample users, clubs, events, and more.
- `README.md` — Project description.

---

## 🛠️ Technologies Used

- Microsoft SQL Server
- T-SQL (DDL + DML)

---

## 📧 Contact

For questions or collaboration, contact: **yourname@example.com**