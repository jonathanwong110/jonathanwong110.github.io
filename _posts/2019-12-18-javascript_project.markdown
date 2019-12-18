---
layout: post
title:      "JavaScript Project"
date:       2019-12-18 05:00:27 +0000
permalink:  javascript_project
---


For my Rails-JavaScript project, I continued on the topic of e-commerce. Users can post products and view other products and their reviews. Users also have the option to update the products’ attributes (title, price, description).

Some parts of the project presented difficulties. When I first made a function to respond to double clicks (called handleProductClick), it would be invoked anytime the (“product-container”, where the products were held in the HTML”) was clicked. I didn’t know whether or not I was assigning it properly or whether or not I should have iterated inside the container instead. Eventually, I realized I needed to add a class to each element of a product and have a conditional statement check for that in order for the function to run. This alone was the biggest hurdle of the project just because my other CRUD functions would also be invoked such as showProduct and deleteProduct.

Figuring out how to do a showProduct function (to highlight a specific product) was also difficult. At first, I took the HTML of the respective product that had its show product button clicked. Then I realized, it also took the buttons as well, which were unnecessary in highlighting said product. So instead, I created a div to hold the highlighted product and had my function recreate all the elements of said product and appended all of those inside the div. It then took me a while to figure out how to access all of the products and then it took me even more time to figure out how to get its respective reviews.

