---
layout: page
title: Part C
---
## Part C

### C1) 

#### User Story 1: As a programming student, I want to be able to communicate with my classmate so that we can discuss the code.
<p align="center">
<img src="https://i.imgur.com/xiKbFCb.png" width="350">
</p>

* We decided to utilize a mute button instead of a text chat box. This seemed like the appropriate choice since it is the most similar to Zoom’s appearance and functionality. 
As a result, the user is experienced with the look of a mute button and how it functions. This reduces the learning curve of the new software drastically. 
Additionally, we believed that the speed at which a person types versus the speed that they can speak is a much faster and more precise way to communicate. 

#### User Story 2: As a programming student, I want to be able to see what my classmate is typing so that I can follow along and comment on what they are doing.
<p align="center">
<img src="https://i.imgur.com/dMezaJe.png" width="350">
</p>

* We decided to implement a live update signal, which will show what contribution the user has made to the code. We chose this over having different users’ cursors appearing 
as a different color. We believed that the different colors would make the code look confusing as IDEs already use different color fonts. Using the live update signal instead 
allows all users to see when something is added to the code and by whom, without getting confused. This can also lead to accessibility issues for color blind users. Since it is 
important to see when new things are added, our solution can increase efficiency in pair programming and diminish the amount of future debugging. 

#### User Story 3: As a programming student, I want my coding partner and I to have access to the same file so that we can work on it simultaneously on different devices.
<p align="center">
<img src="https://i.imgur.com/j1C0EFe.png" width="350">
</p>

* Providing an available project tree on the left hand side of the screen for quick and easy access to project files eliminates the navigation time that would have been wasted
by switching back and forth between files. This design is superior to our other design which was simply showing the user the current working directory. Viewing the project tree
versus only the current working directory also allows the user to stay organized and prevents misplacing files as all users can clearly see the location of each file.
