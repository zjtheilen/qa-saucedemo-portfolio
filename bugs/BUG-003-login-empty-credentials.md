Status: Open
Reported by: Zachary Theilen
Date: 2024-12-17

Title:
Unclear error message when username or password is empty

Description:
When the user attempts to log in with either the username or password field empty, the application shows "Epic sadface: Username is required" or "Epic sadface: Password is required." The messages are unprofessional and inconsistent with UI standards.

Environment:
• Browser: Chrome
• Saucedemo web app

Preconditions:
• User is on the login page

Steps to Reproduce:
1. Leave username empty and enter any password, click login
2. Observe the error message
3. Leave password empty and enter any username, click login
4. Observe the error message

Expected Result:
• Error messages should be clear, professional, and consistent (e.g., "Please enter your username" / "Please enter your password")

Actual Result:
• Messages read "Epic sadface: Username is required" and "Epic sadface: Password is required"

Severity:
• Minor

Priority:
• Low
