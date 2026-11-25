<p align="center">
  <img src="media/image1.png" alt="Stacked API, server, and database layers inside curly braces" title="Title image" width="600">
</p>

# Process: Becoming a Backend Developer

## Table of Contents

- [Purpose](#purpose)
- [Building your technical foundation](#building-your-technical-foundation)
  - [Learning a backend language](#learning-a-backend-language)
  - [Understanding databases and SQL](#understanding-databases-and-sql)
- [Developing server-side skills](#developing-server-side-skills)
  - [Designing and testing APIs](#designing-and-testing-apis)
  - [Using version control with Git](#using-version-control-with-git)
- [Gaining practical experience](#gaining-practical-experience)
  - [Building portfolio projects](#building-portfolio-projects)
  - [Joining collaborative work](#joining-collaborative-work)
- [Presenting your skills to employers](#presenting-your-skills-to-employers)
  - [Polishing your resume and LinkedIn profile](#polishing-your-resume-and-linkedin-profile)
  - [Preparing for technical interviews](#preparing-for-technical-interviews)
- [References](#references)

## Purpose

As a future Husky student, you likely seek guidance on finding a job, this document can serve as a guide for you on learning effective strategies to acquire a job. This work presents best practices when seeking a position in backend development.

## Building your technical foundation

This section covers choosing a language to specialize in and database basics.

### Learning a backend language

Developers tend to cluster into small groups of widely used languages. In a 2026 Stack Overflow survey, 62% of developers used JavaScript, 58% used Python, 43z% used TypeScript, and 27.6% used Java. Languages with such substantial use come with large communities, so you will find more libraries, examples, and answers to questions.

Choose one widely used backend language and build a deep understanding in that language before moving on to learn a second. Languages like Java and Python appear near the top

### Understanding databases and SQL

Most backend features read or write stored data, in the aforementioned survey, 73% of developers used a database, and SQL ranked second among languages. Learn SQL on a relational database such as PostgreSQL, start with creating small project database.

## Developing server-side skills

This section covers designing and testing the application programming interfaces (APIs) that your backend exposes.

### Designing and testing APIs

**Name actions with HTTP methods.** Use GET, POST, PUT, PATCH, and DELETE instead of verbs in the URL, such as `/getorder`. The methods keep URLs short and predictable.[^1]

**Nest URLs to match your data.** Write `/products/:productid/reviews` to show that reviews belong to a product. Nested URLs mirror data relationships, which speeds onboarding, reduces errors, and makes endpoints easier to discover.[^1]

**Parse JSON with a standard library.** Never split or search the text by hand. A parser keeps working when a new field, such as a middle name, appears, while string handling silently misreads the data.[^1]

**Write a test for every endpoint, and isolate each test run.** Tests document what the API does by example. Load known-good data before a run and remove it afterward, so one run cannot disturb the next.[^1]

> *TODO: figure*

### Using version control with Git

> *TODO*

## Gaining practical experience

This section covers starting a project and making a first contribution.

### Building portfolio projects

The Open Source Guides cover starting a project and finding users for it. A published project lets other people discover, interact with, and respond to your work. Publish a small project that solves a real-world problem to start.

### Joining collaborative work

You can also make a first contribution to an existing open-source project. For example, choose a project you already use, read its contributing guidelines, and potentially submit a change such as a bug fix or feature.

## Presenting your skills to employers

### Polishing your resume and LinkedIn profile

> *TODO*

### Preparing for technical interviews

> *TODO*

## References

[^1]: M. Heusser, "16 REST API design best practices and guidelines," *TechTarget*, 3 April 2025. [Online]. Available: https://www.techtarget.com/searchapparchitecture/tip/16-REST-API-design-best-practices-and-guidelines. [Accessed Nov. 25, 2026].