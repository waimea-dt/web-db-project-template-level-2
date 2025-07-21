# NCEA Level 2 Web and Database Project Instructions

| Standard             | Version | Level | Credits |
| -------------------- | ------- | ----- | ------- |
| [91892](as91892.pdf) | 1       | 2     | 4       |
| [91893](as91893.pdf) | 1       | 2     | 4       |

## Contents

- [Introduction](#introduction)
- [Assessment Conditions](#assessment-conditions)
- [Detailed Game Specification](#detailed-game-specification)
- [Achievement Criteria](#achievement-criteria)
- [What You Need to Hand In](#what-you-need-to-hand-in)


---

## Introduction

You are required to design and create a web application that satisfies a particular need or problem for a person or group of people. The need / problem should be a genuine and authentic one.

You will be assessed on how skilfully and effectively you design, create, and test your system over the course of a number of 'sprints'

*Note: If you cannot identify a need / problem, [this document](ideas.md) has some that might help you.*

---

## Timeline

| Weeks | Phase                                                                       |
| ----- | --------------------------------------------------------------------------- |
| 1     | Project idea clarification, development and research                        |
| 2-3   | **Sprint 1**: Project design and working prototype, using DrawSQL and Figma |
| 4-6   | **Sprint 2**: Working MVP (minimum viable product), using Flask template    |
| 7-9   | **Sprint 3**: System refinement and completion                              |
| 10    | Final testing and evaluation                                                |

A 'sprint' is a set period of time during which specific work has to be completed and made ready for review. In this project, the work for each sprint has been defined for you in the table above.

During each sprint you will develop your ideas, create suitable outcomes, present these to your end-user(s) so they can try them out, collect feedback / test data, and improve your outcomes to fix any issues.


---

## Assessment Conditions

This is an 'open book' task. You may look at previous projects that you have worked on, and you may use any notes provided (e.g. the language reference documents).

### Starter Template

A project template with a minimal Flask application is provided for you to base your project off - this has little to no functionality, but will speed up the setup of your system.

### Plagiarism and the Use of AI / LLMs

This is an individual assessment activity: Beyond the starter template, all the work that you produce must be your own. Do not copy blocks of code from other people, nor use an AI code-generation tool to write blocks of code for you.

*You will be asked to explain the workings of any/all of your code to assess whether you wrote and understand the code. Also, your git commits will be examined to check how your code progresses.*


---

## Achievement Criteria for the Database

| Level          | Criteria                                                     |
| -------------- | ------------------------------------------------------------ |
| **Achieve**    | Use advanced techniques to develop a database.               |
| **Merit**      | Use advanced techniques to develop an **informed** database. |
| **Excellence** | Use advanced techniques to develop an **refined** database.  |

*To help you keep track of how successfully you are meeting the criteria, use the [Checklist document](checklist.md)*

### Achieve Criteria

Use advanced techniques to develop a database means that, taking into account the problem / need and the end users:

1. You need to design the structure of the database:
   - **Tables** - at least two that are linked by a relationship
   - **Data Types** - appropriate data types for each field
   - **Key Fields** - primary keys for each table, foreign keys for relationships
   - **Values** - auto-generation / default values as required

2. You should use appropriate tools and advanced techniques to organise and query the data:
   - **Linking data in related tables** using queries or keys
   - Writing **custom queries** to filter and/or sort data
   - Possibly using **logical, mathematical and/or wildcard operators**

3. You should use appropriate tools and advanced techniques to present the data:
   - Customising **presentation** of the data
   - Using **custom forms** to add user input to the database
   - Setting **validation rules** for data entry

4. You must apply appropriate data integrity and testing procedures:
   - Show that any **presented data is correct** (e.g. matches database values / calculations)
   - Show that any input user data **updates the database as expected**

5. You need to explain relevant implications:
   - Identify the **implications most relevant** to your project
   - Explain **what the implications mean** and **why each is relevant** to your project
   - Explain **how each implication will impact your project** (considerations / choices / designs)

*Note: You must satisfy **all** of the criteria above to pass*

### Merit Criteria

Use advanced programming techniques to develop an informed computer program means **all the criteria for Achieved**, plus:

1. Your program must be well-documented with:
   - appropriate and well-considered **variable / function names**
   - comments that **describe code function and behaviour**

2. Your code should follow **common conventions** for the Kotlin language (e.g. indentation, use of upper/lowercase, comment blocks, etc.)

3. You must test and debug your program **effectively** to ensure that as well as valid data, it also works with relevant **boundary** (edge/limit) data values (this needs to be documented)

### Excellence Criteria

Use advanced programming techniques to develop a refined computer program means **all of the criteria for Merit**, plus:

1. Your program should be **well-structured** and a **logical** response to the task

2. You must make your program **flexible**, including:
   - Using **constants** and **derived values** in place of literal values
   - Using conditions, branching, loops and functions **effectively**

3. You must make your program **robust**, correctly handling **invalid** (unexpected) data values

4. You need to **comprehensively test** and **debug** your program to ensure that as well as valid / boundary data, it also copes wit **invalid** data (this needs to be documented)


---

## What You Need to Hand In

At the end of this project you will need to submit the following:

1. **The URL of your GitHub repo** which should contain:
   - **Project Description** - in the [README](../README.md) document
   - **System Source Code** - in the [app](../app) folder
   - **Supporting Documentation** - in the [docs](../docs/) folder

2. **A zipped copy** of the repo above

3. **The URL of your live site** - your site must be hosted externally and live

