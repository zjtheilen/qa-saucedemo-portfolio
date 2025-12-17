Status: Open
Reported by: Zachary Theilen
Date: 2025-12-17

Title:
Unclear error message when locked out user tries to login

Description:
• When locked-out user tries to login, the application displays a vague/unprofessional error message. 

Environment:
• Browser: Chrome
• Saucedemo web app

Preconditions:
• User is on the login page

Steps to Reproduce:
1. Enter "locked_out_user" for username
2. Enter valid password for password
3. Click login

Expected Result:
• Error messages should be clear, professional, and consistent (e.g., "This user has been locked out.")

Actual Result:
• Messages read "Epic sadface: Sorry, this user has been locked out."

Severity:
• Minor

Priority:
• Medium
