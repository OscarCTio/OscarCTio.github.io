---
layout: essay
type: essay
title: "Practacing Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2026-04-29
published: True
labels:
  - Software Engineering
  - Design Patterns
  - Web Development
---

<img width="600px" class="rounded float-start pe-4" src="../img/design-patterns-logo.png">

## Recognizing Patterns in Code

When building software, it quickly becomes clear that many problems are not entirely new. The same types of challenges show up again and again, just in slightly different forms. Design patterns are the general solutions developers use to handle these recurring problems. They are not specific pieces of code, but rather structured approaches that guide how systems should be organized. Instead of reinventing a solution each time, patterns provide a reliable starting point that leads to cleaner and more maintainable code.

## Why They Matter

One of the biggest advantages of design patterns is that they create a shared language among developers. Saying something follows a certain pattern immediately communicates how it is structured and how different parts interact. Patterns also help avoid messy code by encouraging separation of concerns and modular design. This makes projects easier to debug, extend, and collaborate on, especially as they grow in size.

## Patterns in My Project

In my final project, a web app that tracks real-time campus busyness, several design patterns naturally appeared. The separation between database logic and the user interface reflects ideas similar to the Model-View-Controller approach, keeping data handling and presentation distinct. There is also a service-like structure where centralized functions handle fetching and processing data instead of spreading that logic across components. Additionally, the UI updates automatically when new data is submitted, which follows the core idea of the observer pattern where parts of the system react to changes in state.

## AI Usage

AI was used while writing this essay.
ChatGPT was asked to help condense and refine explanations while keeping the ideas clear and straightforward.
