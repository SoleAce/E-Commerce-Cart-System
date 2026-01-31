E-Commerce Cart System (Web Storage & Cookies Project)
This project is a simple web-based e-commerce cart system that demonstrates how to use localStorage, sessionStorage, browser caching, and cookies to manage shopping cart data, user preferences, and session-related information.

The application focuses on client-side storage techniques and how they improve user experience by persisting data across page reloads and browser sessions.

📌 Features
Product catalog with items, prices, and Add-to-Cart buttons
Shopping cart display with selected items and quantities
Persistent cart storage using localStorage
Font preference stored for the session using sessionStorage
User name and small preferences stored in cookies
Cached static assets (CSS, images) for improved performance
Clear cart and reset preferences functionality
Dynamic total price calculation
Personalized greeting for returning users

🧰 Technologies Used
HTML5, CSS3, JavaScript (Vanilla JS)
Browser Web Storage APIs
localStorage
sessionStorage
Cookies

📂 Project Structure
project-folder/
│
├── index.html
├── style.css
├── script.js
└── assets/
    └── images/


How the Application Works
1. Product Catalog
Displays a list of products with:
Name
Price
Add-to-Cart button

2. Shopping Cart (localStorage)
When an item is added:
Cart data is saved in localStorage
On page load:
App checks localStorage
Displays saved cart items if available
Cart updates automatically when items are added or removed

3. Font Preference (sessionStorage)
User selects a font from a dropdown menu
Selected font is saved in sessionStorage
Preference lasts only during the current browser session

4. Browser Caching
Static assets (CSS and images) are cached by the browser
Improves page load speed on subsequent visits
A message informs users when cached resources are being used

5. Cookies (User Info & Preferences)
Username stored in a cookie
User greeted on page load:
Example: Welcome back, Alex!
Optional small preferences (currency, shipping method, etc.) stored in cookies

6. Clear & Reset
"Clear Cart" button:
Removes cart data from localStorage
Reset preferences:
Deletes cookies
Clears stored preferences

8. Total Price Calculation
Total price updates dynamically
Automatically recalculated when cart changes
🚀 How to Run the Project
Download or clone the repository
Open index.html in any modern web browser
Start adding items to the cart
No server or installation is required.

✅ Learning Outcomes
By completing this project, you will learn:
How to use localStorage for persistent data
How to use sessionStorage for session-based preferences
How cookies store small user data
How caching improves performance
How to build a simple cart system with JavaScript
📸 Example User Flow
User opens site
Enters name → saved in cookie
Selects preferred font → saved in sessionStorage

Adds products → saved in localStorage
Refreshes page → cart and greeting remain
📝 Future Improvements (Optional)
Quantity increment/decrement buttons
Product filtering and search
Login form with validation
Better UI styling

IndexedDB for larger datasets

📄 License
This project is for educational purposes only.
