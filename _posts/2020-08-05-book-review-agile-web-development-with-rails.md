---
layout: post
title: Book Review - Agile Web Development with Rails 6
date:  2020-08-05
---

![](/assets/book.jpg)

Agile Web Development with Rails 6 is written by Sam Ruby, David Bryant Copeland and Dave Thomas with some some excerpts from DHH (The creator of Ruby on Rails).

I read this book after learning Rails a little bit before. It's hard to for me to jump straight to reading for learning something completely foreign once I understand the basics I love to read.

The book is has 3 sections I'll go over the three sections instead of the chapters and provide my takeaways.

## Part 1 Introduction & Getting Started

This section is a crash course on Ruby on Rails,  which is good it doesn't bog you down with by going too deep. Instead this section gives you just enough to know the important parts to get started building something. It expresses the benefits on building applications with Rails and the philosophies behind Rails like Convention over Configuration. 

You start by installing Rails on different OS's. Once you have everything installed you go straight into building a small app you can use Rails in practice. I like this part because it will show you a command or some and explain what you just did. It lets you see it and type it first, so you have a frame of reference when you read about it.

By the end of the 2nd chapter you have a built small app using the fundamentals parts of a Rails app. From starting a new app with the `rails new` command to creating controllers, editing your views eRB's with links and more. 

Then it goes on to explain how Rails works with routing and the MVC pattern. It also has an gentle introduction to Object-Relational Mapping(ORM). It's follows that with a example that gets broken step-by-step


> Active Record is ORM layer supplied with Rails it maps database classes to classes, row to objects, and columns to object attributes. 

Then before you get to building an application you learn just enough Ruby to under whats going on in the app. You'll understand better by the typing in the code and seeing the patterns that emerge, this is a lightning intro to Ruby.


## Part 2 Building an Application 

This section was all about building a shopping cart application. You mostly used Rails scaffolding to build the app. It's not something you would use everyday though. You also get introduced to testing in Rails. There quite a few blurbs from DHH in this section with his thoughts on certain topics like picking good fixures names. 

> You want to keep fixtures as self-explanatory as possible. This increases the readability of the tests

One of my favorite parts of this section is getting an introduction to React. I wasn't expecting that. One of the new features of Rails 6 is there is a webpacker gem. This section show how to use webpacker to install React and create a component, write JSX and import components. I never thought I would get such a gentle intro to React from a Rails book.

This sections introduces all the amazing features that makes Rails such a complete solutions for building apps. It includes defaults so you can focus building and providing for your users. I was blown away everything that is included. 

You'll learn about:

* Action Cable - for real-time updates like (price changes)
* Active Storage - to set up cloud storage 
* Action Text - A rich text editing system from Basecamp
* Action Mailbox - Receive incoming emails 

One thing we didn't learn about in depth is Turbolinks. It's something I want to look into it a way to make your apps work like a single page app. It's show you how to use AJAX with Rails to only reload part of the page. For a better user experience.

## Part 3 Rails in Depth

This is the section where every you just built gets broken down, now you have code to reference to put together with the explanations you're reading. Nothing is better than having something real and functioning to compare these explanations to. 

This section focuses on the core of Rails Models, Views, Controllers and your database.

## Conclusion 

I prefer watching videos but I wanted to try something different. If your are new to Rails I would recommend this book takes your time to digest it and take notes because it will feel like it's moving really fast. I think it does a good job of bringing everything home and not leaving in the dust.

Thank you for reading! 

