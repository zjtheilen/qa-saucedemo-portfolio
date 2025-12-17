# Cart Test Cases - SauceDemo

## TC-CART-001: Add single item to cart
**Description:** Verify that a user can add a single item to the cart from the Products page  
**Preconditions:** User is logged in and on the Products page  
**Steps:**
1. Click "Add to cart" on a product
2. Verify cart icon updates with item count
**Expected Result:** Cart icon shows 1 item, button changes to "Remove"  
**Actual Result:**  
**Severity:** Minor  
**Priority:** Medium  
**Related Bug:** N/A

---

## TC-CART-002: Remove item from cart
**Description:** Verify that removing an item from the cart updates the cart correctly  
**Preconditions:** User has at least one item in the cart  
**Steps:**
1. Click "Remove" on a product in the Products page
2. Verify cart icon updates
**Expected Result:** Cart icon decrements correctly, button changes back to "Add to cart"  
**Actual Result:**  
**Severity:** Minor  
**Priority:** Medium  
**Related Bug:** N/A

---

## TC-CART-003: Add multiple items to cart
**Description:** Verify that multiple items can be added to the cart and cart count updates correctly  
**Preconditions:** User is logged in and on the Products page  
**Steps:**
1. Click "Add to cart" on multiple products
2. Verify cart icon updates with total item count
**Expected Result:** Cart icon reflects the correct total, buttons change to "Remove"  
**Actual Result:**  
**Severity:** Minor  
**Priority:** Medium  
**Related Bug:** N/A

---

## TC-CART-004: Add to cart button does not reset after resetting app state
**Description:** Verify that the add-to-cart button resets when the app state is reset  
**Preconditions:** User is logged in and has added at least one item to the cart  
**Steps:**
1. Add item(s) to the cart
2. Click "Reset App State" in the sidebar
**Expected Result:** Cart should empty, and all "Remove" buttons should revert to "Add to cart"  
**Actual Result:** Remove buttons do not revert unless user navigates away, refreshes, or manually clicks Remove  
**Severity:** Minor  
**Priority:** Low  
**Related Bug:** [BUG-002: Add to cart button does not reset](../bugs/BUG-002-cart-button-reset.md)

---

## TC-CART-005: Cart persists across navigation
**Description:** Verify that cart contents persist when navigating between pages  
**Preconditions:** User has added items to the cart  
**Steps:**
1. Navigate to another page (e.g., About or Inventory)
2. Return to Products page
**Expected Result:** Items remain in the cart, cart count reflects current items  
**Actual Result:**  
**Severity:** Minor  
**Priority:** Medium  
**Related Bug:** N/A

---

## TC-CART-006: Cart quantity cannot be adjusted
**Description:** Users cannot modify the quantity of items in the cart; they must repeatedly click “Add to cart” to increase quantity, which is inefficient. 
**Preconditions:** User is logged in, has added at least one item to the cart, and navigated to the cart page
**Steps:**
1. Try to select number in "QTY" column
**Expected Result:** User should be able to enter a quantity in the field  
**Actual Result:** Field is not selectable or editable  
**Severity:** Medium  
**Priority:** Medium
  <!-- TODO: change to correct bug report -->
**Related Bug:** [BUG-005: Cart quantity can't be changed](../bugs/BUG-005-cart-quantity-bug.md)