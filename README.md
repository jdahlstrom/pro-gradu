Reactive User Interfaces in the Web
===

M.Sc. Thesis  
University of Turku  
Department of Information Technology  
Computer Science  
2015  
Johannes Dahlström

Introduction
---

Interactive software systems have become progressively more complex, driven by the demand for richer user interaction along with the growing multimedia capabilities of modern hardware. Applications are increasingly being written for the World Wide Web platform, and the inherently distributed nature of web applications brings forth its own challenges. Not only are they required to serve an ever-increasing number of users, but also, more and more commonly, to facilitate interaction between users. 

In the recent years, several mainstream object-oriented programming languages used in the industry have adopted concepts traditionally belonging to the relatively academic realm of functional programming. These include functions as first-class values; anonymous functions (lambdas); and combinators such as map, filter, and reduce.

One impetus for this paradigm shift has been the constantly increasing importance of concurrency and parallelism in software. Correctly managing and reasoning about mutable state shared between concurrent threads of execution is notoriously difficult, and the general disposition towards immutable state in functional programming has proven to be a useful basis for building better concurrency abstractions.

Reactive programming is a programming style centered on the concept of propagating change. In a reactive system, a variable can be bound to other variables so that its value changes automatically as a response to value changes in other components of the bound system. A common example of such reactivity is a spreadsheet application, where the value of a cell can be a formula referring to several other cells. The displayed value of the cell is refreshed whenever the value of a referenced cell changes.

Vaadin is a web application framework written in Java, aiming to provide a rich set of user interface components facilitating rapid application development. It also contains a data binding layer for propagating input and output between the user and a data model.

This thesis seeks to answer the question of whether reactive programming techniques are useful in writing user interfaces in Vaadin. Furthermore, it seeks to analyze whether some of these techniques should be adopted by Vaadin itself instead of simply being built on top of the framework.

