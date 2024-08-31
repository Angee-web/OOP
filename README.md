
This project is an example of object-oriented programming (OOP) in JavaScript. It demonstrates how to manage a shopping cart using JavaScript classes. The main goal is to show how to create products, add them to a cart, calculate the total price, and remove items from the cart.

The application has three main classes:
Product: Represents an item you can buy.
ShoppingCartItem: Represents an item in the shopping cart, including its quantity.
ShoppingCart: Manages a collection of ShoppingCartItem instances, allowing you to add, remove, and display items, as well as calculate the total price of the cart.

How It Works:
Create Products: Define products with an ID, name, and price.
Create a Shopping Cart: Initialize a shopping cart that will hold the items.
Add Items: Add products to the cart with a specified quantity.
Display Items: Show the items in the cart along with their quantities and total prices.
Remove Items: Remove items from the cart by their product ID.
Calculate Total: Get the total price of all items in the cart.

Classes and Methods
Product Class:
constructor(id, name, price): Creates a product with a unique ID, name, and price.
ShoppingCartItem Class:
constructor(product, quantity): Creates a cart item with a product and quantity.
getTotalPrice(): Returns the total price of the cart item.
ShoppingCart Class:
constructor(): Initializes an empty cart.
addItem(product, quantity): Adds a product to the cart with a specified quantity.
removeItem(productId): Removes a product from the cart by its ID.
getTotal(): Returns the total price of all items in the cart.
displayItems(): Displays all items in the cart with their details.
