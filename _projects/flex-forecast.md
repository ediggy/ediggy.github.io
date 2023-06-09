---
title: "Flex Forecast"
time-length: "Feburaury 2023 - May 2023"
layout: case-study
description: "This Android Application is a student-built weather app that allows the user to decide what is shown on their home screen. This application was produced in an agile group environment, over 3 sprints."
permalink: /flexforecast/

overview: "This Android Application is a student-built weather app that allows the user to decide what is shown on their home screen. This application was produced in an agile group environment, over 3 sprints. I was the Scrum Master, UX/UI Designer, and Git Expert and worked alongside 3 other Java developers. As a group we decided the project specs, and from there, we created the application over the course of 14 weeks."

problem: "Weather apps do not allow users to decide what they would like to see on their weather screen. We wanted to allow the user to have full control over the information that is displayed in their app."

goals: "We needed to create a user-friendly software that was extensible and focused on letting users have control over what information is displayed on their weather application."

results: "Flex Forecast is an awesome display of our team's abilities as developers. We have included an API that takes national weather data and displays it to our users. We are able to show different types of data, depending on what the user wants through the app's settings. The UI is welcoming, friendly, and easy to use."

img-thumbnail: "/assets/images/flexforecast/thumbnail.jpg"
alt-thumbnail: "Display of the menu and home screen of the flex forecast app."

img-overview: "/assets/images/flexforecast/final_main.jpg"
alt-overview: "Display of seven different final screens of the flex forecast final product."

img-problem: "/assets/images/flexforecast/LoFi_Planning_Whiteboard.jpg"
alt-problem: "Low fidelity drawing of map application. Meeting notes including an avocado icon with the quote 'chaos until it works'."

img-goals: "/assets/images/flexforecast/goals.png"
alt-goals: "Elegance: Our Our code should be easy to read and continue, no matter who the programmer is. Extensibility: Our program should be extensible to meet user’s needs as they grow. Iteration:Each step needs to improve the last, and move us closer to our goal for this project. UX/UI Design: The end user needs to be able to easily achieve their goals without any guidance from the program."

img-results: "/assets/images/flexforecast/final_demo.png"
alt-results: "Image of blue 3D printed bridge."

---
### Designing

Our first task was to decide what type of project we wanted to work on. One of our group members had experience working in meteorology, and they were also skilled at using APIs so we wanted to create a weather app. We all had experience using Java, so we chose an Android Studio project. We learned later that using Java with Android Studio was a foolish endeavor, but we made it work.

<img src="/assets/images/flexforecast/LoFi_Planning.png"
     alt="Image of welcome screen of the map application. It looks really good. Trust me." />

Our next task was to decide what fun “twist” our app would have to make it stand out from the hundreds of other weather apps. I dug into the reviews of all the popular (and some of the more obscure but still highly rated) weather apps. I created a short list of the top complaints, and aside from too many ads, the biggest issue was that people had a hard time finding the information they wanted.

<img src="/assets/images/flexforecast/research.png"
     alt="Image of the 3D preview." />

We weren’t going to have any ads on our app, so that left us with the idea to allow our users to customize their weather app experience. We decided to allow our users to drag, drop, add, and remove widgets from their app.

<img src="/assets/images/flexforecast/sticky_notes.png"
     alt="Image of the 3D preview." />

### Developing

We quickly learned that drag and drop functionality, while simple and elegant in theory, is a huge pain to build. Our team spent several weeks creating the interface for our drag and drop before we finally gave up because we ran out of time in our sprint. 

We changed our design idea to still allow flexibility, but instead of drag and drop, we use toggle switches to allow the user to pick what is displayed. It’s not the complete customizability that we initially wanted, but we were still able to keep part of our first design. 

Once we overcame that challenge, we were able to focus on the robustness of our app. We put our time into developing the UI and making the API function. We were also able to add location searching and radar placement. I didn’t have any part in either of those, but I’m still really proud of my team members for what they accomplished


<img src="/assets/images/flexforecast/code_snippit.png"
     alt="Image of the most elegant code you can imagine." />

### Deploying

This app is not ready to be deployed to the Play Store. It’s still full of bugs, the list of icons for all types of weather is incomplete (there’s a lot of weather types!).

However, our team may continue this idea in the future. While there is a possibility of us releasing it at some point our GitHub repo will remain private. However, if you want to read more about our project, you can check out our official blog ([here!](https://sites.google.com/augustana.edu/computersciencesi/blog))

### Testing

We tested our app on our friends and family. They gave us good suggestions that we weren’t able to implement, such as allowing all of our locations to be displayed on the home screen. If we continue working on the app, the user testing will be the first place we will start.