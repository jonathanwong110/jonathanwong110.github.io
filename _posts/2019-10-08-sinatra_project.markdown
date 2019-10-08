---
layout: post
title:      "Sinatra Project"
date:       2019-10-08 05:25:37 +0000
permalink:  sinatra_project
---


For my project, I created an e-commerce store where people can sign up as users and then post items that they want to sell. If users are interested in an item, users can message each other and figure out the details. Users can post items and send messages. Users can choose to edit/delete items only if they're the ones who posted it. Users have the option of deleting a message only if they're the recipient or the ones who sent it.

I had a lot of fun with this project because I felt like I was able to really create and customize a "website". The best part of this project was really trying to think someone else would use this "website". 

It was very difficult at first. A lot of my mistakes came from just trying to figure out how to access the information from one variable to another in the views option. For example, giving each item a user ID or giving a message a user ID. It sounds intuitive at first but it took me a while to figure that out. 

One particular problem that took me a while to figure out was figuring out how to set up the flash message for when a person decides to sign up but picks a username that's already chosen. At first it took me a while on write the code to figuring out how would take the username written in the form and then check it in the User class to make sure its not taken. I then did several trials and errors trying to input bad data into the sign up form with every category (while putting in a username that's already chosen) and it kept putting the wrong flash message. I then just chose to rearranged my code to make sure that every category was filled and then to check if the username is unique.
