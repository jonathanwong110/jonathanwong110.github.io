---
layout: post
title:      "UltimateStore -- React-Redux Project"
date:       2020-02-09 23:53:23 -0500
permalink:  ultimatestore_--_react-redux_project
---


   For my React-Redux project, I created an e-commerce store. Users can post products for sale and view others and their reviews or delete products. Users can also add items to cart.

   There were many difficult parts in this project but one that stands out in particular was getting the reducer to add a product to cart. I had no idea how to transfer over the information from the action to the reducer. Eventually through trial and error, I had to use Object.values and use action.payload as an argument in order.

   Another difficult task was getting the products to render through their respective categories. It took me a while to come up with how to do it, especially when I realized that I had to use state/useState in the ProductsContainer and then using the proper “links” to make the page seem more interactive for the user when a category is clicked.

   My favorite part of this project was using React-Bootstrap. I didn’t even know it existed until right when I started the project. It was fun being able to style the webpage so creatively without using CSS (not that there’s anything wrong with CSS!).

