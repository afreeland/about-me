---
title: "Work"
date: 2018-09-26T22:43:51-04:00
draft: true
---

I work as a software engineer for **Memorial Health System** in *Marietta, Ohio*.  I am currently on a **Decision Support** team that specializes in bringing business intelligence, analytics and integration into our healthcare system.

Our primary focus is an in-house application called **DataSuite**.  This cross-platform desktop app built in `Electron` allows us to distribute analytics and insight across various levels of the organization consistently, securely and reliably.  Since access to data is so important in healthcare, this application is also available natively through IOS and Android devices via `React-Native`. From daily information such as appointments and alerting for physicians, all the way through C-suite trends and analysis. 


Maintaining parity across applications was very important to development and to our team.  We found that utilizing `GraphQL` made building APIs friendly and highly reusable.  This allowed us to bring disparate systems together from PostgreSQL, Redis, SQL, External APIs and even LDAP for Active Directory.  Not only did this help give us a consistenty across apps, with GraphiQL, it gave us a great discovery and query tool for our team.

Healthcare often has a lot of moving pieces that can really benefit from a micro-service mentality with a large emphasis placed on high-availability.  Pair these needs with a small development team and it can certainly turn into an environment nightmare.  To help alleviate these burdens we have implemented a *bare metal* installation of `Kubernetes` that makes devops a beautiful experience.  Applications can be built directly in `Docker` containers and easily deployed with confidence.

Being on an team focused around analytics and having so many containerized applications, capturing logs and user traffic has been a large priority.  We have implemented `ElasticSearch` which allows us to *slice and dice* our data to better understand our application usage, as well as understand issues across our entire offering.

Our team has been given a lot of freedom, flexibility and responsibility for the direction and continued growth of our application.  I am often leading the way in pushing new ideas and concepts from initial design, to storyboards and all the way through architecture, technology and implementation. 