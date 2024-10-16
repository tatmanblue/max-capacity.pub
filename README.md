# Max Capacity
[![BuiltWithDot.Net shield](https://builtwithdot.net/project/5737/max-capacity/badge)](https://builtwithdot.net/project/5737/max-capacity)

**The ultimate factory management challenge.**  


## Available Now

__Version 1 Full Release__ available now on [Itch.io](https://tatmanblue.itch.io/max-capacity) and [Steam](https://store.steampowered.com/app/2579870/Max_Capacity/).  Please see the steam store for the latest release updates.

[![Release Announcement](https://img.youtube.com/vi/kaOTkWa1Pi0/0.jpg)](https://youtu.be/kaOTkWa1Pi0)


## Social Media
[Press Kit](https://impress.games/press-kit/tatman-games/max-capacity)  
[Steam Store](https://store.steampowered.com/app/2579870/Max_Capacity/)  
[Website](http://www.tatmangames.com)  
[Youtube Channel](https://www.youtube.com/@MattRaffel)  
[Patreon](https://tatmanblue.itch.io/max-capacity)  
[Itch](https://tatmanblue.itch.io/max-capacity)  
[Reddit](https://www.reddit.com/r/MaxCapacity/)  


## Tag line

The ultimate factory management challenge.

Max Capacity is a factory simulation game that challenges you to build and manage the most efficient factory possible. You must hire and train employees, purchase machinery, and configure production lines to produce goods as quickly and cheaply as possible. The market for your goods is constantly changing, so you need to be constantly innovating and adapting your strategies to stay ahead of the competition.  

In single-player mode, you can compete against other players on the Steam leaderboards to see who can make the most money. In multiplayer mode, you can work together with other players to complete contracts and earn even more money.  

Max Capacity is a challenging and rewarding game that will test your skills as a factory manager. If you're looking for a game that will keep you entertained for hours on end, then Max Capacity is the game for you.  

Here are some of the things that make Max Capacity an exciting game to play:  

* Challenge of building and managing an efficient factory.  
* Ever-changing market conditions that keep you on your toes.  
* Compete against other players on the Steam leaderboards.  
* Cooperation required in multiplayer mode.  
* Accomplishment you feel when you successfully complete a contract or achieve a goal.  

If you're looking for a factory simulation game that is both challenging and rewarding, then start playing Max Capacity today!


## Core Tech

- Unity
- C#


## Purpose

While the goal is for players of the game to have fun, the real purpose of this game is to:

1. Demonstrate how market forces around supply and demand in a closed system change outcomes for both human players and AI agents.
2. Use AI and possibly some ML to add controls into economy for the purpose of adding real time adjustments to market conditions based
on player actions.
3. Aggregate data from all players causing impacts to the economy in the entire game, globally and visable to all players. 

# Game Play

_Please Note_: this section will be updated as more decisions are made about game play  

## Summary

Player builds a factory and hires employees with the funds in their banks account.  The player manages the employees and the goal
is selling product made in the factory to make a profit.

## Employee (also called Agents)

Existing Agents:  

| Employee | Function |
| -------- | -------- |
| Staff    | Create and gather resources used by equipment in the factory |
| Buyer    | Buys material used by equipment in the factory |
| Sales    | Sells material and finished product on the market |  
| Stocker  | Helps move inventory between containers |  



## Components

Existing Equipment in the factory:  

| Equipment in the factory | Function |
| -------- | -------- |
| Container | Storage.  Currently there are two storage containers with the primary difference between them being volume |
| Machine | Converts materials into other materials and products.  Currently there are 4 machines--all have the same abilities |


# AI

Long term goal is to incorporate AI to interact in the markets, both for single and multi-player modes, to help keep the market changing in realistic patterns.

## AI & Markets

Markets are now data driven with data from all participating players used to create realistic pricing models.  The models are consumed by all
players to create their local economy.

The AI resides server side and not in the game therefore requiring players to agree to contribution anonymized market data from their game play.


# Format/Platforms
Unity Game.  For Windows, MacOS, Linux

## Installation/Using
Built with Unity 2022.03 LTS

You must have the 3rd party assets installed prior to opening any of scenes.   In house assets are built by bulding and exporting the asset and are checked into the repo.
3rd party assets must be purchased from the vendor (links provided).  

## Access to the Code

An NDA is required to view the materials including game design documentations and code.  If you wish to view this material, please contact me.  

# Legal
If you have any questions about the content of the repository, please email [matt.raffel@gmail.com](mailto:matt.raffel@gmail.com). I can assure you all content has been purchased and licensed to me. Proof will be made available on request. Repeated DCMA counterfit and harassment claims will result in counter suits per Section 512(f) of the DMCA penalties for _misrepresentation can include actual damages and attorney’s fees_.

# Status
On-going/Active

This game is in active development stage.

edited: 2024.06.17
