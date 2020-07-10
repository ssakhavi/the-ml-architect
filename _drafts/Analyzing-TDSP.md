---
toc: false
layout: post
description: Analyzing the Team Data Sciece Process utilized by microsoft and how some Machine Learning tools can help implement.
categories: [Agile, Project Management, Tools, Team, Software Development]
title: "Analyzing the Team Data Science Process (TDSP) - Part 1"
comments: true
---

In this series of post, I will be focusing on analyzing the the TDSP method proposed by Microsoft. I remember being introduced to it via the MLOps Resources repository but didn't have the time to read it. Now that it's popped up again in my emails, I decided to go for it and understand what it is. This is part 1 of the series.

I'm going start this series blindly; I won't read the whole thing and then come write a review. Rather, I will read and analyze as I go. This will help we correct myself as I go along. Also, by reading and analyzing, I'll be hypothesizing and speculating what directions TDSP will take or should which wukk make me articulate my thinking process as well.

You can find the blog posts regarding the method in [this link](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/overview).

## Definition

> The Team Data Science Process (TDSP) is an agile, iterative data science methodology to deliver predictive analytics solutions and intelligent applications efficiently.

Well, maybe we need to open up the definition a little better and see whether in the future parts it actually addresses what it claims.

It says it's **Agile**, that means that it should be following the agile values and principals. Agile initially was a _guideline_ proposed by a group of programmers and computer scientist identifying how to conduct a software product ([Agile Manifesto](https://agilemanifesto.org/)). Now, any framework which addresses the requirements of the manifesto, basically is agile. Unfortunately, like many things, when a concept becomes popularized, people who want to milk money from it change what it represents and twist it in a way which only the name of it is left. There are a few talks and booka which address this matter. Eventually, what has happened is that a lot of people say a project management framwework is _agile_ or have knowledge about a framework, but don't realize or have the knowledge that it my not work for software development. I refer you to the footnote for a few videos to watch [^1]. Let's see if TDSP lives up to it's definition.

It says it's **Iterative**. When it come to iteration, usually what is intended is continous integration and continous delivery (CI/CD). This means, results and development of the software is seen more frequently. I have come to understand that when it comes to machine learning, the concept is a bit more difficult to implement in comparison to other software development. It has to be clarified which part of the process of the Machine Learning Lifecycle is going to be iterative. It's possible that iteration might refer to deploying a model, viewing the performance, and re-training the model based on the performance.

Now condidering that the methodology is specified, these two are going to be used for *"predictive analytics solutions and intelligent applications"*.

## Components

The article specifies that the TDSP has four main components:

* Data Science Lifecycle
* Standardized Project Structure
* Infrastrcture and Resources
* Tools and Utilities

Let's jump and see what each of them actually is.

### Data Science Lifecycle

I think the visual representation really shows what the whole thing is about. We have 4 main elements: **Business Understanding**, **Data Aquisition and Understanding**, **Modeling** and **Deployment**.

[^1]: Some videos that are related to the topic of refocusing what agile means:

* [Uncle Bob on Clean Agile the Book: Taking it Back to the Basics](https://www.youtube.com/watch?v=T4Td2vgrgsM)
* [Taking Back "Software Engineering" • Dave Farley](https://www.youtube.com/watch?v=_N_jIrEBOpw)
* [Robert C. Martin - The Land that Scrum Forgot](https://www.youtube.com/watch?v=hG4LH6P8Syk)
