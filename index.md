# Intro
Hi! I'm James McManus, a Computer Science and Game Development student at Northeastern University. This is my WIP portfolio, mostly for my game development work. I will be updating this website relatively frequently to showcase any new work I've created, or to better highlight my current work. My contact information is below and additional information is located at the top of my resume. Thanks for stopping by!

### Contact information
mcmanus.j@northeastern.edu

[Resume](James M Resume.pdf)

[LinkedIn](https://www.linkedin.com/in/james-mcmanus-819a39206/)




# Projects
## Spaceship FPS
[Itch.io Link](https://mcmanusj.itch.io/mca4)

Engage enemy ships that are raiding space stations around planets in our solar system. Fight them off with your ship's fast-firing lasers and slow but powerful missiles, and defend the space stations. This was an individual project created for my Game Programming class, and mainly showcases the basics of Unity that I've learned over the semester. Enemies either charge straight towards the player or are controlled by a simple Finite State Machine (FSM), which switches between patrolling, chasing, and attacking states based on line of sight and proximity to the player. 

![Image](https://cdn.discordapp.com/attachments/475503547656568842/831848450639134770/unknown.png)

Player firing upon an enemy ship near Mercury.
![Image](https://cdn.discordapp.com/attachments/475503547656568842/832025472355139621/unknown.png)

Side note: you can probably tell from the pictures, but the planets are not quite in the right spot or the right size, but they are to scale relative to each other.


## Bullet Hell Endless Scroller
[Itch.io Link](https://bejules.itch.io/fp3).

Group project created for my Game Programming class. Everything except assets and animations were written and made from scratch. 

A Screenshot from the first level of the game. Player is the green character in the bottom middle, and the camera slowly moves upwards as enemies spawn along constantly generating terrain. As the player defeats enemies, they gain experience and levels, which can be spent in the shop shown in the next picture.
![Image](https://cdn.discordapp.com/attachments/475503547656568842/831840201620979712/unknown.png)

The shop is accessable by beating the boss at the end of a level or dying, and it contains permanent upgrades for the player, including new spells, movement speed, damage reduction, etc.
![Image](https://cdn.discordapp.com/attachments/475503547656568842/831847536821796874/unknown.png)

The first boss in the game, the Goblin King. The boss switches between two phases on a timer. In both phases, the boss runs back and forth along the top of the platform. In the first phase, the boss fires a projectile directly downwards periodically. After a certain amount of time, the boss will switch to the other phase. In this phase, if the player is in line-of-sight of the boss (i.e. directly below the boss), the boss will charge forward quickly. After a certain amount of time, the boss switches back to the original phase.

Phase 1- Boss fires projectiles downwards.
![Image](https://cdn.discordapp.com/attachments/475503547656568842/832029413839339520/unknown.png)

Phase 2- Boss is charging at the player, dealing damage on contact.
![Image](https://cdn.discordapp.com/attachments/475503547656568842/832029485993558026/unknown.png)


## FPS Phase-Shifting Mechanic Showcase Level
[Itch.io Link](https://mcmanusj.itch.io/phasechange).

This level is a showcase of a mechanic I came up with based on a game design pattern a classmate had created. The [design pattern](https://patternlanguageforgamedesign.com/PatternLibraryApp/PatternLibrary/442) talked about how the core shooting mechanics of most shooter games are relatively stale, and how designers need to change the way players utilize shooting to make shooting an interesting mechanic. I came up with the idea that whenever the player shoots, the world switches phases, denoted by Blue and Orange objects for each phase. Only one phase can be active at a time, so whenever the player shoots while blue objects are visible, the blue objects disappear and the orange objects appear. As the level progresses, more things become tied to phases, and the player has to think about their position and crosshair placement to 'defeat' all of the enemies (capsules) in the level. The level is a simple showcase of the mechanic, so the demo is focused more on that and lacks general polish.    


Level from the side, showcasing the space filled by objects in both phases (Orange and Blue) in the beginning of the level : ![Image](https://cdn.discordapp.com/attachments/803364518818349116/815703117911031859/unknown.png)

Level is initially in the blue phase, shown here ![Image](https://cdn.discordapp.com/attachments/803364518818349116/815702624858144788/unknown.png)

Player fires a shot from the same spot as the previous picture, switching the phase to orange, changing the geometry of the level. ![Image](https://cdn.discordapp.com/attachments/803364518818349116/815702667169890314/unknown.png)

I plan to make a more polished and functional demo over the summer of 2021, and will update/add on to this section in the future. 


