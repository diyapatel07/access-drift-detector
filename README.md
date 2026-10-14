# 🔐 Access Drift Detector

### 📊 Overview

This project aims to **detect access drift** by identifying permissions assigned to employees beyond their standard role permissions. It uses a Role-Based Access Control (RBAC) approach to flag unexpected permissions and generate an access review report.

---

### 🎯 Objectives

- Identify permissions that fall outside an employee's standard role.
- Compare assigned permissions with expected role permissions.
- Generate a report of permissions requiring review.
- Support IAM access auditing through a simple Python-based prototype.

---

### ⚙️ Tools & Technologies

- **Language:** Python
- **Libraries:** pandas
- **Environment:** Jupyter Notebook
- **Concepts:** Identity and Access Management (IAM), Role-Based Access Control (RBAC)

---

### 🧩 Project Workflow

1. **Employee and Role Data**
   - Created fictional employee records and standard role permissions.
   - Defined the permissions assigned to each employee.

2. **Access Drift Detection**
   - Compared assigned permissions against standard role permissions.
   - Flagged permissions that fall outside the expected role.

3. **Access Review Report**
   - Organized flagged permissions into a structured report.
   - Included employee details, flagged permissions, and review status.

4. **Report Export**
   - Exported the access review report for further inspection.

---

### 📋 Expected Output

- A list of permissions that require review.
- Employee-wise details of flagged permissions.
- A report that can be exported for access auditing.

---

#
