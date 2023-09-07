---
layout: essay
type: essay
title: "Smart Questions on Stack Overflow"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Forums
  - Stack Overflow
---
<img width="300px" class="rounded float-start pe-4" src="../img/smartQuestions/smartQuestions.jpg" style="float: left; margin-right: 10px;" />
<div style="clear: both;"></div>

# Analysis of a Smart Technical Question

## What is a Smart Question?

A smart question is specific, concise, and well-researched. It provides enough context for the reader to understand the problem, including code snippets, error messages, or related documentation. A smart question shows that the asker has put in some effort to solve the problem themselves and is clear about what they are asking.

---

## What is a Not-So-Smart Question?

A not-so-smart question is vague, lacks context, and shows little to no research effort. It may be missing crucial details like code samples, error messages, or a description of the desired outcome. These questions make it difficult for others to provide meaningful assistance and are less likely to attract expert help.


---
## Example Question:

**I have been doing some code with the help of stackoverflow people. I have collect data, filter them, and then sort them. but I get suck when I want to go to the next step.I have been doing some code with the help of stackoverflow people. I have collect data, filter them, and then sort them. but I get suck when I want to go to the next step.**

**Here is the code : function FILL_PROJ_005() { //function content }**

**In the function var PROJECT_LIST = DATA_SORTED.getRange(1,1,1,1); I would like to extract only some value of the DATA_SORTED ( at the end I need all the column “B”, and .getRange(1,1,1,1); is just a first test.) But I get this error message : TypeError: DATA_SORTED.getRange is not a function I understand that the result of var DATA_SORTED is an array, but how do I convert it again into values that I can continue to filter ? I have try to use .map, but I felt to understand how to use it…**

**Here is a sample of the data I’am working on : //sample**


[How do I convert an array into values?](https://stackoverflow.com/questions/77061273/how-do-i-convert-an-array-into-values)

---

## Specificity and Context

The question is highly specific, outlining what has been done, where the person is stuck, and what the end goal is. This makes it very clear for anyone trying to assist, offering them immediate understanding of the problem space.

---

## Self-Troubleshooting

Before posting, the asker has attempted to solve the issue themselves. They even pinpoint the TypeError they've encountered, signifying an understanding of the issue at hand. This shows a proactive approach, making it easier for helpers to step in with targeted suggestions.

---

## Detailed Information

The question comes with both the code and a sample dataset. This completeness allows for a full understanding of the situation, saving time and back-and-forths for everyone involved. Code is also well-formatted, which increases readability and helps potential helpers to identify issues more quickly.

---

## Openness to Learning

The asker is upfront about the areas they don't understand and is open to learning. This encourages potential helpers to not only provide a solution but also to educate the asker about the concepts involved.

---

## Inclusion of Error Message

Including the exact error message helps potential helpers diagnose the issue quickly. This often speeds up the troubleshooting process and makes it easier for those answering to provide immediate and relevant guidance.

---
## Analysis of a Not-So-Smart Question

**The question "I'm having problems with my code. Can anybody help?" is considered not so smart or effective for the following reasons:**

### Lack of Specificity
The question doesn't specify what the problem is. Is it a syntax error, a logical error, or something else? Without this information, it's impossible for anyone to provide targeted assistance.

### Missing Context
There's no code snippet, error message, or even a description of what the code is supposed to achieve. Context is crucial for troubleshooting issues in programming.

### Vague Language
The word "problems" is too vague. It doesn't convey whether the issue is with a particular function, the entire program, or perhaps something more abstract like performance or security.

### No Indication of Effort
Good questions often show that the asker has tried to solve the problem themselves. This could be through sharing error messages they've received, explaining troubleshooting steps they've already taken, or providing sources they've consulted.

### Inefficient for Both Parties
The lack of information means that anyone willing to help will need to ask for more details first. This results in a longer time to get to a solution, making it inefficient for both the person asking the question and those attempting to provide help.

### Discourages Expert Help
Experts are more likely to engage with well-formulated questions that show research effort and provide sufficient detail. A vague question is less appealing because it suggests that the asker has not invested time in framing their question or attempting to solve their problem.


