# 🔐 Optimizing User, Group, and Role Management with Access Control and Workflows  
**Category:** ServiceNow System Administrator  

## 📌 Overview
This project demonstrates how efficient user, group, and role management—combined with well-structured workflows—can significantly improve accountability and task visibility in a small project management environment.

By leveraging **ServiceNow**, the solution introduces proper access controls, role-driven authorizations, and streamlined workflows to ensure tasks are assigned, tracked, and completed responsibly throughout the project lifecycle.

---

## 🧩 Problem Statement
A small project team consists of:
- **Project Manager** — *Alice*
- **Team Member** — *Bob*

The current system suffers from:
- Lack of role clarity
- Poor access control
- Zero automated workflows
- Confusion in task assignments and status tracking

This leads to:
- Accountability issues
- Overlapping responsibilities
- Delays in project execution

---

## 🎯 Objectives
The goals of this project are to:
✅ Define clear user roles and access privileges  
✅ Improve visibility of task progress  
✅ Automate the task assignment workflow  
✅ Enhance accountability through structured approvals  
✅ Reduce redundancy and confusion  

---

## 🏗️ Proposed Solution
To mitigate these challenges, the following ServiceNow features are implemented:

### 👥 User, Group & Role Management
- Users are assigned to security groups
- Roles determine access and permissions
- Segregation of duties ensures responsibility

### 🔑 Access Control Rules (ACLs)
- Control read/write/delete privileges
- Improve data integrity
- Protect sensitive task information

### 🔄 Workflow Automation
- Task creation triggers workflow
- Approvals handled by Project Manager
- Real-time progress tracking

---

## 🔒 Role Definitions
| User  | Role | Permissions |
|-------|------|-------------|
| Alice | Project Manager | Approve tasks, assign tasks, view all statuses |
| Bob   | Team Member | Update assigned tasks, view only their tasks |

---

## 🚀 Technologies & Skills Used
- **ServiceNow** platform administration
- **TensorFlow** (optional ML insights such as priority prediction)
- **Oracle DB** for database storage and user record persistence

---

## 📁 Project Structure
