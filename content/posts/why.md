+++
title = 'Why startups should not use dotnet'
date = 2023-12-01T20:55:05-07:00
draft = true

+++


I have had the opportunity to see dotnet evolve from it's early days in the 2000s to the latest dotnet 8 core framework at the time of writing this. I haven't continiously worked solely with microsoft dotnet over the course of my career, rather, I have worked with multiple programming langugaes and technologies such as Java, Python, Scala, Node/Javascript. In addition, even though I was educated in OOD, I have explored functional paradigm over the course of my career. 
The exposure to multiple programming languages and programming paradigms has formed some of my opinions and points of view. 



My first encounter with dotnet was in early 2000s while helping develop a desktop appliction in C# for the secondary mortgage industry. Back then C# and dotnet was just another object orieted langauge competing with Java. The decision to choose C# dotnet was already made when I joined the company. The main reason for choosing dotnet was better support for runtime relfection and code generation. This feature was absolutely crucial for our product.  

My second encounter with dotnet was at the latter part of 2000s when developing a small web application using ASP.NET in C# while working for a consulting firm. Here the choice of ASP.NET/C# was made because my team was focused on Microsoft solutions and we could choose any programming language or technology as long as it was Microsoft. 

My most recent encounter with dotnet consisted of migrating and rewriting/redesigning a legacy monolith application written in dotnet framework to the latest dotnet core. While migrating/rewriting the application the design was modularized with a number of microservices and an API first approach was adopted. The API's were all gRPC. In addition to gRPC providing synchronous request-reply we used NATs for asynchronous messaging between microservices. In addition, the applications's persistenc layer was revamped and based on SQL Server.




https://www.reddit.com/r/dotnet/comments/16fu7o0/why_isnt_dotnet_core_popular_among_startups/


In this article, I have expressed my opinions around the choice of programming language and technology and I'll finish this with an 'it depends' discalimer: As with all things technology the final choice of programming languages and the technologies depends on your specific requirements and contraints. 