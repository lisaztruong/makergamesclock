# MakerGames Clock 

https://lisaztruong.github.io/makergamesclock/

This is a wep app that helps organize timed activities for different groups. 

##Page components

###Inputs
User inputs total time in seconds that he/she wants to run the clock and how many divisions he/she wants to divide the clock into. For example, I have a class activity that runs for 10 minutes and I have 5 groups. I would thus input 600 into "time" and 5 into "groups". 

###Start
After inputing "time" and "groups", the user should hit the "start" button to activate the clock (left side) and allow the materials section (right side) to update. 

###Clock Section - Explanation of the other buttons available
1. (hedgehog) - User may click this button twice for the groups number of hedgehogs to appear. In this example, 5 will appear. 
2. (pause) - User may pause the clock 
3. (continue) - User may continue clock after pausing it
4. (restart) - User may restart the clock. Note: currently, the restart button here only restarts the clock. It will not erase/ rebuild the materials section.

###Materials Section
Currently, the default money value is 75. Users can increase or decrease the money by 5 using add and subtract buttons respectively. The reset button in the materials section will reset the money value back to its default. Users may also input materials and view them in a list form. Once the materials box exceeds its space, a scroll down bar can be used. 

##Known bugs
1. User must click twice in order for hedgehogs to appear. This has to do with how hedgehogs are loaded onto the page... we used a canvas object in the drawHedgehog(ctx, radius) function.
2. Restart button only restarts clock not the hedgehogs too.

##Future 
1. Placing a countdown timer so that users can see time change as the clock moves. For example, if the users input 5 hours then it'll take a long time for the clock hand to move and users might not realize the clock is running.
2. End button to end an interval and jump to the next one.






