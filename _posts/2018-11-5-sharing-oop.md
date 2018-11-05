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

 # OOP
1. [What is OOP](#oop)
2. [Properties of OOP](#properties)
3. [Advance of OOP](#advance)

## oop
 ### What is OOP? 

OOP(Object-oriented programming) 
 * Object 
  > What is Object? It can be a pig, a dog, a human or a pen, table..


OOP have atribute: 

 - [ ] Abstraction
 - [ ] Encapsulation
 - [ ] Inheritance
 - [ ] Polymorphism
 
 <div style="height:700px; width:900px;">
  <script src="https://gist.github.com/iletai/21c847bdc2b498ae57f9ed1557663bcf.js"></script> 
 </div>

{% highlight javascript %}

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
 
{% endhighlight %}

## properties

## advance
 
|Acess|Public| Protected|Private|
|--|--|--|--|
|In class|`Yes`|`Yes`|`Yes`
|In inheritance class|`Yes`|`Yes`|`No`
|Out class|`Yes`|`No`|`No`

 
