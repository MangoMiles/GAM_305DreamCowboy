# Module Two Team Project Plan

**Miles Titus, Jordan Baughman, Filip Arghir, Angelo Melino**

---

## Scenario

Our game will be a third-person action game set in a warped dream of a cowboy's past.  
The player is trapped in a nightmare jail/castle environment where demonic enemies roam.  
The objective is to escape by exploring rooms, collecting keys, defeating enemies, and reaching the final boss.

---

## Brainstormed Game Design

### Core Gameplay

- Third-person combat system  
- Dodge-based movement system  
- Revolver weapon for ranged combat  
- Exploration of rooms to collect keys and unlock doors  
- Boss fight at the end of the level  

---

### Setting

- Surreal dream/nightmare environment  
- Old western castle-like jail  
- Demon enemies  

---

## Level Design

The level will consist of:

- 1 Courtyard (starting area)  
- 3 rooms  
- Locked boss room  

### Progression

1. Start in courtyard  
2. Explore rooms to collect keys  
3. Unlock final boss room  
4. Defeat boss to complete the level

---

## Game Elements

### Power Pickups

- Tonics – restore player health  
- Tumbleweed – restores stamina  

### Equipment Pickups

- Revolver ammo – reloads the revolver cylinder  
- Weapon power-ups – increase weapon strength  

### Enemies

- Demon enemies  
- Some enemies use swords  
- Some enemies use arrows/projectiles  

### Boss

- Final boss located in the boss room  

---

## Development Schedule

- Alpha - Week 5  
- Beta - Week 7  

---

## Alpha Stage Goals (Week 5)

The alpha build will include:

- PlayerChar (movement and dodge mechanics)  
- Basic combat system  
- Revolver weapon  
- Courtyard and rooms implemented.  
- Key collection and door unlocking.  
- Basic enemy AI  
- Pickups  

---

## Beta Stage Goals (Week 7)

The beta build will include:

- Boss enemy  
- UI  
- Improved enemy behaviors  
- Level polish  
- Bug fixes and gameplay balancing  

---

## Communication Methods

Our team will communicate using:

- Discord for quick discussion  
- GitHub for project updates and commits  

---

## Communication Frequency

- Weekly team meetings  
- Additional communication through Discord when needed  

---

## Task Assignment and Reporting

Tasks will be assigned and tracked using Discord & GitHub Issues and commits.

Each team member will:

- Claim tasks through GitHub Issues  
- Push updates through commits  
- Report progress through Discord.


# Module Three QA and Testing Plan

---

End of the week, do a playtest of each of the elements of the project,
do bug reports and updates on the test plan based on the results of the test

Checklist of things to be tested made as developers make features, 
each dev brings their own checklist of features they wish to test and we collaboratively go through each person's checklist together

Update the test plan at the end of the week based on what the team tests that session

Bugs to be reported both live during the test meeting and in a separate bug log in a discord channel that we have made specifically for bug logs

Bugs will be marked as either fixed or not fixed, with a change log that is updated as people attempt to fix the bug (so progress may be made on fixing a bug without the bug actually being fixed yet)

Beta Phase (Week 7), we focus on the demo and double check/clean up any remaining bugs that were on our checklist

## General Checklist on features we want to implement:
Player:
-	Movement
-	Dodging
-	Shooting
-	Interacting with objects
-	Interaction with pickups

Enemies:
-	Enemy AI
-	Pathing for Moving Enemies
-	Boss Mechanics

Pickups:
-	Health Pickup
-	Stamina Pickup
-	Ammo Pickup
-	Bullet Powerup

Environmental Interactables:
-	Doors and Keys
-	General Level Layout
-	Hazards

# Module Four Project Log - Team Reflection and Alpha Release

## What parts of the testing process did the team perceive to go well?

Initial map creation, player stamina and basic enemy AI for both moving and stationary enemies has gone well, and the next steps are adding in powerups, updating the map further and implementing a dodge mechanic, while also ironing out any bugs that arise during this process. 

---

## How were bugs identified and corrected?

The few bugs that have come up tended to be fairly obvious to muiltiple people on the team, so or usual process for handling bugs is noting it down in a log on discord, and allocating someone to test and attempt to fix the bug. In the case that someone isn't able to find a solution, the task is allocated to another member of the team, or in the case of a minor bug that doesn't break any other elements of the game, we keep tabs on it and attempt to find a fix for it in the background while working on other, more important tasks.

---

## In terms of the QA and testing process, what would you do differently to improve the process?

Our process didn't need to be utilized much only because we were fortunate to have most of our implementations work as intended, however one thing we think could be improved is adding to our logs documents on how mechanics are intended to work. For example, it could be a bug that stamina is only regenerating at a value of 5 per second, but its not caught right away because people think thats whats intended, as we have only discussed there being a stamina regeneration at all and not a specific value.

---

## What tools (chosen in Module Two) did you find successful in the development of your Alpha project? Why?

The main two tools we are utilizing outside of Unreal and GitHub would be Discord and Gitbash. Gitbash is our preferred way up commiting updates to GitHub, while Discord is our preferred way of communicating. Both of these tools have been excellent for us cause its tools we are all familar with and figuring out these tools didn't take away from our development time.

---

## Were there any tools or techniques that you did not find helpful in the success of your project development? Why?

So far, we've not had any issues with Discord or Gitbash that would require us to seek other tools. While we haven't struggled with the tools we chose, we can imagine that there may be some other tools out there that may be better then what we use currently, but we choose to not explore simply because we already have tools that work.

---

## How did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques?

It did not drastically effect our decision on the tools we wanted to use. We chose to use the tools that we felt the team was most comfortable with in order to devote time that would have been spent learning these new tools into development time.

## What parts of the plan did the team percieve to go well in relation to the last stage evaluation?

We have achieved the baseline of the majority of the mechanics we intended to introduce, including moving and stationary enemies, powerups of different kinds, door/key system, health and stamina UI, movement options like sprinting and dodging, and a handcrafted map that is populated with all the different elements as described. The game is in a functional state, with the remaining core mechanics that we are currently undergoing the full creation of being the shooting mechanics (with a beta version ready now), and a boss enemy that already has an arena prepared for it.

## What parts of the plan did the team percieve to go wrong in relation to the last stage evaluation
The only couple struggles we came across was:
1. Communication on who's doing what was up in the air longer then intended, leading to some elements of the project being slow to start.
2. We are attempting to get the player combat mechanics set in a very particular way, which is leading to revisions and bugs regularly throughout our process. The shooting mechanics provided in the beta is our current working version, which we are fairly happy with but we intend to update further.

## How were the previous evaluations integrated into this latest stage?
The primary thing we've been taking from previous evaulations is our github workflow. Things were slow at first as the group was getting accustomed to the workflow process when muiltiple members are working on branches at once, but otherwise we've been moving at an excellent pace.

## What would you do differently to improve the collaboration or development process?
In an effort to ensure we could get the project done in time, we wanted to stick to concepts and technical processes that we were already familar with, but we sometimes regret the possibility of doing something a bit outside of our comfort zone and try a new type of game that none of us have made. In that sense, we could have improved our collaboration by spending more time coming up with a more precise idea and vision of a more unique game.

## Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
Primarily the Issues feature in Github. Its ideally made to assist with documenting bugs and problems, but we found just recording things in discord and having proper communication worked far better, though its likely that's partly due to the small team size compared to a larger team where such regular communication may be a bit more rare.

## Identify the completed stage of development of the intended Beta and address the project schedule to meet Final Release developmental deadline.
Our intended beta was within our scope and overview, and at this point the last two remaining major elements we have yet to finalize is the boss enemy and the player shooting mechanics. Shooting mechanics are already underway, while the boss enemy is something that is currently in active discussion as we have a couple different ideas on what will seperate the boss from other enemies, and its just a matter of finding which option feels best for us (if not combine multiple of them).
