---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Crafting a Mini Bank Database Using C++"
date: 2014
published: true
labels:
  - Lisp
  - GitHub
summary: "A Mini Bank Database that I developed for ICS 212."
---

<img class="img-fluid" src="../img/cotton/bankHeader.png">

Constructing a bank database for my ICS 212 course required not just mastery of C++ but also a solid understanding of database design principles. Given that this was a class assignment, the goal was not just to build a functioning database but to develop one that met the rigorous academic criteria of data integrity, efficiency, and user accessibility.

Requirement Analysis: Setting Parameters
Initially, the primary task was to understand the assignment's requirements. What exactly was expected from a "bank database"? After studying the guidelines, it was clear that the database needed to perform basic operations like adding, deleting, and updating customer records, and it needed to do this efficiently and securely.

Data Structure: The Backbone
The first significant challenge was selecting the right data structure. Given that the database required fast lookup times, I opted for a hash table. This decision set the stage for the rest of the project; the effectiveness of every subsequent operation would hinge on this choice.

Coding in C++: Logical Implementation
Once the data structure was in place, I moved on to the coding phase. This meant implementing all the logic in C++. Despite C++ being a versatile language, it does have its quirks, especially when it comes to memory management. Allocating and deallocating memory efficiently was crucial to prevent memory leaks, ensuring the database's smooth operation.

Debugging and Testing: The Litmus Test
As with any code, debugging was a necessary and often time-consuming process. Syntax errors were the low-hanging fruit, easily caught by the compiler. The logical errors, however, were far more elusive and demanded rigorous testing to identify. Once identified, these were iteratively corrected and re-tested.

User Interface: Streamlining Access
Since the database would be used by individuals without a technical background, the user interface needed to be intuitive. Though C++ isn’t known for its UI capabilities, I employed a simple text-based menu to facilitate ease of use.

Final Checks and Submission: Meeting Academic Standards
Before submission, the code went through a round of optimization to improve efficiency and was checked against the assignment's requirements one last time. This ensured that it met all academic criteria, from algorithmic efficiency to code readability.

The Verdict
The project was complex but straightforward when tackled systematically. Each phase, from planning to coding to testing, presented its own challenges, but these were met through a mix of academic understanding and practical skills. Post-submission, the database was reviewed favorably, signaling that the meticulous planning and rigorous implementation had paid off.

In sum, the project underscored that the road to building a robust bank database in a classroom setting is fraught with technical and academic challenges. However, these are not obstacles but rather crucial components that contribute to the overall educational value of the assignment.
