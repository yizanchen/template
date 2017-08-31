---
layout: project
type: project
image: images/8p.jpg
title: 8 Tile Puzzle Solver
permalink: projects/puzzle
date: 2016
labels:
  - Puzzle Solving	
  - Common Lisp
  - Path finding
summary: This was one of the project for my AI class and was one of the most diffcult project in that class.
---


This was the final project for my ICS 361 AI class, which is also the class that grows my interest in AI but that is a story for another day.In this project, I had to implement A* and Breadth-first search in Prolog to solve the 8-tiles puzzle by finding a solution path from a given start. The main intention of this project was to show the difference between Clisp and Prolog because there was a previous project on this problem in Clisp. 

This was a difficult project that cost a lot of times and works despite the previous experience. The main reason is the lack of experience in Prolog and declarative language because unlike programming language I learned before (Java/C++), Prolog programs are built with rules, a lot, and a lot of rules and some functions to put those rules to work. So, after a lot of research online, I found out the "easy" way is to write out all 48 moves of the 8-tile puzzle game as Prolog rules. It was an unbelievable fact to accept because in Clisp I just need few generator functions.


(24 of the 48 rules)

<img class="8pc" src="/images/8pc.jpg">


Actually, half of my research time was on how to do the project without writing all 48 rules and even though I went back to doing it the "easy" way, I learned a lot from my searches. This is also a lesson make me appreciate each language more by knowing the advantages and disadvantages.

You can find the source code at https://github.com/yizanchen/puzzel.
