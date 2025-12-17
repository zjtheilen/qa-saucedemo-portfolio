Status: Open
Reported by: Zachary Theilen
Date: 2025-12-17

Title:
Add to cart button does not reset on Reset App State

Description:
• When the user adds an item to the cart and then resets the app state, the cart is emptied, but the add to cart button is not changed from Remove to Add to cart. This goes away after the user clicks the Remove button (functionally all this does is reset to default state), navigates away from the page and back, or refreshes their browser.

Environment:
• Browser

Preconditions:
• User is on Products page with sidebar expanded

Steps to Reproduce:
1. Add item(s) to the card
2. Click Reset App State in the sidebar

Expected Result:
• Cart should empty and Remove buttons on items should revert to Add to card

Actual Result:
• Remove buttons do not revert unless user navigates away, refreshes the page, or clicks (and reverts) the button(s)

Severity:
• Minor

Priority:
• Low
