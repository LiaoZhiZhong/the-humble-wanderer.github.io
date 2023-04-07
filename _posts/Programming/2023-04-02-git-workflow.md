---
title: "Git Workflow"
categories:
  - Programming
---

Version control is a skill that every software developer needs to know yet it
isn't taught well if at all.

So what's the point of version control?
- It allows you to keep track of your changes.
- It allows you to revert to a previous version of your code.
- It allows you to collaborate with other developers.
  - Perhaps this is the opaque part of version control - how does it help 
    collaboration?

Let's start with the use case example.

You work for XYZ Pty Ltd which is an e-commerce company. You're in a team of 
4 developers and each of you are working on a separate feature. At the end of the
day, you'll all have to merge your feature into the main codebase.

So, if person A merges first, what happens to the features of person B, C, and D?
How do they update their code to reflect the changes made by person A? What is
the "main" codebase now?

The answer is [version control](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).
