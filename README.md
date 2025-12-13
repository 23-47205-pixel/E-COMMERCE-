 Project Overview
 
This is a fully functional, Amazon-inspired e-commerce website built with HTML, CSS, and JavaScript. The website features a modern, responsive design with a complete shopping experience including product browsing, cart management, wishlists, order tracking, and user authentication.

 Key Features
 Core Shopping Features
Product Catalog: 80+ products across 8 categories (Electronics, Fashion, Home & Kitchen, Books, Sports, Games, Baby, Automotive)

Category Browsing: Visually appealing category cards with gradient backgrounds

Search Functionality: Category-based search with dropdown

Product Filtering: Sort by price, rating, and newest arrivals

Today's Deals: Special offers and discounts section

 Shopping Experience
Shopping Cart: Add/remove items, quantity adjustment

Wishlist: Save favorite products for later

Order Management: View order history and track shipments

Order Details: Complete order information with status timeline

Checkout Process: Secure checkout with order confirmation

 UI/UX Features
Dark Mode: Toggle between light and dark themes

Responsive Design: Fully responsive across all devices

Interactive Carousel: Auto-rotating hero section

Toast Notifications: Real-time feedback for user actions

Modal Windows: Login, registration, and checkout forms

Smooth Animations: Hover effects and page transitions

User Features
User Authentication: Login and registration system

Profile Management: Save shipping information

Order History: Track all past purchases

Local Storage: Persist cart, wishlist, and preferences

 Project Structure
text
ecommerce-website/
├── index.html              # Main HTML file
├── README.md               # This documentation file
└── image/                  # Product images directory
    ├── wireless with noise.jpg
    ├── dual smarthphones.jpg
    ├── laptop.jpg
    ├── smart watch.jpg
    ├── professional.jpg
    └── ... (80+ product images)
 Quick Start
Download the project files

Open index.html in any modern web browser

No server required - runs completely client-side

 Technologies Used
HTML5: Semantic markup and structure

CSS3: Custom properties, Flexbox, Grid, animations

JavaScript (ES6+): Full interactivity and state management

Font Awesome: Icons for UI elements

Google Fonts: Inter font for typography

Local Storage: Client-side data persistence

 Responsive Design
The website is fully responsive and optimized for:

Desktop (1200px+)

Tablet (768px - 1199px)

Mobile (480px - 767px)

Small Mobile (< 480px)

 Demo Credentials
For testing purposes:

Email: Any valid email format

Password: Any password (demo validation only)

Test Order: Complete checkout to see order tracking

 How to Use
1. Browsing Products
Click on category cards to view products

Use filters to sort products

Search using the search bar

2. Shopping Cart
Click "Add to Cart" on any product

View cart by clicking the cart icon

Adjust quantities or remove items

3. Wishlist
Click heart icon on products

Access wishlist from header

Move items to cart directly

4. Checkout
Add items to cart

Click "Proceed to Checkout"

Fill in shipping information

Place order and receive confirmation

5. Order Tracking
View order history from user menu

Click on any order for detailed view

Track status with timeline visualization

 Data Persistence
The website uses localStorage to persist:

Shopping cart items

Wishlist products

User orders

Dark mode preference

User login state (demo)

 Customization
Changing Colors
Edit CSS custom properties in the :root selector:

css
:root {
    --amazon-dark: #232F3E;
    --amazon-orange: #FF9900;
    --amazon-blue: #146EB4;
    /* Add your own colors */
}
Adding Products
Modify the products array in the JavaScript section:

javascript
{
    id: 81,
    name: "New Product Name",
    price: 99.99,
    image: "image/product.jpg",
    rating: 4.5,
    reviews: 100,
    category: "electronics",
    tags: ["electronics", "new"],
    isDeal: false
}
Adding Categories
Update the categories object:

javascript
'new-category': {
    name: 'New Category',
    description: 'Category description',
    icon: 'fa-icon-name'
}
 Security Note
This is a demo project for educational purposes only

No real payments are processed

User authentication is simulated

Data is stored locally in browser only

Do not use real personal information

📄 License
This project is created for educational purposes and is inspired by Amazon's design. All product images and descriptions are for demonstration only.

 Contributing
Feel free to fork this project and customize it for your needs. Suggestions and improvements are welcome!

 Support
For questions or issues:

Check the browser console for errors

Ensure all image paths are correct

Clear browser cache if experiencing issues

Use a modern browser (Chrome, Firefox, Edge, Safari)

Enjoy shopping on your Amazon-style e-commerce website! 
