---
layout: post
author: cridley17
title: "Claire's Final Project Update"
---
Below is what I have so far for my final project code:
<iframe src="https://trinket.io/embed/python/7f38e9370b" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Over the past two weeks I was able to accomplish a lot in my code. By the week of November 24 I created a new module and class that draws the coins the main game turtle will collect for points. I created three functions that serve as my three levels that draw the maze and also include timers. Each level has less time to complete. I also figured out how to restart my levels if the timer goes over the allotted amount of time using an if statement in my level functions. The main turtle can also only move if the timer is active. Instead of causing the level to fail if the main game turtle intersects with the maze, I figured out how to send the turtle back to the starting position. I created a list with coordinates that are contained within the maze obstacles. I then stored the main turtle’s current position into variables that I then stored into a list. I created a function that uses a for loop and an if/else statement to check that the main turtle’s position is not in the maze coordinates list. 
	For this week, I created a function that draws the coins for each level. I used random integers in increments of ten, because the main game turtle moves by tens, so the coordinates would match up. I stored the coin’s x and y positions into variables that were then added to a list, so this list could be used to check intersection with the main turtle. I used a for loop with an if statement to help ensure that the coins wouldn’t be drawn over the maze. I then created a function that checks if the main turtle intersects with the coins. I used the same list of the main turtle’s position and the list of the coin’s position to check. This function operates essentially the same way as the maze intersection check. If the main turtle’s position intersects with a turtle, a new turtle draws a red circle over the coin to signal that the coin has been collected. Also the score count in the dictionary is incremented by one. I also figured out how to iterate through my three levels using a while loop and if statements. If the main turtle gets a score of ten or more each level, the loop progresses to the function for the next level up. I wrote text to signal to the player that the level changes. I originally also stored my levels in a dictionary, but found this wasn’t effective because the level would increment by one, even if a level repeated because time ran out. 

My old plan was:
-	Week one: to create my background, turtle, and write the code to make the turtle move around the screen. Originally next week, I wanted to write the code that established each level and make the turtle move faster for each level, as well as beginning the mazes. Now, for the next week, I now want to figure out 
-	Week two: how to iterate through my levels, and to create my objects for my coins 
-	Week three: to write the code to update the score and level counters 
-	code completed by December 6 so that I have enough time before the project is due for any final debugging and to complete any work left on the reflection.
	
I have completed all my goals that I had laid out in my last project update. My original goals for next week, which were to figure out how to update score and level counters, and print those on the screen, I have already completed. One new goal I need to complete is to finish adding to the maze coordinates list. I don’t have the coordinates included for all of the maze obstacles yet. I have also figured out that there are components included in the project assignment that I did not include in my goals. These components are: having constantly available help dialogue, and using one for more custom images. I still want to attempt to have all my code completed by December 6, but this is probably a stretch goal, and I will be working on components of my program until the day the project is due. 
	My greatest roadblocks ahead are the two components of the project that I had not included in my goals until now. I am currently clueless on how to make my help dialogue constantly available. I currently have help dialogue at the start of the game, but I am not sure how I am going to exit the game for a help screen, and then return to game play. I have also tried using a custom image to show when the game is won, but it did not work. The image either did not show up, or it kept flashing. Another issue of the game, is that once a coin has been “collected” and it turns red, if the main turtle goes over it again, the score counter still goes up. I need to include an aspect in my code that will not allow the player to cheat the game by collecting coins over and over again. 
I have found that many aspects of my program that I was concerned about figuring out in my first project update, I was able to work through and implement into my project. I have spent a decent amount of time working on this project and trying different ways to make the game function how I want to. My goals could have been a little more ambitious. I did not anticipate dedicating the amount of time to this project that I have. I should be able to keep with my remaining plan. 
