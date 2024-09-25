---
layout: essay
type: essay
title: "Being Held to a Standard"
# All dates must be YYYY-MM-DD format!
date: 2024-09-25
published: true
labels:
  - Coding Standards
  - ESLint
  - Typescript
---

<img width="300px" class="rounded float-start pe-4" src="../img/standards.jpg">

## Standards?

As defined by the Oxford Dictionary, standards are “a level of quality or attainment”. Like anything in life, there are standards to which must be met to be deemed reasonable or acceptable. Food in the United States is regulated to FDA standards, water quality is held to EPA standards, cars must meet the safety inspections standards to be road worthy. Similarly, coding has standards that must be met as well. Not only does coding standards lead to functioning, working code, but contains readability, proper type assignments, proper spacing, proper use of functions and variables, etc. Especially when multiple collaborators are working on a project, or projects happen to be open source, coding standards are even more important for success. For our ICS 314 class, we happen to be using ESLint for our coding standards. 

## Red Squiggly Lines

After installing ESLint and all the attribute files, a bunch of red squiggly lines appeared all over my perfectly working typescript code. I was irritated at first, especially since I would get ESLint errors from an extra space on a line of code. However, after addressing all the errors, the code begins to look a lot nicer. It becomes easy to read. Coding standards like ESLint begin to make sense as all code being held to these standards look the same. For loops, if statements, and comparison operators receive proper spacing. Brackets from functions are spaced appropriately. Ultimately, it looks really nice. It may seem like a miniscule detail, but readable code is essential in projects with multiple developers. It makes debugging easier, understanding other people's code easier, and helping other programmers with their code is less of a headache. After using ESLint for multiple typescript coding assignments, I began to appreciate the squiggly read lines. 

## Enhancing Coding Through ESLint

Another reason for having coding standards is functionality of the code. ESLint errors point out errors that would have already been pointed out by the IDE. For example, syntax, non-defined types of variables, data structures being utilized incorrectly, etc. However, it is also very picky with the variable types being declared. For example, I used “let” to declare a variable in a function, which works completely fine. However, since the variable never gets reassigned in this function, ESLint gave an error, telling me to use “const” instead. Small things like that make the code more secure, even though the code is already functioning. This also makes me more efficient in coding and helps me to further understand typescript and improve my code. 

## Debugging

A main feature that ESLint coding standards have is the declaration of errors in code. IDEs like VSCode already point out syntactical errors or potential errors in code like undeclared data types, or misuse of the language. ESLint takes it a step further and ensures that the I, the coder, writes the code as efficiently and correctly as possible to avoid potential bugs in the future. Similar to the point I made previously, it is picky. Additionally, if code happens to be written incorrectly, it will state what is wrong, and sometimes state a solution depending on the simplicity. Features like this make coding more enjoyable as we all make mistakes as programmers. ESLint keeps the quality of code consistent, which is crucial in the work environment. 

## Conclusion

Despite the constant nagging of ESLint, coding standards play an essential role in ensuring code is not only functional but also readable, maintainable, and secure. While the initial frustrations of seeing errors on working code are common, the long-term benefits become apparent as the code becomes more organized and easier to understand. These standards make collaboration smoother, prevent potential bugs, and create good coding habits that ultimately lead to more efficient development. ESLint enhances the quality of the code and ensures that developers produce work that is consistent and reliable, a skill that is crucial both in academics and the professional world.




