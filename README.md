# ABB Robot Challenge

I participated in this hackathon with a team of three of us. It was a very interesting experience and I like the concept of the task. We chose to work from home. First, we had to learn about the ABB Robot Studio program and watch the tutorials, and only then did we start the task.

In addition, there is a story behind our work. Everything went well and smoothly with a lot of laughter and coffee, while the other members did not get tired and went to bed to take a nap. Energetic and optimistic, I continue to work on the task (on the computer where we combined all the versions and edited the codes - it was our first version of the solution that we wanted to further improve as much as we could in the remaining time). During my work, the program only suddenly crashed. I didn't know what to do. I had to restart the computer, and the BOOM part of the solution disappeared forever (since we didn't have a backup version). The first problem was what to say to the other members of the team and in addition to how we will get everything in the remaining 8 hours. In the end, we did not reach the end to complete the solution, but for the most part, we did. I am proud of my friends who did not get angry. We continued to work as quickly and efficiently as possible. We learned about ABB Robot Studio, but also about team spirit! :sparkling_heart:

**Recommendation:** During the hackathon, always make back-up versions and work in programs where you can work in sync with other team members! :+1:

# Problem - YuMI robot :mechanical_arm:

mplement an application in which the YuMI robot makes cocktails by default
recipes. The appearance of the working environment is shown in Figure 1. Near the robot,
there is a glass in which the robot has to prepare a cocktail, two bottles of drinks that are on
dozers as well as three bottles of drink that are closed with a stopper and are located on a pedestal next to it. There is a different type of drink in each container. Dozer bottles are filled
with squeezed juice, while the bottles are closed with corks filled with carbonated drinks.


The user has the option to enter a cocktail recipe using Teach Pendant. If the user enters a combination of drinks that is impossible to make, it is necessary to inform him and enable a new entry of the recipe. For the realization of this functionality is necessary
is to use the built-in functions TPReadFK, TPReadNum and TPWrite.
The recipe is input correctly - if there are enough ingredients. It can be considered that
Squeezed juice is always available, while fizzy drinks are available
only for one dose.

<p align="center" width="100%">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/65766968/156891874-c56c87b0-d476-478d-96b7-64bb7bc6cbd9.png">
</p>

When the recipe is input correctly, the robot starts preparing it. It's necessary
to prepare a cocktail in the glass located in front of the robot. Squeezed juices are poured from a bottle
with dozers. To pour the squeezed juice, it is necessary to place the glass directly below
the dozer and then it is necessary to activate the dozer by raising the glass and the lower
move the dozer surface 10 mm upwards. For the whole dose to be poured, it is necessary
is to have the dozer activated for at least 2 seconds. To pour carbonated juice into a cocktail
the robot must take the bottle with one hand and unscrew the cap with the other hand
finds on it. 2.5 turns are required to unscrew the pin correctly. After pouring
the carbonated beverage, it is necessary to return the cap to the bottle correctly and place the bottle in its initial position. The user must be informed when the cocktail preparation is completed. 

After the user has confirmed that he has picked up a cocktail and set up an empty glass (glass is set
always in the same place) it is necessary to enable the user to recreate the recipe for
a new cocktail. 
