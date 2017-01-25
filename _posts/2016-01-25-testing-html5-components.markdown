---
title:  "Testing HTML5 components"
date:   2016-01-25 13:04:23
categories: []
tags: [html5, testing]
published: false
---

I've recently started working on a front end application and with my pair we decided to give HTML5 components a try.
While my pair had some experience in the JavaScript world, I had done little to no development in this area. My area of expertise
is in backend code. 
As such, I only knew about some of the pains in testing front end code that is tied to the DOM. 

We started writing a very small, simple component that would take a set of options and display them as a list of checkboxes. 
When something is clicked on the component, an event is bubbled up to the parent component to react to the new selection. 
Initially, we deferred testing it as we had no idea about options we had how to build it at all. 
Once we had something that behaved the way we wanted it, we turned back to how to test it. 

Our first instinct was to test mostly on the controller level (yes this is on a slightly dated version of Angular). 

        "How do get to the controller?"
        "Why do need to the controller?"
        "Well, I want to test the isExpanded variable changes when the checkboxClicked callback is called"
        
