---
layout: post
title: SoliderS Devlog:Game Design Document
---
Welcome to dev log of SoliderS, today is the first day of development, I focus on working out a simple game development document.  
Writing a GDD is kind of hard work, but thanks to google, I finish this with the referense of  
[how-to-write-a-game-design-document](http://trickgs.com/blog/how-to-write-a-game-design-document/)  
[Writing a GDD Game Design Document](https://www.youtube.com/watch?v=VrP6VM3XpIk)  
[basic-game-mechanics](http://www.gamedesigning.org/career/basic-game-mechanics/)  
ETC..  
Below is the first version of my GDD, since I plan to finish this game in 3 months with spare time, I keep all of them simple, hope this can draw your interest in my game and I will keep updating the progress in here.

# Game Design Document of SoliderS

## Introduction / Project Description  
This game design document describes the details for a 3rd person action game on mobile platform (ios/android).  

In this game, player controll a super solider with simple tab input to complete missions, for example : steal secret files, base explode, bomb disposal, assassinate etc...  

The name "SoliderS" is short of Solider Super, and also soliders which means the hero is one of the soliders.

## Genre / Target Audience
Genre : 3rd Person Action + Puzzle Game
Target Audience : 12 ~ 35 Male, who interested in military topic game

## Background
### Characters

#### Solider Super
Player controller character, a well trained solider, has many skills to accomplish missions, a tactiturn guy, the only thing in his mind is to complete his job.

#### Commander
Man who gives missions to solider super

#### Solider A  
The super solider of enemy force

### Story
Two big forces are under war conflict, besides sending army, they also send many well trained soliders into opposite side to do destroy work or steal secrets, you are the one who just finish the train and heading to the battle field. 

### Story Progression
Games starts in a tutorial scene, player control solider super to use his skills and finish a few simple task.  
After the tutorial scene, solider super will be taken away by a helicopter, in the helicopter, commander will give you a brief of the mission. When a brief finish, solider super will be dropped into the mission field and mission start.  
Helicopter will show up every time when the mission finish.  

### Theme
This is a game about war, a man become very small when under the war machine, everyone plays a little component and can be replace anytime.(Well, actually nothing special, just enjoy the game XD)

## GamePlay

###  Goals
Overall (long term) : Help to win the war, give an end to everything
Game Play (short term) : Finish missions (get secrets files, kill VIP, set a bomb, destroy a bomb, help somebody out)

### Player Skills

 *  Tap on the screen
 *  Predict the Enemy's movement
 *  Move the aim and release
 *  Puzzle solving

### Game Mechanics

#### Moving System
Player can control the character to move with tapping on the screen, there are way points in the map, what player need to do is tapping the way point and the character will move to the target with setup path

#### Enemy System
There are enemies between each way point, an enemy patrol with setup path and behavior, enemy has view port, if player control character run into their view port, they can spot the character and the game is over.  

#### Sniper System
When character reach a way point with sniper rifle, game screen will turn to a sniper scope, enter sniper mode
Under sniper mode,
 * When player touch the screen, he/she can move around to aim the target
 * When player's hand left up from the screen, character will shoot with the rifle, and reload  

#### Bomb System
When character reach a way point with green package, game will enter bomb setting mode
Under bomb setting mode,
 * Player have to create a puzzle before the time limit
 * After setting the puzzle, puzzle system will rate the complexity and give the escape time amount to player
 * Player need to reach the escape way point within escape time amount, otherwise the game is over

When character reach a way point with red package, game will enter bomb disposal mode 
Under bomb disposal mode, 
 * Player have to resolve the puzzle before the time limit, otherwise the game is over

#### Puzzle System
As the pic below, the puzzle are made by different color start points ( Square ) , end points ( Circle ), and lines between them.
Player have to move the start point square to the end point circle along with the line, line will disappear when start point reach to the end point, which means ways to the end point will become fewer and fewer.
When all start points reach to end points, the puzzle is complete.
![Alt text](/img/1469349836613.png)

#### Mission System
When character enter the field, missions will show up, there are key missions and optional missions.
In order the clear the stage, player should finish all the key missions.
Optional missions are not necessary to finish, but complete them can get higher rank when clear the stage.

## Art / Concepts
![Alt text](/img/1469352736234.png)
![Alt text](/img/1469352753955.png)
![Alt text](/img/1469352785380.png)
![Alt text](/img/1469352880495.png)

## Sound and Music
The sound effect and  music should have a Retro style.
Sound effects will show up when player does something good, keep positive feedback to player.
The background music will be causal at the beginning and become more and more tense with stage progress.

## Technical description
Initially, the game will be Mobile Cross-platform :
 * iOS
 * Android

Game will developed with Unity3D

For project management use Trello. Use github for storing code and assets

## Marketing & Funding

Start a YouTube Channel and post development diary.
Record development logs on blog website.
Create a press kit and send to gaming new websites.

As one man team, game should be finish with self pocket money

