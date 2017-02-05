---
title: Contemplating the Backlog
date: 2017-02-05 22:03:35
categories: []
tags: []
published: false
---

On client site we were recently talking about a potential backlog of user stories for a project on the near horizon. We wanted to create a exemplary backlog with meaningful stories that would not only allow the team succeed in the project, but also show the less technical side of the origanisation that they needn't deliver _all functionality_ in one large push. So the question of what story to tackle first came up. The first answer _"just do the most important thing"_ just didn't feel satisfactory enough.

The team backlog is a linear representation of the pieces of work that need to be done. Assuming the backlog is looked after, the next item that should be worked on is at the top. Remaining future work is further down the line. As such the backlog is a fairly simple concept:  a queue, sorted by "importance" in descending order.

But "importance" is hardly a straight forward concept.The question then becomes: given a set of user stories, how do we "sort" them into a backlog? To explore how we can sort them, we need to take a closer look at the user stories. It's important to understand that a  userstory is multi-dimensional:

* It has value (real or perceived) to customer, which we will harvest when the story is completed
* It carries risk to the business, the customer, and the development team itself
* It unlocks knowledge, which might impact further stories.

As such, assuming that we can "just" sort our stories by monetary value is a simplistic and leaves room for improvement.



### Reward driven backlog

Sorting user stories by their real or perceived value is a good initial strategy. The idea behind is that we intend to recouperate our costs as fast as possible. The moment we deliver a story that adds significant benefit to our customers, we become a valued partner. In environemnts that are driven by reducing costs, delivering some piece of functionality that reduces the costs or increases the value...

...

### Risk driven backlog

More often than not reward is tied to risk. Adding a feature that might beneft 80% of our user base also means that we run the risk of disgruntling 80% of users. Think of a Todo application, where we decide to add a smart sorting algorithm that intelligently rearranges the todos by priority and due date. If it works, every user will get a pretty smart todo list. If we introduce a flaw, we are damaging the core functionality of our app _for every user_.

So a user story "sorting" strategy might be to begin work on stories that have lower overall impact. Those stories are a safe place to experiment and get a grips with the domain that we are working in.

…. …

### Knowledge driven backlog

When you step back from your user stories and look at all of them at once, you might notice that some of them are interconnected. While some user stories might not be of high value to the user, they very well might unlock knowledge to the team. Often, we can delay decision by doing other stories that greater inform us about the domain.

So a sorting strategy can be to bring forward stories that can teach us something for later stories. Sometimes these are called "spikes". The idea behind "spikes" is that the sole purpose of doing them is to gain a new insight for later stories. I prefer the term "experiments", as an experiment embodies the notion that we may figure out that something is not possible.
