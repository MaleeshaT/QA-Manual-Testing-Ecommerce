🐛 BUG-001

Title: Checkout form accepts invalid email format
Module: Checkout
Environment: Chrome v120, Windows 11
Build Version: v1.0
Severity: High
Priority: High
Status: Open

Steps to Reproduce:

Add product to cart

Proceed to checkout

Enter email as testemail

Fill other mandatory fields

Click Submit

Expected Result:

System should display validation error for invalid email format.

Actual Result:

Order is placed successfully without email validation.

Impact:

Invalid customer data stored in database.

🐛 BUG-002

Title: Cart total does not update when quantity is modified
Module: Cart
Severity: Critical
Priority: High
Status: Open

Steps to Reproduce:

Add product priced $100 to cart

Change quantity from 1 to 2

Expected Result:

Total should update to $200.

Actual Result:

Total remains $100.

Impact:

Incorrect billing amount displayed to user.

🐛 BUG-003

Title: Password field accepts less than 8 characters
Module: Registration
Severity: Medium
Priority: Medium
Status: Open

Expected Result:

System should enforce minimum 8-character password rule.

Actual Result:

User can register with 5-character password.
