---
layout: post
title:      "Rails Project"
date:       2019-11-10 21:58:00 +0000
permalink:  rails_project
---


For my project, I continued on the topic of e-commerce. People can sign up as users and post items they want to sell but now users have a cart where they can add others' products to it or clear the cart. Users can also submit reviews and then later choose to edit and/or delete it. Users can still only edit/delete resources that they themselves created. People can also register/login via GitHub. I decided to create a Review controller/model because it would resemble e-commerce stores more as people would normally look at reviews before making a purchase.

It took me a while to first figure out the logistics of the project, especially the has_many :through relationships and figuring out how the Cart would fit into the project. It initially took me a while to figure out how to access information from one class to another and figured it would be best to create a join table. For example, I created a join table for Users and Products and Carts and Products.

I had a few problems when submitting information from one controller to another such as submitting the id value from a particular product and setting it as  the product_id attribute of a review or adding a product to a cart. It was a trial and error process. Another problem was renaming the update method in Cart to add_to_cart to make the name more accurate to what it does. After changing the name, I would have to create a custom URL for the form that submits products to cart.

Figuring out how to register/login into my app via Github took a while as well. Even after figuring out how to login, it took me a while to figure out how to create a new cart. That is because in my app, once a user is created, a cart is created as well. Every user only has one cart and it would be best if the creation of the cart was to happen right after registration.

It also took a while to figure out how to nest the routes optimally. I figured it would be best to route users and products excluding products#index as that would be unnecessary. It would be best to nest the two together for products#show, products#new, and users#show. I left nesting routes near the end because I wanted to get all of the app's functionality down first but after doing it, I should have done it in the beginning.
