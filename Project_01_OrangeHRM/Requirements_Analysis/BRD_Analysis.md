# BRD Analysis – OrangeHRM Web Application

## 1. Application Overview

OrangeHRM is a web-based Human Resource Management System designed to manage employee-related activities such as employee records, leave management, role administration, and system configuration.

The system supports multiple user roles such as Admin and Employee with role-based access control.

---

## 2. Business Objectives

- Maintain centralized employee records
- Manage employee leave efficiently
- Provide secure role-based access
- Improve HR workflow automation
- Reduce manual HR errors

---

## 3. Stakeholders Identified

- HR Administrator
- System Administrator
- Employees
- Management Team

---

## 4. Modules Identified for Testing

Based on application workflow, the following modules are identified:

### 4.1 Login Module

Features:

- User authentication using username and password
- Error message validation for invalid credentials
- Password field masking
- Session creation after successful login
- Logout functionality

Key Risks:

- Unauthorized access
- Weak validation handling
- Session mismanagement

---

### 4.2 Dashboard Module

Features:

- Display quick access panels
- Display system notifications
- Display employee-related widgets

Key Risks:

- Incorrect dashboard rendering
- Broken navigation links

---

### 4.3 PIM (Personal Information Management)

Features:

- Add new employee
- Edit employee details
- Delete employee records
- Upload employee photo

Key Risks:

- Duplicate employee records
- Data validation failures
- Mandatory field handling issues

---

### 4.4 Leave Module

Features:

- Apply leave
- View leave balance
- Approve or reject leave requests
- Leave history tracking

Key Risks:

- Incorrect leave calculations
- Invalid leave approval flow

---

### 4.5 Admin Module

Features:

- User role management
- User account creation
- Permission assignment

Key Risks:

- Role misconfiguration
- Unauthorized privilege escalation

---

## 5. Functional Requirements Identified

FR-01: System should allow login using valid credentials.

FR-02: System should display error message for invalid credentials.

FR-03: System should allow admin to add employee details.

FR-04: System should allow employee leave request submission.

FR-05: System should allow admin to approve or reject leave.

FR-06: System should allow admin to assign user roles.

FR-07: System should allow logout successfully.

---

## 6. Non-Functional Requirements Identified

NFR-01: System response time should be less than 3 seconds.

NFR-02: System should support latest Chrome browser.

NFR-03: System should maintain session security.

NFR-04: System should prevent unauthorized access.

---

## 7. Assumptions

- Valid test credentials are available.
- Application server is accessible.
- Database operations are functional.

---

## 8. Dependencies

- Stable internet connection
- Test user accounts
- Application availability

---

## 9. Risks Identified

- Session timeout handling failure
- Data validation failures
- Role-based access issues
- UI rendering inconsistencies

---

## 10. Test Focus Areas

Based on requirement analysis, the following areas require priority testing:

- Login validation
- Role-based access control
- Employee data entry validation
- Leave workflow validation
- Logout session validation
