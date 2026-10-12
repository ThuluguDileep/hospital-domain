SSKATT Multi-Hospital Workforce Demo

HOW TO RUN
1. Extract the ZIP file.
2. Open index.html in Chrome, Edge, or Firefox. Internet is needed for Bootstrap CDN styling/icons.
3. Choose a hospital and role, then use a demo login below.

DEMO LOGINS
CityCare Hospital
  Admin: cityadmin / city123
  Employee: nurse01 / nurse123
  Additional seeded employees: rahul02 / rahul123, meera03 / meera123

Green Valley Hospital
  Admin: greenadmin / green123
  Employee: staff01 / staff123
  Additional seeded employee: sana02 / sana123

FEATURES
- Separate hospital workspaces and hospital-specific admin accounts
- Separate employee login and employee-specific screens
- Employee directory (admin)
- Clock-in / clock-out and attendance history
- Shift assignment and prepared email notification (opens email app; no automatic sending)
- Leave requests and admin approval/rejection
- Monthly salary-slip generation and print/save as PDF
- Password visibility eye button on login screen\n- Employee forgot-password form that verifies demo username + registered email (no real reset email is sent)\n- Browser localStorage persistence

IMPORTANT PROTOTYPE LIMITATIONS
This is a frontend-only demonstration. Credentials are demo-only and not secure. Browser localStorage is not a shared database, so data is limited to the browser/device and can be edited by the user. No email is automatically sent. Salary slips are illustrative and not official payroll documents. Before real hospital deployment, use a secure backend, database, password hashing, role-based authorization, audit logs, backups, HTTPS, email provider integration, and reviewed payroll rules.
