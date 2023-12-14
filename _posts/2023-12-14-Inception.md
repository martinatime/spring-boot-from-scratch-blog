---
title: "Inception and GitHub Pages"
---
## This blog's concept
So the concept for this blog was that I wanted to build a Spring Boot application from scratch and attempt to follow the project and all of the hurdles that I came across. I have built many Spring Boot applications for work and on my own time but I would usually come across a novel, for me, issue that I would spend a bunch of time researching and finding a solution to but once it was solved it would be lost to time as I would have another issue to deal with. This blog allows me to not only slow-down and work through each issue without having a time constraint but also compile and share the knowledge that I gained even if it is just for my future self. I have wanted to do this for a while and now I have some time to work on it.

## The coding project
The application that I want to tackle is related to podcast management. Here are the initial features to this application that I want to implement:
- User management including admin access.
- Import an [OPML](http://opml.org/) file and be able to select one to many podcast feeds from that file to store against a specific user.
- Export an OPML file with all of the podcast feeds against a user's account.
- Scheduled job(s) that check podcast feeds for updates

Then my strech goal features are:
- Create proxy podcast feeds that wrap existing podcast feeds (passthrough or cached)
  - Ability to filter individual podcasts for either inclusion or exclusion based on attributes and/or regex matching (this item will be split into more detailed requests)
  - Ability to merge multiple feeds into one therefore creating a playlist like functionality
- Provide lightweight response for clients requesting information on a feed (instead of providing the entire feed XML just a response on updated or not)
- Provide push notifications if the client supports it

## DevOps
I plan on having at least one GitHub repo for the Spring Boot project and utilizing [GitHub Actions](https://github.com/features/actions) for the building, testing, packaging, and deployment of the application. I haven't decided where the application will reside yet but [Docker Hub](https://hub.docker.com/) is the first consideration. I'll probably expand on other DevOps considerations in a future blog post.

## GitHub Pages and this blog
You are already reading this blog so you probably realize it is done using GitHub Pages. I am also using [Markdown](https://www.markdownguide.org/) for formatting and this [reference](https://www.markdownguide.org/cheat-sheet/). I used [this course](https://github.com/skills/github-pages) to learn how to use GitHub Pages for a blog.

## Project Management
I'm going to give [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects) a spin in order to track this effort. So far I'm a one man army for this but who knows what the future holds. [Here](https://github.com/users/martinatime/projects/1/views/1) is the project's Kanban board.
