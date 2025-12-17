Status: Open
Reported by: Zachary Theilen
Date: 2025-12-17

Title:
Unclear error message when user is locked out

Description:
• When locked-out user tries to login, the application displays a vague/unprofessional error message. 

Environment:
• Browser: Chrome
• Saucedemo web app

Preconditions:
• User is on login page


Steps to Reproduce:
1. Navigate to SauceDemo login page
2. Enter an invlaid username and valid password
2. Click Login button

Expected Result:
• Error message should:
    • Clearly identify which credential is invalid
    • Use neutral, professional language
    • Provide actionable guidance to user

Actual Result:
• Error message displays:
    "Epic sadface: Username and password do not match any user in this service"

Additional Scenarios:
• Valid username + invalid password
• Invalid username + invalid password

Severity:
• Minor

Priority:
• Medium