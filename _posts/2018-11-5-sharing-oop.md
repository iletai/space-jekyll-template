---
layout: post
title: "Sharing OOP C++"
image: ''
date: 2018-11-5 01:00:00
tags:
- cpp
description: ''
categories:
- iletai 
---

<h1 align="center">
    <img width="1200" src="https://github.com/iletai/space-jekyll-template/blob/master/src/img/object-oriented-programming-oop.png?raw=true" alt="logo"/>
</h1>
<hr/>

- [What is OOP](#oop)
- [Properties of OOP](#properties)
- [Advance of OOP](#advance)


### OOP
--------

**What is OOP?**
OOP(Object-oriented programming) 

 * What is OOP?
  > Object-oriented programming (OOP) is a programming language model organized around **objects** rather than "actions" and data rather than logic. Historically, a program has been viewed as a logical procedure that takes input data, processes it, and produces output data.
  
 * Why we select OOP?
  > Many years ago, the scale of the software project is small and programmer can sloved it and don't need to much time.And tructured programming(call by procedural programing),this technique is mostly and when project more biger after, we need oop to sloved issues.

---

 * Object 
  > What is Object? It can be a pig, a dog, a human or a pen, table..

 * Class
  > Class include **Object** and Object have attributes and method.

     ```
     Class Pig
     Attributes:
      Color;
      Width;
      Height;
      Weight;
     Method:
      Sleep;
      Eats;
     ...
     ```

### OOP have atribute: 

  - [Abstraction](#abstraction)
    - [Abstraction/Somehere](#somehere)
    - [Spritesheet Tools](#spritesheet-tools)
    - [Bitmap Compression](#bitmap-compression)
  - [Encapsulation](#encapsulation)
  - [Inheritance](#inheritance)
  - [Polymorphism](#polymorphism)

#### Abstraction  
--------
*Great graphics placeholders and tools to turn that squared game into a picasso painting*

#### Encapsulation
--------
*Great graphics placeholders and tools to turn that squared game into a picasso painting*

#### Inheritance
--------
*Great graphics placeholders and tools to turn that squared game into a picasso painting*

#### Polymorphism
--------
*Great graphics placeholders and tools to turn that squared game into a picasso painting*
*Edit here*


       ```
       #include <iostream>

       using namespace std;
       class LearnOOP
       {
        public: 
         LearnOOP(); //Constructor
         ~LearnOOP(); //Detructor
         void DoSomeThing();
         bool GetLearn(isLearn); //Get isLearn
         void SetLearn();        //Set value isLearn
        private:
         bool isLearn;
       }  
       ```

### Properties

### Advance
 
|Acess|Public| Protected|Private|
|--|--|--|--|
|In class|`Yes`|`Yes`|`Yes`
|In inheritance class|`Yes`|`Yes`|`No`
|Out class|`Yes`|`No`|`No`

 <table><tr>
    <td> <img src="https://github.com/iletai/space-jekyll-template/blob/master/src/img/object-oriented-programming-oop.png?raw=true" alt="Drawing" style="width: 250px;"/> </td>
    <td> <img src="https://github.com/iletai/space-jekyll-template/blob/master/src/img/object-oriented-programming-oop.png?raw=true" alt="Drawing" style="width: 250px;"/> </td>
  </tr></table>
  

