# Lab5-ece444

## Added tests to my projects
https://github.com/ECE444-2023Fall/Blue-Surf/blob/d0a656516c503a2abd1b315f120642aff5260b31/src/tests/FilterField.test.tsx#L1-L21 
https://github.com/ECE444-2023Fall/Blue-Surf/blob/d0a656516c503a2abd1b315f120642aff5260b31/src/tests/PostCard.test.tsx#L1-L29C1 
https://github.com/ECE444-2023Fall/Blue-Surf/blob/d0a656516c503a2abd1b315f120642aff5260b31/src/tests/SortBy.test.tsx#L1-L19 

## Pros and Cons of Test-Driven Development (TDD)

Test-Driven Development (TDD) is a software development methodology that focuses on writing tests before writing the actual code. This practice has its own set of advantages and disadvantages, and in this section, we will explore the pros and cons of TDD.

### PROS
1. Improved Code Quality
TDD encourages developers to think about the expected behavior of their code before writing it. This leads to more precise and reliable code since developers have to define the requirements and specifications in the form of test cases. As a result, TDD often results in fewer bugs and better code quality.

2. Faster Debugging
By writing tests before implementing the code, TDD helps in identifying and addressing issues early in the development process. When a test fails, it's often easier to pinpoint the problem because you know exactly which part of the code is causing the failure. This speeds up the debugging process and reduces the time and effort required to fix issues.

3. Better Documentation
Tests serve as documentation for your code. They provide a clear and executable description of how a piece of code is intended to work. This makes it easier for other developers to understand and work with your code, especially when they need to make changes or additions.

### CONS
1. Initial Learning Curve
Adopting TDD can be challenging, especially for developers who are new to the methodology. Writing tests before writing code requires a different mindset and discipline. It may take some time for the team to become proficient in TDD.

2. Time-Consuming
TDD can initially slow down the development process because writing tests takes time. However, in the long run, TDD can lead to faster development by reducing the time spent on debugging and maintenance.

3. Test Maintenance
Maintaining a suite of tests can become cumbersome as the project grows. If the requirements change or the code is refactored, tests may need to be updated. Failing to maintain the test suite can lead to false positives or negatives, which can be detrimental to the development process.