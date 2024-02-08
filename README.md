# EcommerceProject
Django for Ecommerce Website

Introduction:
This Django-based E-Commerce project provides a scalable and customizable platform for online businesses. It includes essential features such as product management, user authentication, cart functionality,payment gateway using khalti and order processing.

Table of Contents

    Introduction
    Getting Started
        Prerequisites
        Installation
    Usage:
        Signup
        Login
        Admin Add Product
        View All Products
        Search Products
        Search Products by Category
        Add to Cart
        List Cart
        Remove Item from Cart
        Add Address
        Cart Checkout
    Contribution

Key Features:
User Authentication and Authorization:
Secure user registration and login.
User roles and permissions (admin, customer).

Product Management:
Add, edit, and delete products.
Categorize products for easy navigation.
Product search and filtering options.

Shopping Cart:
Add/remove items to/from the cart.
Update quantity and view the total price.
Persistent shopping cart for logged-in users.

Checkout Process:
Secure and user-friendly checkout.
Payment gateway(Khalti).
Order summary and confirmation.

Order Management:
Order history and tracking for users.
Admin order management interface.

Getting Started:
Prerequisites:
installed your machine:
Python,Django,Database System(MySQL, SQLite)

Installation:
git clone https://github.com/UmeshBabu7/EcommerceProjectt.git ,
cd EcommerceProjectt

git status
git add .
git commit -m ""

Usage:
Signup:
Customer Registration Form

Username:Babu

Password:1234567

Email:babu7@gmail.com

Full name:Babu Lama Tamang

Address:Bhaktapur

Login:
Customer Login Form

Username:Babu

Password:1234567

http://127.0.0.1:8000/my-cart/
Items in my cart:
SN 	Product 	Rate 	Quantity 	Subtotal 	Action
1 	Men Blazer 	2000 	   1       	2000 	     + - *
Total 	                           Rs. 2000 	Empty Cart
checkout


http://127.0.0.1:8000/profile/
Previous Orders:
SN 	Order ID 	Amount 	Ordered on 	    Status
1 	#ORDER_4 	2000 	16 minutes ago 	Order Received
2 	#ORDER_3 	120 	18 minutes ago 	Order Received

Detail Information:

Name: BabuTamang

Username: Babu

Email: babu7@gmail.com

Address: Lalitpur

Joined on: Feb. 8, 2024, 2:42 p.m.

http://127.0.0.1:8000/search/?keyword=Masks
Search Results for "Masks"
KN 95 Masks
KN 95 Masks...
Return Policy: No return policy

http://127.0.0.1:8000/checkout/
Items in the cart:
Update Cart
SN 	Product 	Rate 	Quantity 	Subtotal
1 	Men Blazer 	2000 	1 	        2000
2 	KN 95 Masks 120 	3 	         360
Total 	                            Rs. 2360



Checkout Form

Ordered by:

Shipping address:

Mobile:

Email:

Payment method:Cash On delivery(Khalti)

Place Order