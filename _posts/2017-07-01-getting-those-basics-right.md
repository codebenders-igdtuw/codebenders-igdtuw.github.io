---
layout: post
title: "Getting Those Basics Right – Algorithms"
description: This blog post will go through the basics of what algorithms are and the hows and whys of algorithm designing.
category: Algorithms
headline: Getting started with Algorithms
tags: [Algorithm Design]
comments: false
mathjax: true
---
While running behind every new language that falls our way, we often forget to brush up our basic roots of computing. Algorithms, or should I say the building blocks of logic, are often ignored when it comes to understanding how and why they came into being.

This blog post isn’t going to talk about how dynamic programming is so important or why you should be thorough with all those Data structure algorithms, rather, we will just talk about the principles of algorithmic design. However, if any of you want us to do a “for dummies” post on a particular algorithm, just go ahead and ping us! We’ll be more than happy to do it.

Well, if you are one of those who don’t completely understand what purpose “algorithms” serve, we are going to try our best to help you see why all the geeks are fretting over algorithms.

Now that we have done some warming-up and ice-breaking, let’s begin! Algorithms, in general, are defined as a set of (conceptual) steps for completing a task, or reaching a specific goal. You can even call them instructions or patterns for finding a solution to a problem in an efficient way. The same problem can be solved in different ways with different approaches, hence different algorithms. What makes one algorithm better than the other, is its **efficiency, accuracy and the boundary cases that it can handle**. One can only make better algorithms if they understand and appreciate the concepts of algorithmic design.

Let’s take a simple example of searching for a number through an array of integers. Going by the brute force and comparing each array entry with our desired number might look like the simplest approach to this, but don’t you think it’s inefficient when it comes to searching a number from say, 2,000 entries give or take?

This is where algorithmic design and the need for a better solution comes into the picture. A better approach to the searching problem might be a binary search wherein you first sort the array, find the middle element and then search only in one particular half depending on the value of your search key. Doesn’t this approach seem to reduce our comparisons and the amount of time we spend on actually finding the number? A complete set of other alternatives are also present for the same, but a detailed discussion on problem solving techniques is a topic for another day. Algorithms are hence, nothing but functions that give you solutions.

So, let’s look at it this way. When you are faced with an everyday problem, what do you do? An average normal human being would probably need a set of steps or an ‘approach’ to deal with it and then implement those steps and _Voila! Problem solved_. 

In a very similar fashion, a developer would be writing long codes to develop an application. We are pretty sure you understand, that the way you encode your logic is going to be a great deciding factor of how well you are able to develop your application. Hence the ‘algorithms’ you write to achieve your goal will also determine how smoothly your development process and later debugging goes.
The possible look-out points for you to consider while forming your logic or algorithms are:

1. **Understand your input:** You should be very careful in handling your input. Depending on whether it is simply numbers or strings or a combination of more than one, you will be able to set appropriate constraints and check for exceptions. 
2. **Know-how of the language you are using:** The flow of every language (function-call stack, loops, exception handling) isn’t the same, so it’s always better to properly understand how your lines of code will affect the flow of control and the overheads of your functioning. You should be familiar with the inbuilt libraries and functions, along with the performance and implementation of low-level functions and utilities.
3. **The application environment:** Developing a good algorithm doesn’t just deal with the immediate application you are intending to write, it also depends on how well your solutions works with the environment which is interacting with your application (it could be the speed of your code rendering strings or the response time of the servers).
4. **Coding for fewer steps:** Try and use language features which reduce your number of operations, avoid the use of nested iterative loops. Recursive divide and conquer often helps in reducing steps. Trying to minimize the size of recursive processes can also help.
5. Well it’s always better to study **advanced algorithms** for better understanding of different approaches to reaching certain solutions. Standard algorithms always form the base of your logic-building, so getting a good hold of that will help you get an edge in the future.

We recommend the following link if you want to play with your status quo and extend your frontiers in the battle field called algorithms:
[https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms](https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms).

Happy learning!



