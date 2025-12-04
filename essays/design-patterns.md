---
layout: essay
type: essay
title: "Design Patterns in Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2025-12-03
published: true
labels:
  - Design Patterns
  - System Design
---

<h1> Introduction </h1>

<p>

When users visit Amazon to shop, they notice all the various categories on the homepage, the products displayed on their screen, and the small animations that make the experience feel smooth and modern. But beneath these visual elements are the building blocks of the software itself, and below those lie architectural ideas that act as the fundamental bones of the entire system. Amazon’s platform depends on a set of well tested concepts that developers rely on to keep such a huge application flexible, stable, and maintainable.

</p>

<h1> Define </h1>
<p>

These architectural ideas are known as design patterns. Deisgn patterns are reusable solutions to problems that appear again and again in large, complex systems. They are tested and proven pre-existing blueprints that help and guide software engineers solve recurring design patterns in their code. Instead of reinventing a solution each time a familiar problem appears, developers adapt these patterns to build software that is cleaner, more organized, and easier to extend.
</p>

<h1> Use Case </h1>

<p>
Working on my project, I haven't gotten to really thinking about use cases and implementation of design patterns in my final project. However, after gaining a stronger understanding of some of these design patterns, it is quite evident that they exist in my project even without me knowing of them previously. One important pattern that I have implemented in my web application is the observer pattern through React's useState hook. The useState hook is implemented in various parts of my application. One key implementation of the hook is the submit button on my 'Contact Us' page. The submit button relies on useState to track form input and automatically update the component when the user enters or modifies information.
</p>

<p>

Another use case of a design pattern that is implemented in my application is the singleton pattern. The same database is shared globally across the web application All of the data that is being handled by my web application is stored in a single database. This database is used to store, pull, and update user information. By ensuring one database interface (instead of a new one for every part of code), this avoid data inconsistencies and easy access to data. 

</p>

<h1> Thoughts </h1>

<p>

Design patterns are tools that give structure and stability. While they may not be obvious to all, they exist underlyingly when working on an application. Design patterns help make code easier to understand, easier to scale, and more reliable. As I continue learning and building, I now see design patterns as part of the foundation for writing software.

</p>





<p>

ChatGPT was used to help me gain a better understanding of the 23 design patterns.
  
</p>
