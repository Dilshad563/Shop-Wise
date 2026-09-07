ShopWise - E-Commerce Store
Welcome to ShopWise, a lightweight, responsive e-commerce web application built entirely with HTML5 and CSS3. This project features a clean user interface to showcase and sell products online across multiple customized layouts.

🛠️ Tech Stack
Structure: HTML5

Styling: CSS3

📁 File Structure
The project relies on a central HTML file powered by modular CSS stylesheets to handle different sections and layout designs:

Plaintext
├── shopwise.html   # Main HTML page containing the store layout and structure
├── shopwise1.css   # Global styles, typography, color palette, and reset rules
├── shopwise2.css   # Header, navigation bar, and main banner styling
├── shopwise3.css   # Product grid, product cards, and hover effects
└── shopwise4.css   # Footer, shopping cart UI, and responsive media queries
Key Features
Responsive Layout: Optimized for desktop, tablet, and mobile viewing.

Product Showcase: Clean grid design to display featured items with pricing and action buttons.

Modular CSS Architecture: Styles are divided across four dedicated CSS files for easier maintenance and debugging.

Zero Dependencies: Pure HTML/CSS without external Javascript libraries or heavy frameworks.

🚀 How to Run the Project
Clone or Download the Repository:

Bash
git clone https://github.com/your-username/shopwise.git
Ensure File Paths Are Correct:
Make sure shopwise.html and all four CSS files (shopwise1.css, shopwise2.css, shopwise3.css, shopwise4.css) are located in the same directory folder.

Link CSS Files in HTML:
Verify that the <head> tag of your shopwise.html links all four stylesheets in order:

HTML
<link rel="stylesheet" href="shopwise1.css">
<link rel="stylesheet" href="shopwise2.css">
<link rel="stylesheet" href="shopwise3.css">
<link rel="stylesheet" href="shopwise4.css">
Launch the Store:
Double-click shopwise.html or open it directly inside any web browser (Chrome, Firefox, Edge, Safari).

📌 Future Roadmap
Add JavaScript functionality for an interactive shopping cart.

Implement a checkout form and checkout validation.

Add individual product detail pages.
