---
title: "Multithreading with pthreads"
date: 2020-12-25T02:39:53-03:00
draft: true
---

## Introduction

Yo, for today i'll explain a bit about multithreading. Few months ago in my college, i was started a parallel systems programming course that introduced me to this word of parallel programming, i'll share a bit of what i learn at course in this post.

So, whats is parallel programming in reality? it's a way to approche the multicores of an CPU. It means, insted of use a single core as a serial way, the developer can use all the cores on the system for split tasks performed by an algorithms to get an speed up.

**parallel image**

## Important Concepts

### Thread x Process

Both are independent sequences of code, some times you can see this terms treated as the same, but it's not. properly the core diferrence between both is that process works run in a saparated memory space, while threads running on shared memory space.

### Parallelism x Concurrency x Asynchrony

As the before case, this terms can be easily missused. I'll give an breaf explanation about each or them.

#### Parallelism

#### Concurrency

#### Asynchrony

## Hands on

To check it, i'll show one of the algorithms used in my class, to show the difference between serial and parallel programming. As this mentioned at title, i'll use pthreads library and C programming language, and as a example, we will create a square matrices adder.

## Understanding the problem

The square matrices multiplication are done adding the sum of the products of any elements presents in
