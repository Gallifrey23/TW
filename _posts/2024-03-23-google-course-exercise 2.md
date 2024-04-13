---
layout: post
title: "Google TW Course Exercise 2"
date: 2024-03-23
author: Z
---



> [!NOTE]
> * This page provides possible answers to some in-class exercises of [Google Technical Writing Course].
> * The anwers here are only for personal reference, not for commercial use.



# **_TW1-Exercise 4_**

**Improve the following sentences. Feel free to rearrange, add, delete, or modify words as you see fit.**

1. JavaScript, despite the similarity in name to Java, has nothing to do with Java and has more to do with marketing, meaning that the inventors of JavaScript wanted to capitalize on the popularity of the earlier language.

   > **JavaScript was named for marketing reason after the language "Java" became popular. It has nothing to do with Java.**

2. It is important to keep in mind that the career of Katherine Johnson was able to span both the manual calculation era and the time of computer-based computations.
  
   > **Note: Katherine Johnson worked through both the era of human-based and computer-based computations.**

3. Python, which was invented by Guido van Rossum from the Netherlands in 1991, is a language whose primary data type is the list (like Lisp) and that emphasizes readability based on indentation (like FORTRAN).

   > **Python is a language invented by Guido van Rossum from the Netherlands in 1991. It presents two main features:**
   >  * **Use list as primary data type (like Lisp)**
   >  * **Easy to read with indentation (like FORTRAN)**

# <font color=#ffc44d> **_TW1-Exercise 5_**</font>

Jun and Arash are recent engineering school graduates who have just joined your engineering team. In the past, new engineers on your team have not run sufficient internal tests before releasing new products. New engineers on your team usually don't know what the term dogfooding means.

**Revise the following paragraph for Jun and Arash:**

There are several intended primary goals for dogfooding a new project. At the current time, it is suggested by Engineering that all projects be in dogfood for a period of no less than one month. One is to find bugs under heavy, high-cycle usage. When disastrous bugs occurred in 153 out of 157 of the previous project releases, Engineering's analysis of bugs in the aftermath concluded that prevention of the bugs could have happened by more thorough testing.

>It is suggested that dogfooding, which means running internal tests before releasing new products, should be carried out in all projects for at least more than one month. This is because when disastrous bugs occurred in 153 out of 157 of the previous project releases, Engineering's analysis of bugs in the aftermath concluded that prevention of the bugs could have happened by more thorough testing. Therefore, the primary goal for dogfooding a new project is to find bugs under heavy, high-cycle usage.

# **_TW2-Exercise 1_**

A hurried writer wrote the following first draft for a document entitled **An Introduction to Hard Links in Linux**:

You need to know about Linux commands prior to reading this document. This document explains a lot of introductory material about hard links, not soft (symbolic) links. Suppose you run a Linux command that creates a file. When you create this file, Linux creates the contents of that file and a filename. A filename is a hard link to the contents. A hard link is a pointer from the filename to the contents. Now, here's the interesting part: you can create multiple hard links to the same existing content. For example, the command echo "Hello There." > foo creates a file named foo containing the textual contents "Hello There." The command ln foo bar is a way of creating a hard link named bar that points to the contents of foo. Changing foo and bar are now synonymous. You can create lots and lots of hard links to the same content. Any change made to foo will also appear in bar.
	
**Do not revise the sentences; just organize the original sentences into four sections of your choosing. In other words, create four suitable headers and then move the sentences under the appropriate header.**


>**1. Before you begin:**  
You need to know about Linux commands prior to reading this document.  
>**2. Short description:**  
This document explains a lot of introductory material about hard links, not soft (symbolic) links.  
>**3. What is hard link?**  
A hard link is a pointer from the filename to the contents. Suppose you run a Linux command that creates a file. When you create this file, Linux creates the contents of that file and a filename. A filename is a hard link to the contents.  
>**4. How to create hard links in Linux?**  
Now, here's the interesting part: you can create multiple hard links to the same existing content. For example, the command echo "Hello There." > foo creates a file named foo containing the textual contents "Hello There." The command ln foo bar is a way of creating a hard link named bar that points to the contents of foo. Changing foo and bar are now synonymous. You can create lots and lots of hard links to the same content. Any change made to foo will also appear in bar.  

# **_TW2-Exercise 2_**

During this part of the exercise you will review a paragraph relating to one part of the complex diagram you saw during the in-class discussion. The audience for this set of drawings is Intro to Computer Networks students.  
Using Google Drawings, create a diagram that represents the following paragraph:  
When the Domain Name Server (DNS) resolver first receives a request from a client, it asks the Root Server about what Top Level Domain (TLD) server it should talk to next. The Root Server replies to the resolver with the location of the relevant TLD server.

> [A revised diagram for reference](/images/google_exercise/revised_diagram.jpg)

![revised diagram](/images/google_exercise/revised_diagram.jpg)


# **_TW2-Exercise 3_**

Describe the appearance of a thumbtack (not a pushpin) without using mathematical measurements, illustrations, or photographs.

>## Description of a Thumbtack  
>This document explains the appearance of a thumbtack. This document does not describe the usage of thumbtack.    
>A thumbtack resembles a pushpin, except that a thumbtack has a flat, round metal top whereas a pushpin is characterized by its small ball-shaped plastic head.
>**A thumbtack consists of the following two parts:**  
>### 1. A Flat Round Top  
>The top of a thumbtack is usually made of metal and in flat, circular shape. It looks like the top of a nail, but usually thinner. 
>### 2. A Short Sharp Pin
>The short sharp pin on a thumbtack is pointed at one end, with the other end adhere to the flat round top. The pin is similar to a needle, except that it doesn't have a hole on the top.



[Google Technical Writing Course]:https://developers.google.com/tech-writing/for-instructors


[◀️Back to home page](https://gallifrey23.github.io/)
