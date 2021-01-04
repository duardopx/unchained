---
title: "Multithreading with pthreads"
date: 2020-12-25T02:39:53-03:00
draft: true
---

## Introduction

Yo, for today i'll explain a bit about multithreading. Few months ago in my college, i was started a parallel systems programming course that introduced me to this world of parallel programming, i'll share a bit of what i learned at this course in this post.

## Important Concepts

In this section we will discourse about some concepts that are necessary to understand and primary dont miss understand essential ideas about multithreading.

### Thread x Process

Process is an instance of a program in execution, and an thread can be understand as a segment of a process, it's a execution unit that is a part of an process, it means that one process can have multiple threads, the memory work diferrent with threads and process, while in process the memory is separed by each process, the threads work with shared memory.

### Parallelism x Concurrency x Asynchrony

As the before case, this terms can be easily missused. I'll give an breaf explanation about each or them.

### Parallelism

### Concurrency

### Asynchrony

## Hands on

To check it, we will implement one of the algorithms used in my class, to show the difference between serial and parallel programs. As this mentioned at title, i'll use pthreads library and C programming language, and as a example, we will create a square matrices adder.

## Understanding the problem

The square matrices multiplication are done adding the sum of the products of any elements presents in
