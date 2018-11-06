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
    <img width="900" src="https://github.com/iletai/space-jekyll-template/blob/master/src/img/object-oriented-programming-oop.png" alt="logo"/>
</h1>
<hr/>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"/></a>
    <a href="https://travis-ci.org/ellisonleao/magictools"><img src="https://travis-ci.org/ellisonleao/magictools.svg?branch=master" alt="build"/></a>
</p>

- :free: - Free
- :tada: - Open Source
- :moneybag: - Paid
- :money_with_wings: - Partially Free

1. [What is OOP](#oop)
2. [Properties of OOP](#properties)
3. [Advance of OOP](#advance)

## oop
 ### What is OOP? 

OOP(Object-oriented programming) 
 * Object 
  > What is Object? It can be a pig, a dog, a human or a pen, table..


OOP have atribute: 

 - [Abstraction ](#abstraction)
 - [Encapsulation](#encapsulation)
 - [Inheritance](#inheritance)
 - [Polymorphism](#polymorphism)

  # abstraction
    - Something here

  # encapsulation
    - Something here

  # inheritance
    - Something here

  # polymorphism
    - Something here
    
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

 
