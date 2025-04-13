📚 OLMS – Online Learning Management System

An academic DBMS project that demonstrates the creation and management of a scalable online education platform using MySQL. This system facilitates tracking of students, teachers, courses, enrollments, assignments, exams, and more, making it a robust model for educational institutions.

🛠️ Project Overview

OLMS (Online Learning Management System) is a relational database project built with MySQL that simulates the backend operations of an e-learning portal. The database supports:
- Instructor and student management
- Course creation and enrollment
- Assignment submissions and exam results
- Discussion forums
- Role-based access control for admins, professors, and students

📌 Features
- Comprehensive database schema with normalization
- DDL, DML, DCL, and TCL command implementation
- Advanced SQL queries with aggregate functions
- Access control using MySQL users and privilege management
- Transaction handling with commit, rollback, and savepoints
- ER Diagram and relational schema modeling

🧱 Database Schema -

Main Entities:
- `Instructor`  
- `Course`  
- `Student`  
- `Assignment`  
- `Submission`  
- `Exam`  
- `Exam_result`  
- `Enrollment`  
- `Discussion_post`

# ER Diagram:
Includes relationships like:
- Instructors teach Courses
- Students enroll in Courses
- Students submit Assignments
- Exams are associated with Courses
- Students receive Exam Results
- Forum posts are linked to Courses and Students


📂 SQL Implementation

# DDL Commands
- `CREATE`, `ALTER`, `DROP`, `RENAME`, `TRUNCATE` for defining schema
- Extensive use of constraints like `PRIMARY KEY`, `FOREIGN KEY`, `CHECK`, and `UNIQUE`

# DML Commands
- `INSERT`, `UPDATE`, `DELETE` and `SELECT` operations across all major tables

# Aggregate Functions
- `SUM`, `AVG`, `MAX`, `MIN`, `COUNT`, and `GROUP_CONCAT` for performance insights

# DCL Commands
- `GRANT`, `REVOKE` for role-based access to `admin`, `professor`, and `student`

# TCL Commands
- `START TRANSACTION`, `COMMIT`, `ROLLBACK`, `SAVEPOINT` for safe data operations


🔐 User Roles & Privileges

 Role         Permissions 
---------------------------------------------------------------------------
 Admin      : Full access to all tables 
 Professor  : Read/write access to course-related tables |
 Student    : Read access + limited write to assignments and discussions |



💡 Future Scope

- Integration of AI for personalized learning
- VR support for immersive content delivery
- Mobile-first design for broader accessibility
- Predictive analytics for student performance
- Gamification features

🎓 Learning Outcomes

- Mastery of SQL (DDL, DML, DCL, TCL)
- Database design & normalization
- Complex queries and performance optimization
- Role-based security implementation
- Real-world application of DBMS concepts in education




👩‍💻 
- Nitika Sinha
- UID: 23BCA10182


  
