# Shopify-App-Assignment-
Hosted Website Link :- https://majestic-biscotti-35b91c.netlify.app/

Overview :-
Choco Cube is an e-commerce Shopify store that offers a feature allowing customers to create custom packs of chocolates. 
This feature enables customers to select a combination of chocolates for their custom pack, with a total limit of 8 items.
The price is calculated automatically based on the selected products and their respective quantities.

Table of Contents :-
Key Features
Project Structure
Functions
Usage
Responsive Design
Demo
Tools and Technologies
License

Key Features :-
Customers can build a custom pack of chocolates by selecting different chocolates from the product list.
The total number of items in the custom pack is limited to 8.
The total price of the custom pack is calculated automatically based on the selected items and their respective quantities.
An intuitive and responsive user interface ensures a seamless shopping experience.
Notifications are provided for adding and removing products from the cart.

Project Structure :-
The project consists of the following key files:
index.html: The HTML file containing the structure of the web page, including product listings, cart, and notifications.
styles.css: The CSS file that defines the styles for the web page, including layout, colors, and responsiveness.
script.js: The JavaScript file that contains the logic for adding, removing, and updating cart items, as well as handling user interactions.

Functions :-
JavaScript Functions :-
changeQuantity(id, action): This function allows users to increase or decrease the quantity of a product in the cart when the plus (+) or minus (-) buttons are clicked.

addToCart(id): This function adds a selected product to the cart, ensuring that the total number of items in the cart does not exceed 8.

updateCartSize(): This function updates the cart icon with the total quantity of items in the cart.

checkCart(currentProductQuantity): This function checks if adding a product to the cart would exceed the maximum limit of 8 items.

showCart(): This function displays the cart modal with a list of selected products, quantities, and total price.

closeCart(): This function closes the cart modal when the close button or overlay is clicked.

removeFromCart(id, productContainer): This function removes a product from the cart and updates the total price accordingly.

notification(msg): This function displays notifications for adding or removing products from the cart.

Event listeners are used to handle user interactions, such as clicking buttons and navigating the website.

Usage :-
Customers can visit the Choco Cube website and browse the list of available chocolates.

To add a product to the cart, they can click the "Add to Cart" button for the desired product. They can also change the quantity using the plus (+) and minus (-) buttons.

The cart icon in the navigation bar shows the total number of items in the cart.

Customers can click the cart icon to view the contents of the cart, which includes product names, quantities, and prices.

The total price of the cart is displayed, and customers can remove items if needed.

Responsive Design :-
The website is designed to be responsive, adapting to different screen sizes and devices.

Media queries in the CSS (@media) are used to adjust the layout and styling for smaller screens, ensuring a consistent user experience.

Demo
You can access a live demo of the Choco Cube website to see the custom chocolate pack feature in action.

Choco Cube Hosted Website Link :- https://majestic-biscotti-35b91c.netlify.app/


Tools and Technologies :-
HTML, CSS, JavaScript
Shopify platform (for e-commerce functionality)
Font Awesome (for icons)
Google Fonts (for typography)

License :-
This project is licensed under the MIT License.

Screenshots :- 

![Screenshot (3526)](https://github.com/ABHINEET4/Shopify-App-Assignment-/assets/108821830/cb7d4eef-6401-4dcc-b48c-a08da83289fa)



![Screenshot (3527)](https://github.com/ABHINEET4/Shopify-App-Assignment-/assets/108821830/fc38b862-f69f-431d-8ea2-f48bdd86261f)



