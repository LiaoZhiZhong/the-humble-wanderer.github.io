---
title: "Practical Tips to Code Better in Python"
categories:
  - Programming
---

Be intentional about your changes - every line of code that is changed needs to have a purpose.

### Print statements - useful when debugging
Generally you don't want uncontrollable print statements in library code.

### Steps to take before submitting code

0. ALWAYS think about `backwards_compatibility` which is being able to be used
with the older version of the frontend, backend, and database (in the situation
   of database migrations).
1. Amend code but don’t change things too much.
2. remove spaces that don’t separate logic.
3. Remove packages that aren’t used - linters will warn you about this so don't worry.
5. Amend all function definitions for documentation.
6. Remove print statements.
7. lint the code.
8. Run the test locally using:
    1. `pytest -k test_name -o log_cli=True -s`
    2. right click the folder with tests and click `run pytests` or something 
       like that and it’ll run the entire suite of tests (for pyCharm).
9. Be consistent with the rest of the codebase but don't let this limit you
   from improving the codebase's quality.
   
   
### Speed up the code where you can

When in doubt about your code, try and look for the pythonic way of doing this. 
E.g., 
- Use a set to iterate when I can (for pairs of lists)
- Use list comprehensions
- Use numpy vectorisation and consequently, use pandas when you can