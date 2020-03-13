---
layout: post
title: A fundamental way to reason about technology
author: ahmad
tags: [Digital, Essay]
image: '/images/posts/26.jpg'
---

> Architecture. 

Chances were, that the first image that came into your mind after reading that word, was that of a building. Another fun fact – pieces of code, of instructions that make up software are called ‘Builds’! Developers, Routes, Storage, Architects, Stacks, the more you understand the glossary of the digital world you soon realize, that despite being so abstract – it is actually a mirror of our physical world.

> Being human in the digital world is about building a digital world for humans. - Andrew Keen

Modern research in physics, has revealed that underneath the quantum level lies another level, a level from which space and time (physical reality) both emerge (the wavefunction) - and that is  at the level of ‘information’. Perhaps this is why the dawn of the information age, propelled our world to exponential heights. 


So here is the question, ‘what made it so transformational?’ A clue to begin the search for this answer, lies in what happened when humans began to, not just collect information, but arrange and organize it effectively towards a single goal - To transform the environment that surrounded them and bend it to their will.

##### The Transformation of one’s environment

There is a pattern that manifests itself throughout human history as we sought to transform our environment. The Model-View-Controller. A horse drawn cart is replaced by a diesel engine because humans began to think of information related to the model (transportation systems) as separate from the view (horse or engine) and the controller (coachman or driver).

![alt](https://images.unsplash.com/photo-1562657551-5ca50b25d3da?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1355&q=80)

This is a very effective way to reason about and articulate problems that address specific concerns, without having to dream up a completely new idea. For example, incremental improvements can be done by improving the Controller. Innovation can be achieved by changing the View. And radical re-thinking can be achieved by changing the Model. 

Let’s get back to the horse and cart situation — better transportation time can be achieved by getting a better coachmen (controller); unthinkably better times can be achieved by replacing the horse with an engine (view); and entire societies are transformed with the ability to make a car appear by pressing two buttons in the palm of your hand. (the model).

![alt](https://images.unsplash.com/photo-1554672408-730436b60dde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=667&q=80)

### Using another example, this time from banking:

*    Improving the controller (logical & algorithmic efficiency) may result in a better transaction speeds; 
*    Improving the view will change the user experience (i.e. banking experience — branch to web to mobile);
*    Improving the model (i.e. crypto-currency) seeks to radically transform society.

Let us now use this image to understand how the digital world works, from a web development perspective.

---

> Graphic design is the paradise of individuality, eccentricity, heresy, abnormality, hobbies, and humors. — George Santayana

#### Model-View-Controller: Web development
Let’s start with the View, as it resides on the upper most part of the information ‘Stack’.
##### View
The view, as its name implies refers to what is ‘rendered’ on your screen. The word rendered is used because what you see, right from the colors, fonts, animations, styles, the layout every single icon has instructions written in code. The people who do this are, ‘Front End Developers’, as the name suggests – working on what is seen and experienced – the front end. As we have architects for buildings, we have ‘User Interface Designers’ who create the interfaces.
The tools and languages used to create views:
* HTML – Hypertext Markup Language: Is like an information templating system to plan information layouts on the screen.
* CSS – Cascading Style Sheets: These are instruction templates that deal with the styling of the HTML
* JavaScript – Also referred to as JS, They integrate instructions and enable interactivity with the information presented using HTML/CSS. They can listen to events, that is - if a mouse has clicked a part of the page, if you have swiped left, or if you have filtered a data list for visualization. All the interactivity you have experienced in the modern web is thanks to JavaScript.

##### Model
The model is probably the hardest to define. Can the model be a scaffold — like a view-model — on which actual data gets mounted? Now we are thinking of modelling visual representations. Can a model contain business logic? What if you had an Account model and it had associated maintenance fee, interests rate, and rules for how they are applied — could you now query the model to get insight on how much money I will have after 5 years? The Model is essentially, structured data, arranged as records - like the ones you find on a spreadsheet. The model only represents the data, it does nothing else. It does not depend on the controller or the view. The people who do this are called ‘Backend Developers’.

There are many tools used to create and store models, for our scope in this article I shall focus on databases, in particular – relational databases and non-relational databases.\

* Relational Databases (RDBMS – Relational Database Management System): These are similar to what you see on excel. They store data in columns and rows - tables. A collection of tables make a schema. A number of schemas create a database. Relational databases are robust, and are used when the data is structured. Some of the popular relational databases are: MySQL, PostgreSQL, SAPHANA, 

* Non-Relational Databases: These are more recent, and are an innovative way of storing data. Here data isn’t stored in a tabular form. You can think of it as Data stored as documents on a bookshelf. Another way to look at it would be like your folder on the PC. You can have audiofiles, videofiles, slides and documents all in one folder irrespective of the file type. It follows similar fashion here. With more and more businesses getting into big data, non relational databases make it easy to store, retrieve and manipulate data. Some of the popular non relational databases are: MongoDB, Cassandra, Redis, Neo4j

##### Controller
The controller is easier to explain. The controller ties the model to the view. It is the layer sandwiched between the view and the model. It contains all the logic as well as the routes to the data model in the backend. Information architects and User Experience designers play a critical role in providing inputs to design controllers that fetch data from the backend and present them in the view. 

---

#### Tying it all together from the physical world

Let’s reinforce what we have learnt so far by going back in time to consider a situation without digital technology. Imagine a store clerk at an auto parts warehouse. A customer comes in and says he wants to buy brake pads for a 1992 Honda Civic. 
* The clerk looks up where that part is stored in the warehouse and brings it to the customer. 
* The customer inspects it and then moves to the other clerk at the cash register to purchase the part. 
* The second clerk inspects the part and asks for a specific amount of money to complete the transaction.

In the first scenario — looking up the part — the view was the physical part, the model was the part as a component of the warehouse inventory. In the second scenario the model was still the part as a component of the warehouse inventory, but the view was the price. In this contrived scenario we have two controllers — the clerk that finds the part based on some query parameters, and the clerk, that given a part, requests some money.


#### Interpretation into the digital world

1. Bringing it back to the regular web application this process becomes easily translatable. On a landing page we look for a part. Our initial view is that of a search field that provides an interface to find something we are looking for.

2. As we click “Search” this information is passed to a controller that then finds the model that matches, ties it to view and returns it back to the user. The user looks at the view of the search results — essentially one or more models — and makes a choice.

3. A different controller then takes the model(s) and renders a new view that now will show the price, the sales tax, shipping information etc.

> In short, we have many controllers tying models to different views. Each view arises out of the customer needs identified in the physical world.

---


### The oppurtunity for transformation
Let us conclude by tying some philosophical musings with the concrete ideas behind the model-view-controller.

* If you are a looking for gradual improvement, or improvement in performance - look at changing the Controller. 
* If you are looking for innovation, look at changing or presenting a different View.
* If you are looking for Radical Transformation look at changing the Model.

Most techies may look at the Model-View-Controller as a mere pattern or an architecture, but it has a more powerful purpose. It provides a fundamental way to reason about technology.

In the next session we are going to understand the process of building. Say you wanted to build an app. How would you go about doing it? Where and how would you start? What are the steps and resources involved and how does anthropology, design, engineering and digital innovation fit into all this. Stay tuned.

---






![alt](https://images.unsplash.com/photo-1433785567155-bf5530cab72c?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&w=1080&fit=max&s=1348aea714b9493fa61a09a8c01113e6)