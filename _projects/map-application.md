---
title: "Avocet Map Application"
time-length: "September 2022 - December 2022"
layout: case-study
description: "This Maven based CAD software allows a user to create a printable 3D RPG Terrain. This application was produced in an agile group environment, over 3 sprints."
permalink: /avocetmapplication/

overview: "This Maven based CAD software allows a user to create a printable 3D RPG Terrain. This application was produced in an agile group environment, over 3 sprints. I was the Scrum Master, UX/UI Designer, and Git Expert and worked alongside 3 other Java developers. We were given an overview of what the client wanted, and from there, we created the application over the course of 14 weeks."

problem: "Our client had presented us with the issue that consumers wanted to create their own unique game boards to play with their groups. We needed to create a software that allows everyday people the opportunity to bring their imaginations to life through a printable game board. "

goals: "We needed to create a user-friendly software that was extensible and focused on letting users quickly and intuitively create their game boards. The software also needed to be compatible with 3D printing hardware."

results: "The Avocet Map Application is an extensible, robust, elegantly designed, software that has minimal technical debt. The client was very satisfied with the final product, and if another team wishes to continue the product in the future, we made sure that all the code is easily readable with strong variable and function names, and comments for any code that is not self-documenting."

img-thumbnail: "/assets/images/mapplication/thumbnail.jpg"
alt-thumbnail: "Display of the welcome and main screens of the Avocet Map Application."

img-overview: "/assets/images/mapplication/filal_main.jpg"
alt-overview: "Image of final main editor screen of the CAD map application."

img-problem: "/assets/images/mapplication/LoFi_Planning.jpg"
alt-problem: "Low fidelity drawing of map application. Meeting notes including an avocado icon with the quote 'chaos until it works'."

img-goals: "/assets/images/mapplication/goals.jpg"
alt-goals: "Elegance: Our Our code should be easy to read and continue, no matter who the programmer is. Extensibility: Our program should be extensible to meet user’s needs as they grow. Iteration: Each step needs to improve the last, and move us forward to the client’s goals. UX/UI Design: The end user needs to be able to easily achieve their goals without any guidance from the program."

img-results: "/assets/images/mapplication/printed_map.jpg"
alt-results: "Image of blue 3D printed bridge."
img-results-2: "/assets/images/mapplication/pointy_printed_map.jpg"
alt-results-2: "Image of green 3D printed pyramid with pointy tops."
---
### Designing

The beginning phases of the project involved a lot of brainstorming, not only for the product, but also for our team dynamics. This was the first time most of us had worked together so we took the time to find out what our individual strengths and weaknesses were. We assigned tasks based on availability and skills.

<img src="/assets/images/mapplication/final_welcome.jpg"
     alt="Image of welcome screen of the map application. It looks really good. Trust me." />

Beyond the team dynamics, most of our time during the first sprint was spent in the design and ideate phase of the project. We took the time to find out what industry standards for tool layouts were and compared our tool pallet to what the user would actually use.

<img src="/assets/images/mapplication/3D_Preview.png"
     alt="Image of the 3D preview." />

Our team used Git/Github to manage our code ([Check out the repo here!](https://github.com/AugustanaCSC305Fall22/AvocetRepo)), and we communicated through a private Discord Server. Each week we met as a group to build and design the larger parts of our project, then during the week we met as pairs, or coded individually to keep progress moving forward.

Our code was produced using the MVC method, and our focus was always on minimizing technical debt. We did that by carefully planning how each function and class was going to interact with each other, and coming up with simple code that solved complex issues.

### Developing

Technical debt was a big concern for our team. To minimize the time we spent coding, before we made sure we had a solid foundation for what features our client would need to achieve their goals. For us, this meant spending time thinking through each step of how we would implement any new features, how they would interact with the rest of the code, and what steps we would need to actually produce the code. This helped us avoid technical debt, and when we found ourselves with less elegant code, it didn't take much effort to refactor because of the time we spent focusing on good design.

During the second sprint, we spent one of our meeting days clearing up unnecessary dependencies between classes, and when we implemented different ways to set the heights of the map tiles, we ended up refactoring our method to take in input from different locations and made the tile class be in charge of setting its own height. That allowed for more extensibility in the Map Application, because now, instead of the tiles just increasing or decreasing by 1 each time, the user can choose to set the height, or if the client wanted a feature to change the height increment setting, we would only need to add a couple lines of code outside the setHeight() method, instead of editing the method itself..

<img src="/assets/images/mapplication/code_snippit.jpg"
     alt="Image of the most elegant code you can imagine." />

### Testing

Testing wasn't a huge part of this project because a lot of what we were doing mostly involved the UI. However, we used JUnit testing for our save/load features, and a few of our backend map editing methods, such as the crop grid and checking tile height limits.