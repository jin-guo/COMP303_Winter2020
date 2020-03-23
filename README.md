# COMP303 Winter2020

## General Information
|   |  |
| :---: | ------------- |
| Instructor    | [Jin Guo](http://jguo-web.com/index.html)  |
| Class Time    | WF 2:35 pm - 3:55 pm (No class recordings) | 
| Location      | Strathcona Anatomy & Dentistry M-1  |
| Office Hour   | Instructor: Wednesday 9am-10am, MC328 <br> TA: [See below](#TA-Office-and-Lab-Hours) |
| Discussion Forum | [Piazza link](http://piazza.com/mcgill.ca/winter2020/comp303) |


## Description
This course provides an in-depth introduction to the discipline of software design for building realistic and high-quality software applications. It will focus on object-oriented programming techniques, and cover topics related to managing software complexity and verifying that they work as expected. It will use Java for all the code examples and assignments. However, the considerations during the design process apply in all languages for practical software development.

## Expected Outcome

After completing this course successful students should be able to:

- Properly explain and apply general Design Principles (separation of concerns, encapsulation, substitutability, interface segregation, etc.) and important Design patterns;
- Properly explain and apply design techniques such as UML Diagrams and Design by Contract;
- Effective use programming language mechanisms such as exception handling and reflection;
- Analyze and evaluate the quality of design solutions; correctly identify design smells and apply appropriate refactoring to eliminate them;
- Gain experience on software development tools such as modern IDEs, automatic documentation and testing tools, and version control system.

## Reference Material
- **Required Textbook**: 
  - [Introduction to Software Design with Java (referred to as SD in the schedule)](https://link.springer.com/book/10.1007/978-3-030-24094-3). The electronic version of this book is **free** for McGill users with library access. For those who optionally want a print version, the [Paragraph Bookstore](http://paragraphbooks.com/) will stock a limited number of copies;
  - [Companion Website](https://github.com/prmr/DesignBook) for source code, exercises, and solutions.
- **Other Recommended References:** 
  - [The Pragmatic Programmer (referred to as PP)](https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/), by David Thomas, Andrew Hunt, Addison-Wesley Professional;
  - [Effective Java (referred to as EJ)](https://www.oreilly.com/library/view/effective-java-3rd/9780134686097/), by Joshua Bloch, Addison-Wesley Professional.

- **Sample Projects:** 
  - [Inclass demos](https://github.com/jin-guo/COMP303_CodeDemos);
  - [Minesweeper](https://github.com/prmr/Minesweeper);
  - [Solitaire](https://github.com/prmr/Solitaire).

- **Diagramming Tool (and Sample Project):** 
  - [JetUML](http://cs.mcgill.ca/~martin/jetuml/)

## Prerequisites
COMP 206 and COMP 250. Please also perform the [self assessment](https://github.com/prmr/COMP303/blob/master/Assessment.md) within the first week of the class to determine if you are ready to take this course.

## Teaching Assistant Team

| Name | Email Address |
| :---: | :---: |
| Deeksha Arya | deeksha.arya@mail.mcgill.ca |
| Meng Cao | meng.cao@mail.mcgill.ca |
| Fuyuan Lyu | fuyuan.lyu@mail.mcgill.ca |
| Srinivas Venkattaramanujam | srinivas.venkattaramanujam@mail.mcgill.ca |
| Alison Li | alison.li2@mail.mcgill.ca |
| Aaron Sossin | aaron.sossin@mail.mcgill.ca |
| Eric Liu |	eric.liu2@mail.mcgill.ca |

## TA Office and Lab Hours
Location: TR 3120

| Time | TA |
| --- |---|
| Monday 10 am to 12 pm | Fuyuan | 
| Tuesday 10 am to 12 pm | Meng |
| Tuesday  12 pm to 2 pm | Aaron |
| Wednesday 10:30 amto 12:30 pm | Eric & Srinivas |
| Thursday 1 pm to 3 pm | Deeksha |
| Friday 8 am to 10 am | Alison |

## Assessment and Evaluation (Updated):

|  Assessment Method | When | Weight |
| :---: | :---: | :---: |
|  Participation | in class + online | 10% |
|  Lab tests | 3 sessions (Location TR 3120 or Online. Schedule can be viewed [here](https://docs.google.com/spreadsheets/d/1dvCugSYc8ivpxAiW5GoW0hCQNfIS8NQWlB_C8SYFWEw/edit?usp=sharing)) | 20% |
|  Midterm | 6:15 pm - 8: 15 pm, Feb 27th (LEA 132)  | 30% |
|  Final | Takehome. Release on Apr 27th | 40% |


 
- It’s important to attend the lectures in order to gain the best learning experience – it cannot be replaced by watching the videos afterward. There will be random participation/attendance collected during this semester;
- Our TA will try their best to support your learning. But considering this is a big class – many of you will have similar questions or concerns and many of you have will answers to other people’s questions, we encourage you to discuss your questions about the lectures and exercises online;
- The participation during the class and the online discussion will count 10% of your final grades; The top 20% contributors for the online discussions will gain bonus credits based on the amount of contribution, up to 3%;
- Every module of the lecture will come with [exercises provided by the textbook](https://github.com/prmr/DesignBook). Those are for your practice and will not be graded. Instead, your practical skills will be evaluated through 4 lab tests that count 20% of your final grades. You are responsible to book the slot of lab test for each session in advance with the TAs.
- Missing any of the lab test sessions, midterm or final exam will result zero grade for that assessment.
- Any form of plagiarism, cheating is strictly banned during midterm or final exam. Integrity is crucial to this course and your future career. Any violation against academic integrity will be taken very seriously. For more information, please refer [here](https://www.mcgill.ca/students/srr/academicrights/integrity).

## Schedule (Tentative)
*Subject to minor adjustments*

| Lecture | Date | Content | Reading | Exercise |
| :---: |:---:| :---: | :---: | :---: |
|1	|  8 Jan  | Introduction | SD: Chapter 1| [Exercise 0](https://github.com/jin-guo/COMP303_Winter2020/blob/master/M0-Exercise.md) <br>[Exercise in SD: Chapter 1](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter1.md) |
|2	|  10 Jan | Encapsulation - 1 | SD: Chapter 2 | [Exercise 1-5 in SD: Chapter 2](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter2.md)|
|3	|  15 Jan | Encapsulation - 2 | EJ: Item 15-17  | [Exercise 6-9 in SD: Chapter 2 <br>(omit the exercise related to Design by Contract and Assertion which will be introduced later in the course)](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter2.md) |
|4	|  17 Jan | Types and Polymorphism - 1 | SD: Chapter 3 |  [Exercise 1-2 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) |
|5	|  22 Jan | Types and Polymorphism - 2 | EJ: Item 14 |  [Exercise 3-6 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) |
|6	|  24 Jan | Types and Polymorphism - 3 | |  [Exercise 7-12 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) |
|7	|  29 Jan | Object State - 1 | SD: Chapter 3, EJ: Item 10, 11 | [Exercise 1-5 in SD: Chapter 4](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter4.md)|
|8	|  31 Jan | Object State - 2 | EJ: Item 1, 3 | [Exercise 6-11 in SD: Chapter 4](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter4.md)|
|9	|  05 Feb | Design for Robustness - 1 | PP: Topic 23, 24, 25| |
|10  |  07 Feb | Design for Robustness - 2 | EJ: Item 69 - 72 | |
|11	|  12 Feb | Unit Testing - 1 (by TAs)|  SD: Chapter 5  | [Exercise 1-3 in SD: Chapter 5](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter5.md) |
|12	|  14 Feb | Unit Testing - 2 (by TAs) | | [Exercise 4-11 in SD: Chapter 5](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter5.md) |
|13	|  19 Feb | Composition - 1 | SD: Chapter 6 | [Exercise 1-5 in SD: Chapter 6](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter6.md) |
|14	|  21 Feb | Composition - 2| | |
|15	|  26 Feb | Content Review (by TAs) | | |
|M|  27 Feb | Midterm (no class on 28th) | | |
|16	|  11 Mar | Composition - 3 | SD: Chapter 6 | [Exercise 6-19 in SD: Chapter 6](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter6.md) |
|17	|  13 Mar | Univerity Close | | |
|18	|  18 Mar | Univerity Close | | |
|19 |  20 Mar | Univerity Close | | |
|20 |  25 Mar | Univerity Close | | |
|21 |  27 Mar | Univerity Close | | |
|22 |  1 Apr | Inheritance - 1 | | |
|23 |  3 Apr | Inheritance - 2 | | |
|24 |  8 Apr | Inversion of Control - 1 | | |
|25 |  14 Apr | Inversion of Control - 2 | | |

## Survey links
[Class 1](https://forms.gle/EjAER6EqFZ1iH6Zq8)

[Jan 24 - Strategy Pattern](https://forms.gle/kcu86qGR1RiqvTdZ8)

[Jan 29 - Object Equality](https://forms.gle/DwSGkPwSeb3YpXnA8)

[Jan 31 - Flyweight and Singleton](https://forms.gle/SvhT28ktHACYs8hS9)

[Feb 19 - Composite](https://forms.gle/HYoDKD8YoZFPx6mr8)

[Feb 21 - Prototype](https://forms.gle/MG1wgD6ubG4TTmuX8)

