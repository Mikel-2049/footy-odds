<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Footy Odds

Final project for the Building AI course

## Summary

Football has become an increasingly complex and popular sport, and viewers are coming up with new metrics to grade a team's performance other than the score itself. The project's aim is to take this underlying metrics such as xG, average pass direction, field tilt, and even outside metrics like days since last game, squad size, and others to create a model that is able to predict the ammount of goals that will be scored in a match by team, ergo the result. 


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

Football, as most sports do, brings a sense of anticipation to itself. It is only natural to try and predict how your team will perform based on the football they play, and there is nothing wrong with trying to make some money by making accurate guesses. 

As someone very passionate about football, my true goal is to understand the math that shape football, how different styles are represented in numbers, why some squards are succesful, why some fail, and how good is a player for tha system.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

First phase it can be mainly used for game viewers who wanna get ahead of the game, all they would need is somewhere to connect to the program.

Second phase would be used by clubs who are looking to get a better understanding of their own teams, looking into potential transfers, or wanna refine the coaches tactics.


## Data sources and AI methods
Firstly you need to get the stats, I would rather use a single source of data, such as Opta (https://theanalyst.com/na/2022/10/premier-league-stats-2022-23/). I believe that first one would need to check for every top data providers, and if there is a need to use multiple providers, calculate averages for overlapping data.

With the data as the input layer, we would now need to think about the hidden layers. A neural network with supervised training would work great. High quality data has been recolected for more than 10 years now, that gives us 3800 games to chose from just from the Premier League. 

Once we have a reliable model, it can be used for predicting future games and simulate seasons ahead. 

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

There are factors that are yet outisde the scope of quantifiable numbers, like the atmosphere around the club, mental health, and so many human interactions that make up the job of a top athlete.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

I see this project as a 2 phase monster. The first part has been explained, training a neural network to predict goals scored in a game so we can predict scores and seasons.

The second phase would be my main interest, scale the project to be able to use the data inside the network to have a better undestanding of what goes into a match. With that one could see what specifics are needed to improve based on the style of play, which players would fit the team, how certain roles need to adapt, etc... create a general understanding of football that gives specific fixes.

