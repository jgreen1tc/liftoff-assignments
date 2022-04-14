# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
Catalyst aims to be the unofficial companion app to aid in running The Hub and Spokes section of the indie tabletop roleplaying game, The Burning Wheel. While the full ruleset of the game is over 500 pages long, The Hub and Spokes manages to reduce the rules of the game to their basic components - around 70 pages describing the general process of playing The Burning Wheel. This can still be a lot for a person to remember, but luckily, while initially complicated, the process of playing the game follows the same pattern or loop each time. 

Once finished, Catalyst will automate the complicated process of running The Burning Wheel using rules from The Hub and Spokes by hosting all of the game assets, providing all of the necessary prompts to the users at the appropriate times, executing the appropriate actions based on the users prompts, and keeping a log of the results.

### Features
User login: Users will be able to create an account and/or log in using their Discord credentials via auth0. Each user will be a Player and/or GM and will have a profile.
Create characters: Both Players and GMs can create Characters using the rules presented in The Hub and Spokes of Burning Wheel. 
Create games: The user that created the game becomes the GM. Games consist of approved Characters controlled by either Players or GMs, the Situation, and optional discord server information.
Create tests: Players and GMs play the game by creating Tests that represent a characters Intent and Task when faced with a Situation. 
Evaluate tests: Tests are presented and voted upon or approved by the GM before being evaluated by the program and logged to update the Situation for the next test. 
Update chacters: Character attributes are automatically updated based on the results of the test. Characters are given Artha based on a vote of the test log.
Discord chat: If a GM provides discord server info, their server is embedded into the app.
### Technologies
Java
Spring Boot
MySQL
Hibernate
Angular
TypeScript
### What I'll Have to Learn
Integrating discord for login and chat servers
### Project Tracker
https://trello.com/b/tQ2ZLFoh/project-board
