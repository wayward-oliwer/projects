# Projects
This portfolio includes 2 projects completed as a part of my personal ventures, as well as a personal VR environment that I have created from scratch using Blender.

## Personal Encryption Python Project
This is a Python project that was completed for my personal amusement.
It is an encryption software that utlises majority of the visual characters of Unicode.
It adds a random number to each character in the message and then converts that number into a string of characters.
The same process is used for decoding (but the number is not randomly generated but simply the key provided is used).

## Personal Chess Python Project
This is a Python project that is still being worked on for my own pleasure.
It is a Chess program that allows 2 players to play a game of Chess together.
It has a set of rules made for each piece and the board is stored as an object.
This is all done to maximise the efficiency of checking the validity of the moves as well as searching for a checkmate.

## Personal VR Environment Project
This is a VR environment that was inspired by "Effects of Emotion and Agency on Presence in Virtual Reality" research page.
(Link: https://dl.acm.org/doi/abs/10.1145/3411764.3445588)
It is a VR environment that is suppose to create a calming feeling through the lighting and imagery.
All assets in the environment were made by hand (including the textures).

# Additional Projects
As part of my university degree, I had to complete multiple courseworks that displayed my programming skills to the university board.
However, the university prevents me from sharing this coursework online and hence, I would not able to add it to this profolio.
This is why I will do some brief descriptions of each one of the projects instead.

## Theatre Rating Web Application
This application was designed for computer web browsers and was written with 4 other developers.
It utilised JavaScript to create the front-end and as the web application was simply supposed to be a prototype for the stakeholders, the back-end was minimal due to the tight deadline assigned for this project.
The primary focus of this application was a close connection with the stakeholders, which consisted of the target demographic of the user base, people aged 18 to 30. 

The application consisted of users creating accounts and leaving reviews for different theatre productions that they have seen. This included professional and amateur production.
The inclusion of amateur productions was the unique selling point (USP) of our application as it allowed for promotion of the arts on an amateur level, which no application has done previously.
A friend system was in place to allow friends to see each other's reviews and promote shows to each other.

Features, such as ticket purchasing, wishlists and a premium feature, would be implemented in the future to maximise the company's growth and project's longevity.

## 3D Rendering Software
This software was written using C++ and allowed for OBJ files to be read and projected onto a 3D space, where materials, textures, and lighting could be added and changed to create a final rendering image.
A basic empty framework of the software was provided to us by the university and all the expansions to make the framework functional was done by us. I have implemented texturing as an additional feature of the rendering software, 
it included reading image files and mapping the colours of the file onto the faces of the objects within the environment. 

Photon Mapping was added as a final feature of the software, which allowed for a more realisitc mapping of the environment than the raytracing that was initally part of the software. This involved changing a vast majority of the framework to account for photons being entered into functions rather than the rays that are used in raytracing.

## Recyclablity Scanner Application
This application was designed for Android and was written with 6 other developers.
It utilised React Native and Node.JS to create the front-end of the application and Python to create a relational database for the community aspect of the application.
The application used an existing AI model of classifying what bin a recycleable object would go in. This was done primarily due to the time constraints of the coursework.

Users would use the application to scan trash and see which bin to put it in to prevent incorrect recycling. Potential users were the primary stakeholders that were contacted on a regular basis.
As the Agile system was used to create this application, it allowed for a regular flow of feedback between the stakeholders and the development team.

The relational database was utilised as a game aspect was added to the application to encourage users to use the app within their households. 
The game aspect involved a guessing trivia after each scan and if the correct guess was acquired then points would be acquired by the users so they could compete with friends and flatmates on a leaderboard.

## RPN Calculator
This was a program which prompted us to use an existing software of a Reverse Polish Notation (RPN) calculator that the lecturers created.
There were many hidden features and quirks that it contained that could only be found using extensive testing. 
The program was written in Python and was tested against the original calculator created by the lecturers.

## Dungeon Crawler Game
This was a program which involved us reading an imported map of a dungeon. The dungeon had walls, coins, an exit, the player, and the enemy (AI).

The player had to could complete 1 of 5 actions:
- Look: A 5x5 matrix of the space surrounding the player is displayed.
- Pick: Collects the coin that the player is on. If a coin exists at their current location, it increases their score.
- Victory: Sees how many coins the player needs to collect to win.
- Move: Moves the player by 1 space in the direction that they want to move in (North, South, East, West). If there is a wall in the new location, it doesn't permit the movement.
- Exit: Closes the game. If the player is on the exit and has the coins needed for victory, game is won.

The AI in this game has been designed by me and had set priorities to maximise its victory, which could be done by catching the player or by collecting enough coins to exit the dungeon and win.
The program was written in Java and was tested with various maps by the university board.
