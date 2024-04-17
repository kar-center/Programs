### What is this program?
It gives you a single path among many to consider yourself a junior backend enthusiasts.

### What does it require?
1. analytic mindset
2. passsion to finish what you start
3. around 4 hours a day for 2 months


### How does it work?
1. You continue your studies as state in section below
2. You do your project as scheduled in section below
3. You communicate with one of Kar.Center backend developers for one hour each 2 days to get hints, answer questions and general guidance

### Program:

### Chapter 1: Basics of Machines - 2 week
Study these subjects as much as you think you require to feel confident,  
Each of these can bring you a PHD so don't dwell too much.


* Theory:
  1. turing machines, what is computation?
  2. john von neumann computer model
  3. shanon information - speed duality, practical things have an upper cap
* Fundementals:
  1. how OS works? what is kernel
  2. networkig OSI model, how computers communicate
  3. ram, heap, stack and all other jargons
  4. a C program from source to execution, how does it load into memory and get processed ?
  5. concurrency and race condition, locking and interrupts


**Project:**

implement these in C:
* linked list
* hash map
* Graph (with adjacent list)
* BFS, DFS and Dijkstra Algorithms on that Graph 

### Chapter 2: virtuality - 1 week
in this chapter we aim to understand how virtualize oir execution on a virtual machine (or interpreter)

compare and find differences in each of these execution frameworks:

* node.js
* python
* java
* .net core

how do they execute their code on every machine without recompiling for that specific CPU architecture?

we mostly use jvm-based languages (kotlin tbh) but feel free to choose any language in above list and familiarize yourself with your choice

### chapter 3: functional and oop

you have a data, you have a function, you have a scheme - you have a data function scheme apple pineapple (dad joke) 

what are classes?  
what is instance?  
what is constructor? 
what is inheritance?  
what is each of these?  
* class
* abstract class
* interface

what are public protected and private modifiers?  
what is static?  


also check design patterns:

* singleton
* facade
* factory

also check these keywords and see examples:
* higher order functions
* listeners and hooks
* event driven



** Project 2 **

* the Code Cafe:

we have a cafe called CC which stands for Code Cafe,  
our cafe is entirely made of machines and no human is there to cook, pour, wash or stock our inventory 

we bought all the robots and they require some clean and maintainable code!

they work as follows:
* we have `RegisterBot` which tracks our budget
* we have `ShopperBot` which buy our stuff
* we have `ChefBot` which turns stuff into food and drinks
* we have `OrderBot` which keep track of orders of customers
* we have `InventoryBot` which keep track of our fridge
* we have `WasherBot` which wash dishes and make them clean again
* we have `ServerBot` which serve ready orders
* we have `CleanerBot` which cleanup tables and gather dirty dishes
* we have `ManagerBot` which can create new bots and destroy them to optimize our cafe as required


* all `Bot`s have some shared attributes like how much energy they use for each operation and how much time they take to do one of their functions and how much they are cost for buying or being sold.

customers will flow and they need to be served with least amount of time and most amount of profit.

run this simulation in best possible way to optimize this cafe.


start from basic and add complexity layer by layer and have tests from the begining to aid you while developing this (see JUnit or any test framework that your language supports)

your code will be graded and is required to gain at-least 80/100 (which is given based on attributes like clean-code, comments (not useless vomit comments), tests (both failing and passing ones), loose coupling, use of patterns and inheritence and good message passings)

you can submit for review for any number of times.


