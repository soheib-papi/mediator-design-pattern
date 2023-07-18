# mediator-design-pattern
Implement mediator design pattern in C#.

Resource: [https://refactoring.guru/design-patterns/mediator]


## Intent
Mediator is a behavioral design pattern that lets you reduce chaotic dependencies between objects. The pattern restricts direct communications between the objects and forces them to collaborate only via a mediator object.

## Problem
Say you have a dialog for creating and editing customer profiles. It consists of various form controls such as text fields, checkboxes, buttons, etc.

![Relations between elements of the user interface can become chaotic as the application evolves.](https://refactoring.guru/images/patterns/diagrams/mediator/problem1-en.png?id=86f99055b3e60bb8834dcc7222922bdf)

## Solution