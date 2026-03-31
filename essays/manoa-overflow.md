---
layout: essay
type: essay
title: "Manoa Overflow"
date: 2026-03-30
labels:
  - Software Engineering
  - Nextjs
---

By Oscar Tio, Sebastian Wheelehan, Nathan Wong

## Overview

**Problem:**  
Students often struggle with very specific assignment issues, especially in technical courses. Existing platforms such as Discord or general forums can often be unstructured, difficult to search, and not focused on course-specific problems. As a result, it is hard to find others experiencing the same issue or to locate relevant solutions efficiently.

**Solution:**  
Manoa Overflow is a forum-style web application designed specifically for University of Hawaiʻi at Mānoa students. It allows users to organize problems by course and assignment, making it easier to find, discuss, and solve specific issues. Students can post problems, browse existing discussions, and collaborate with others facing similar challenges.

## Approach

To use Manoa Overflow, users first create an account and log in.

1. **Select or create a course (subject)**  
   Users can choose from existing courses (e.g., ICS 314, ECE 361) or create new ones if needed.

2. **Browse or create problems**  
   Within each course, users can:
   - View existing problems
   - Create new problem posts tied to a specific assignment or topic

3. **Interact with posts**  
   Users can:
   - Comment with hints or solutions
   - Upvote helpful responses
   - Mark a problem as solved

4. **Collaborate with others**  
   Users can identify others working on the same problem and potentially form study groups or discussions.

## Mockup Page Ideas

- **Landing Page**
  - List of available courses
  - Recently posted or trending problems

- **Course Page**
  - Displays all problems related to a specific course
  - Filtering options (assignment, solved/unsolved, tags)

- **Problem Page**
  - Problem description
  - Comment thread with solutions and discussions
  - Upvote system
  - “Mark as solved” feature

- **Create Problem Page**
  - Form to submit a new problem
  - Fields for course, assignment, title, and description

- **User Profile Page**
  - Displays user’s posts and contributions
  - Optional reputation or activity tracking

## Use Case Ideas

- A student encounters an error while working on a Next.js assignment and posts the issue under ICS 314.
- Another student who experienced the same issue finds the post and provides a solution.
- Additional students join the discussion and contribute alternative approaches.
- The original poster marks the problem as solved.
- Future students can search for the same issue and reuse the solution.

## Beyond the Basics

- **Reputation System**
  - Users gain points for helpful contributions and solutions

- **Tagging System**
  - Problems can be tagged with technologies or topics (e.g., Next.js, Prisma, React)

- **Search and Filtering**
  - Advanced search to quickly find relevant problems

- **Study Group Matching**
  - Identify users currently working on the same problem

- **Real-time Updates**
  - Live comments or notifications for active discussions

- **AI-assisted Suggestions (optional)**
  - Provide hints or suggest similar problems without giving full solutions
