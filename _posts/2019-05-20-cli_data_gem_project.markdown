---
layout: post
title:      "CLI Data Gem Project"
date:       2019-05-20 22:47:02 -0400
permalink:  cli_data_gem_project
---


     I created a CLI gem which scrapes from a website, for my first portfolio project. While it was overwhelming and difficult, it was fun. I recently finished the coding and the recordings (the recordings of which had to be done several times done over).  My gem scrapes from the Uniqlo's Men's T-Shirt section, providing a list of all the items posted on that section of the website. My gem then allows you to enter a number corresponding to an item and then provides you with the price and URL for said item. From there, you can enter the option to either see the list of items again or exit the program.

     I ran into several issues while doing this project. One simple issue I had that took me a while to solve was when I was scraping the prices for the t-shirts. Sometimes t-shirts would be on sale and Uniqlo would show the original price and then the sale price. To fix this, I simply added a .last before .text so it would grab the last value (the sale price because its the current price).
		 
		 Another issue I was running into near the end of my project was when my program would scrape a list of items, the numbers of the items would accumulate. For example, say if 1 - 50 objects were scraped from the website and if I were to enter the option to see the list again, the t-shirts in the program would be numbered from 51 - 100. To solve that, I would have my program only add the products to the list once by using ".length". I made it so the items would add themselves to the list of the length of the array were 0, only allowing for the items to add themselves to the list once.
