# 🛠️ Leave Management System Flutter X Golang X MSSQL

A modern leave management system built with **Flutter**, **Golang**, and **MSSQL Server**.  
Designed with role-based access control, secure session handling, and an intuitive user experience.

---

## 🚀 Stack

- **Frontend**: Flutter  
- **Backend**: Golang  
- **Database**: MSSQL Server

---

## 🔐 Session Management

- Sessions expire **3 minutes** after login.  
- After expiration, users are redirected to the **login screen**.  
- **Automatic logout** on inactivity.  
- All login processes include **comprehensive error handling**.  
- Server responses deliver **clear success/failure messages**.

---

## 👥 User Roles

### 👨‍💻 Developer
- Full access across all users and departments.

### 👩‍💼 Manager
- Access limited to users within their department.  
- Can send announcement messages to their department.

### 👤 Employee
- Can only view their own information.  
- Can submit leave requests.

---

## 📆 Leave Request System

- Employees can only submit a **new leave request** if there is **no pending request**.

### If a request is pending:
- Orange warning is displayed on the form.  
- Submit button is **disabled** (gray).  
- Clicking the button shows a **snackbar warning**.

### If no request is pending:
- Submit button is **blue and active**.

**Security**:  
Submit button remains disabled until the user’s leave data is fully loaded to prevent accidental submissions.

---

## 🏢 Department System

- Every user belongs to a specific department.  
- Developers and Managers can send announcement messages to departments.

---

## 💬 Announcement Module

- Internal messaging system used exclusively for **announcements**.
- Allows:
  - **Department-based announcements**
  - **Company-wide corporate communication**

---

## 🎬 Trailer

[![Watch the demo](https://img.youtube.com/vi/YFxJGhBSA8o/hqdefault.jpg)](https://www.youtube.com/watch?v=YFxJGhBSA8o)

---

