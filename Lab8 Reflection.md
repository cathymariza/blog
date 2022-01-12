---
layout: post
title: Lab 8
date: 2021-10-27 22:38:11 -0500
categories: jekyll update
author: Catherine Mariza
---

I started lab 8 three weeks ago and it was easy initially, since most things were similar to lab 7. However, when I started creating more entities and adding new models and working with multiple tables, things bbecame quite complicated.

At first I started the lab and didn't make any commits or push until I was halfway through the steps and got stuck. I had done everything from Get started part up until the last step of `Creating a complex Data Model`, and I accidentally ran the command two consecutive times. I dropped the database twice and couln't undo the action, then Students Page disappeared entirely. I tried to search up possible solutions it but I didn't get anything helpfu, and then I restarted everything from scratch. I recloned my repo, and since I hadn't made any commits, I lost everything and restarted, but this time I made commits and pushed things after evry step.

I got stuck again at the same point, but when I went to office hours, I got a solution and finished the lab.

I spent long hours learning and working on this lab but I absolutely enjoyed seeing each piece come togeether and seeing how complex data models work, as opposed to having a single data model. In particular, I loved learning how one can update the Database through Migrations, by running the simply running this command  
`dotnet ef database drop --force
dotnet ef migrations add InitialCreate
dotnet ef database update`

Even though I had some hiccups, it wa all worth it and I'm happy for evrything I learnt and this really strenthened my knowledge and helped in the final project.



You can [click here](https://github.com/cathymariza/csci340lab8) to see my web app.
