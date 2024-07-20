---
layout: page
title: SQL/SSRS
description: Database Work
img: 
importance: 1
category: Work
related_publications: false
---
### SQL
During my work for Sandia I was given the responsibility of managing reports and SQL databases. This involved generating long SQL queries from various types of databases in the backend. These queries were then used in SSRS to generate custom reports for both internal and external HR usage.
During the initial implementation of the simpler SQL queries I worked as part of a small team to create them. The responsibility eventually shifted to relying on a few individuals rather than a team.
Our queries often involved joining several datasets together from excel type sheets,lists, and more.Allowing us to maintain data that automatically refreshed and was easy to work with.Due to the origin of the data and limitations given to the nature of our queries we could not build functions but often needed to do things like removing HTML tags. We manually developed a method to remove the specific HTML tags and rearrange field data listed as "last,first" to "first last". I learned to implement string split with uncommon characters as to eliminate future formatting problems. I eventually learned to implement our queries as stored procedures for reproducibility.
Due to the nature of the work I am unable to provide images of my work.

### SSRS
I've also had to learn to redesign SSRS and Power BI reports to use updated datasets that automatically refresh and generate new pages for new data as it appears. A specific example is in an updated SSRS report the I was tasked with creating a filter to track previous and current employees from a list based query. I created a type of cascading parameter set that would check based off user input for current,past,or all employees then allow the next parameters such as name to change accordingly to only show those that were possible with the previous filter. This allowed for seemless updates and user interactivity unlike our previous one.


