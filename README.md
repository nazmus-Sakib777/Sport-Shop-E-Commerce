SAS Sports Corner Website

Overview

SAS Sports Corner is an e-commerce website for sports equipment, featuring user registration, login, shopping cart, checkout, product categories, and an admin dashboard. Built with HTML, CSS (Tailwind CSS), and JavaScript.

Features



User Authentication: Register and login functionality.

Shopping Cart: Add, view, and remove items.

Checkout: Simulated checkout process.

Product Categories: Browse sports gear by category (Football, Basketball, Tennis, Cricket).

Admin Dashboard: Manage products and view orders (accessible with admin credentials).

Responsive Design: Mobile-friendly layout using Tailwind CSS.



Setup Instructions



Clone or Download: Copy the project files to your local machine.

Serve Locally:

Use a local server (e.g., VS Code Live Server extension, or python -m http.server).

Open index.html in a browser via the server (file:// protocol may cause image/loading issues).





Dependencies:

No external installations required; Tailwind CSS is included via CDN.

Ensure internet access for loading Tailwind CSS and placeholder images.





Admin Access:

Temporary admin user: Email: admin@sassports.com, Password: admin123.

Admin dashboard is accessible via the "Admin" link after login.







Project Structure



index.html: Homepage with categories and featured products.

login.html: User login page.

register.html: User registration page.

cart.html: Shopping cart page.

checkout.html: Checkout page.

category.html: Product category page.

admin.html: Admin dashboard.

styles.css: Custom CSS (if needed, currently minimal due to Tailwind).



Troubleshooting



Images Not Loading:

Ensure you're using a local server (not file:// protocol).

Check internet connectivity for placeholder images (via.placeholder.com).

Verify image paths in HTML.





Cart Not Updating:

Clear browser localStorage (localStorage.clear() in browser console).

Ensure JavaScript is enabled.





Admin Login Fails:

Use the provided admin credentials.

Check console for errors (F12 > Console).







Notes



Images are placeholders from via.placeholder.com and Unsplash for demo purposes.

Admin dashboard and checkout are simulated; no backend is included.

For production, integrate a backend (e.g., Node.js, PHP) for user data and payments.



Contact

For issues or enhancements, reach out to the developer or open an issue in the repository (if hosted).

