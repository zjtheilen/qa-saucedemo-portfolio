Status: Open
Reported by: Zachary Theilen
Date: 2025-12-17

Title:
Login error message is unclear and unprofessional for invalid credential scenarios

Description:
• When user enters invlaid credentials on login, the application displays a vague/unprofessional error message. This message does not cleary indicate whether username/password/both are incorrect, and uses informal language that might confuse or frustrate users.

Environment:
• Browser

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
• Low

Priority:
• Medium