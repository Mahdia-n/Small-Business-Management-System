Small Sales and Order Management System
Your project will be a small e-commerce website where customers can browse products, create an account, add items to a shopping cart, and complete a purchase. You will build it in stages, starting with customer management and user registration.
For the first version, the website will have two main parts:
Customer-facing website: A landing page with a “Purchase Now” button, product browsing, sign-up, login, and checkout.
Customer management backend: A database and backend code to register customers, authenticate them, and store their information securely.
Later, you can add inventory management, order tracking, payment integration, and an admin dashboard.

Website initial pages to develop in the first stage:
Page 1 — Home (index.php)
Business name and logo
Navigation menu
Welcome section
“Purchase Now” button
Featured products
Footer with contact information
Page 2 — Product Catalog (products.php)
Display available products
Show product names, prices, and images
Add to Cart button
View Cart button
Page 3 — Customer Registration (register.php)
Full name
Email address
Password and confirm password
Form validation
Link to existing customer login
Page 4 — Shopping Cart (cart.php)
Selected items
Quantity controls
Remove item option
Subtotal and total
Proceed to Checkout button

Things to Do:
Design the customer registration form.
Collect the customer's name, email, and password.
Validate required fields and email format.
Check that the email is not already registered.
Hash passwords using PHP's password_hash().
Save customer records to MySQL using prepared statements.
Create the login and logout functionality.
Use PHP sessions to keep customers logged in.
Test registration, login, invalid credentials, and duplicate emails.




