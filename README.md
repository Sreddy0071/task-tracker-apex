
# 📋 Task Tracker – Oracle APEX Project

## Overview
Task Tracker is a web-based task management application built with **Oracle APEX**. It helps users organize tasks across projects, track progress, maintain due dates, and assign work with role-based access.

## 🌟 Features
- Create/update/delete tasks and projects
- Due dates with overdue task highlighting
- Task progress tracking (% complete)
- File uploads for each task
- Commenting system with task history
- Role-based access (Admin/User)
- Dashboard and visual reporting
- Fully exportable Oracle APEX app

## 📁 Project Structure
```
task-tracker-apex/
├── OracleApex_TaskTracker.sql   # Final APEX export
├── README.md                    # Project documentation
├── task_history.sql             # Table for task update logs
├── task_files.sql               # Table for file attachments
├── alter_tasks.sql              # Alters TASKS table for due date & percent complete
```

## 🏗️ Setup Instructions
1. Import `OracleApex_TaskTracker.sql` into your Oracle APEX workspace using App Builder → Import.
2. Run the application and login as an Admin user.
3. Use `task_history.sql`, `task_files.sql`, and `alter_tasks.sql` to set up supporting tables.

## 🛠 Tech Stack
- Oracle APEX 24.2.5
- PL/SQL, SQL
- APEX Interactive Reports and Forms

## 📬 Future Ideas
- Email reminders for due tasks
- Gantt chart for task dependencies
- REST API for mobile app integration

---

> Developed by Sowmya Likkidi | May 2025
