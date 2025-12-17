Status: Open
Reported by: Zachary Theilen
Date: 2025-12-17

Title:
Add to Cart button does not reset after app state reset

Description:
• When the user adds an item to the cart and then uses the "Reset App State" option, the cart is emptied, but the add to cart buttons are not changed from "Remove" to "Add to cart." This issue resolves only if the user clicks the "Remove" button, refreshes the page, or navigates away and back.

Environment:
• Browser

Preconditions:
• User is on Products page with sidebar expanded

Steps to Reproduce:
1. Add one or more item to the card
2. Click "Reset App State" in the sidebar

Expected Result:
• Cart should empty
• All "Remove" buttons should revert to "Add to Cart"

Actual Result:
• Cart empties, but "Remove" buttons remain until the user refreshes, navigates away, or manually clicks the buttons

Severity:
• Minor

Priority:
• Low
