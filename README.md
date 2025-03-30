![image](https://github.com/user-attachments/assets/45550b4d-ee3d-4b2b-b977-af25119aa2a5)


![image](https://github.com/user-attachments/assets/00e69609-9129-48de-b3a9-0076913ef61b)

📌 Project Overview
The Clothing Store is a web-based application designed to provide users with a smooth and interactive online shopping experience for clothes. The project includes functionalities such as product display, filtering, adding items to a cart, and managing orders using LocalStorage. The application fetches data dynamically from a DummyJSON API.

🌐 Live Demo
📂 GitHub Repository
💡 Features
Product Display (Clothing items like Shirts, Pants, Accessories, etc.)

Product Filtering (by Category, Price, Gender, etc.)

Product Detail View

Shopping Cart with Add/Remove functionalities

LocalStorage Integration for session persistence

Responsive Design for Mobile, Tablet, and Desktop

🖥️ Technology Stack
Frontend
HTML: Structuring of web pages.

CSS (Tailwind CSS): Styling, layout, and responsiveness.

JavaScript (Vanilla JS): Interactive UI, dynamic rendering, event handling.

Backend (API)
DummyJSON API: Dynamic fetching of clothing items.

Storage & State Management
LocalStorage: Maintaining cart state across sessions.

Additional Tools
Tailwind CSS: For responsive and efficient styling.

Font Awesome: Icons for cart, filter, etc.

🚀 Installation & Setup
Prerequisites
A modern web browser (Chrome, Firefox, Edge, etc.)

A code editor (VS Code, Sublime Text, etc.)

A local server (optional, for better performance – e.g., Live Server extension in VS Code)

Clone the Repository
bash
Copy
Edit
git clone https://github.com/Hitman-coder/Clothing-Store.git
Open the Project
bash
Copy
Edit
cd Clothing-Store
Run Locally
Open index.html in your browser.

Alternatively, use a local server like VS Code Live Server for better performance.

📂 Project Structure

/project-folder  
│── index.html              # Home page displaying all products  
│── style.css               # Styling and responsiveness  
│── menscollection.html     # Men's Product Collection  
│── womenscollection.html   # Women's Product Collection  
│── kidscollection.html     # Kids' Product Collection  
│── cart.html               # Shopping cart page  
│── README.md               # Project documentation  




javascript
Copy
Edit
fetch('https://dummyjson.com/products/category/clothing')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error('Error fetching data:', error));
🛒 Functionality
Product Listing
Displays various clothing items fetched from the API.

Pagination or Load More option for browsing large inventories.

Product Filtering
Categories: Men, Women, Accessories, etc.

Price Range: Filter based on price range or popularity.

Product Details View
Displays detailed information when a product is clicked.

Includes images, descriptions, price, ratings, etc.

Shopping Cart
Allows adding, removing, and viewing items.

Persisted using LocalStorage for maintaining state across page reloads.

Search and Filter
Search bar to find items by name.

Category-based filtering for a better user experience.

Responsive Design
Built using Tailwind CSS to ensure responsiveness across devices.

🧩 Testing
Functional Testing
Feature	Expected Outcome	Status
Product Fetching	Displays products from API	✅
View Details	Redirects to product details page	✅
Add to Cart	Adds items to cart & updates LocalStorage	✅
Remove from Cart	Successfully removes items from cart	✅
Cart Display	Shows selected products & total price	✅
Clear Cart	Removes all items from cart	✅
UI/UX Testing
Test Case	Expected Outcome	Status
Responsive Design	Proper rendering on all devices	✅
Navigation Behavior	Smooth scrolling and transitions	✅
Font & Color Consistency	Uniform style across pages	✅
📌 Challenges and Solutions
API Fetching Issues
Challenge: Handling API errors.

Solution: Implemented error handling using .catch(error => console.error(error)).

Responsiveness
Challenge: Making layout adaptable across various devices.

Solution: Utilized Tailwind CSS with responsive utility classes.

State Management
Challenge: Persisting cart data after refreshing.

Solution: Used LocalStorage to retain cart state.

🚀 Future Improvements
Implement user authentication and profiles.

Add sorting features (e.g., price low to high, popular items).

Integrate a real backend with a database.

Implement a payment gateway for order completion.

📞 Contact
If you have any questions or feedback, feel free to reach out!
GitHub: Hitman-coder
Email: aborse2003@gmail.com
