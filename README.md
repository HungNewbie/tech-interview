# Setup instruction:
## All you need to do is push the project on GitHub, setup a GitHub page and now the webpage can be run normally. Can also be run locally using live server plugin

# Discussion of technologies used:
## Normal HTML, CSS and Vanilla Javascript. A json file is for stored hard-coded array of objects as products.

# Requirement:
## Have a pre-populated (hard coded) array of objects as products: Inside products.json
## Your product display should have (not limited to) product image, product name, product price: By using .innerHTML from cart.js 
## All products should be displayed when the page loads: By using .innerHTML from products.js
[All products:](./images/Screenshot2.jpg)
## Using an ‘add to cart’ button, the user should be able to add the products to a shopping cart list: the page display the number of item added by the user on the top right of the screen. When click on the word "Total item in cart:", the shopping cart page appear. Refer to function handlePageView() in script.js
## The shopping cart lists all products and displays a the total price: Refer to cart.js, fucntion displayCartItems() and localStorage
[All products in cart:](./images/Screenshot1.jpg)
## The user should also be able to delete the products from the cart, thus modifying the total price of the cart: Click on the Remove button will delele the item from the list and the price will be updated too. using localStorage and function: loadCartListeners, handleDelete and handleChange from cart.js
## The user should be able to enter a quantity for each product: doable, work as a form, min number of item in cart is 1 and maximum is 100. Everytime a number is entered on the form, the price also update as well.