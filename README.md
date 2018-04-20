# SDP Project

This will be the stage-two evaluation of the SDP on Open Source Tools. This document contains the details to complete your stage-two project successfully. This project prerequisites you to form groups, i.e. you will be working in groups. The project is designed in such a manner that, you will revise all the content that you've learnt during the 3 sessions and much more if you are willing to.

Make sure to read the entire README.md before you proceed.

## The Basics

The project shall focus on key areas of the SDP sessions namely:

-   Python
-   HTML
-   Git

We recommend that you go through the "Before the project" section below to get up and running.

## General rules

This section has a set of rules that you need to follow:

-   You need to form a team of 3-5 members
-   The repository contails 5 sets of questions. You need to solve any 3 of your choice
-   Each and every person in the group must have their own repository i.e, you can divide the questions amongst your team members but, make sure all of you have your own repositories with all the solutions in it
-   The answer to one question must be one commit, i.e. if there are three questions, your repository must have three commits
-   On the day of presentation you will be asked to explain what you have done. So, you might as well know what you are doing so that you won't have a problem later.
-   You can submit partial answers, although you will be scored accordingly

## The Projectwork

The project work has three parts to it. We will see them one by one now.

### Part 1

This part deals with Python programming language. So, what you need to do is pretty simple.

You will be given a program in C programming language, you will need to port that code into a valid Python 3 code.

For, example conside the following C code:

```C
#include <stdio.h>
#include <string.h>

int main()
{
   char source[1000], destination[1000];

   printf("Input a string\n");
   gets(source);

   strcpy(destination, source);

   printf("Source string:      \"%s\"\n", source);
   printf("Destination string: \"%s\"\n", destination);

   return 0;
}
```

If you haven't already guessed it, well, I am just copying a string from one location to another.

Now the valid Python 3 code for the above C code would be:

```Python
import copy
a = input()
print("Source string: " + a)
b = copy.deepcopy()
print("Destination string: " + b)
```

**Hint: You can run the C code on your computer to figure out what it is doing to easily convert it to its corresponding Python script. Remember, you need not convert line by line. We expect an algorithm port from C to Python. If you do not prefer the former approach, you can do it in your own way.** :sunglasses:

### Part 2

The HTML part would be pretty straight foreword. This deals with presenting your answer. You need a render that looks something like this...

![HTML render](https://github.com/GLUG-REVA/SDP-Project/blob/master/images/Example.png)

Now this requires you to just Google for one tag in HTML that we haven't covered. We will be kind enough to provide you with a place where you can look for it.

[Click here](https://www.w3schools.com/html/default.asp) and you shall be directed to w3c website where you can find what you are looking for and much more.

### Part 3

The last and the simple part is to push your code to git. A caveat here is that you will need to push your HTML file that looks like something that we showed you above, to your git repository.

* * *

And that's it. You are done with your project.

## Before the Project

We would just like to point out a few points before you start your project.

### Setting-up Git on your system

We recommend that you work on Linux operating system, if for some unfortunate reasons this is not feasible, you can complete your project using [Git for Windows](https://gitforwindows.org/).

For setting-up Git on Linux or macOS we recommend going through tutorials for respective operating systems.

Look [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for instructions.

**_Note: Please, read the instructions carefully before you execute them._**

### Some useful links and pointers

We have listed some websites that you can visit if you get stuck anywhere:

-   [Git documentation](https://git-scm.com/book/en/v2)
-   [HTML reference](https://www.w3schools.com/tags/default.asp)
-   For python, you could just simply google your need and Google will point you in the right direction. [Python tutorials Point](https://www.tutorialspoint.com/python3/index.htm), [Stackoverflow](https://stackoverflow.com/) are some of the most trusted and used websites. If you are feeling adventurous you can seive through the [python3 documentation](https://docs.python.org/3/):stuck_out_tongue_closed_eyes::sunglasses:
-   Please make sure that you google for python 3 instead fo python 2 as there are significant syntax changes and the scripts might not always be cross-compatible

## By the way...

#### Your evaluation date is on the 10th of March 2018.

If you have any queries, you can reach us at:
k.saisomanath@gmail.com or
akash.james2096@gmail.com

### **_Good luck, padawans!_**
