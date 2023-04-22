---
layout: essay
type: essay
title: "Tricks of the trade"
# All dates must be YYYY-MM-DD format!
date: 2023-04-22
published: true
labels:
  - Design Patterns
  - Software Engineering
---

<div class="text-center p-4">
  <img width="400px" src="../img/coding-standards.png" class="img-thumbnail" >
</div>

As a university student who has spent the last four years dedicating my efforts towards learning how to code, I would still consider myself a beginner. Although I have garnered numerous skills and techniques over the years, I still recognize that there is a lot I haven’t experienced or mastered yet. One of the most valuable abilities that I’ve been taught in college has been design patterns and how to recognize instances where they can be used.

## Learning the ropes
Design patterns can be thought of as tricks of the programming trade. Initially identified by those who have mastered the craft, design patterns offer general solutions and methods to solve common coding problems. The template solutions created by recognizing these patterns give beginner programmers the ability to effectively curate solutions. While it may take someone decades to completely master software engineering, design patterns offer newbies guidance towards solutions for typical coding problems. 

The most recognizable design patterns are the factory, singleton, observer, and model view controller. These design patterns are vital for every programmer to know no matter what level they are at. In the factory pattern there is a class labeled as the factory which can return objects from other classes and return multiple objects. These factory classes are typically more complicated than normal object-oriented (OO) classes. For the singleton pattern, a “global variable” is created in an OO language that doesn’t support global variables. This design pattern is recognized as an antipattern since its use is not encouraged. The observer pattern supports event-driven code through observer objects. Dependencies can be open-ended and altered at runtime. In the model view controller, internal representation of data and its presentation to users is decoupled. This allows for simultaneous development by programmers of different skill sets.

## Diving into the deep end
After learning about these design patterns, beginners can jump into the deep end of software engineering. With these tricks of the trade under their belts, they can tackle problems and be guided towards possible solutions. Undoubtedly there will be frustration and struggle, but design patterns give beginners a floatation device in the deep end.

For me, these design patterns have been used all throughout my college career. Some of the most prevalent patterns I’ve used are the observer and model view controller. 

With many of the assigned applications being event-driven, using the observer was extremely helpful in executing the code. Through a publish and subscribe system, the pages of my team’s application were able to retrieve data from the database and be notified of any state changes. Each subscription acted as an observer and each publication was a subject. On the database’s server side, the collections were published while the clients were able to subscribe to a collection’s publication and display the needed information. Our applications also used reactive data from the observer design pattern using hooks. If a collection happened to be changed on the server side, the data on the client side would be reloaded and updated to reflect the change. 

The development of web applications required the integration of user-interface (UI) and backend components. Using the model view controller design pattern was helpful in finding solutions. The backend model used in all our projects was the MongoDB database. Programmers on our team were dedicated to developing the database and all the collections’ data handling. On the other side, the view was represented by the different pages created for the web application. The programmers developing the user interface dealt with the creation and display of the data to users. Through the model view controller pattern, our team was able to develop the backend and UI components independently and join them together in the end.
