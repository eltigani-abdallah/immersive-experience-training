


# Projection Area
^projection-map


![projection map](projection-map.png)

# Fireball Combat

- players: 8 (4 on each side of the [[#Projection Area]] to play 2 sessions at the same time)
- genre: combat

- desc: 

>4 players split into 2 teams.

>each player has one role between combat or support.

>combatants stand next to the wall to shoot fireballs and block to reduce the enemy's HP to 0. once energy runs out the combatant can neither attack nor block

>supporters run on the floor to collect energy that will be sent to the combatants, allowing them to keep fighting.

- status: refused

>running 2 sessions at the same time would consume too many CPU resources but running 1 session at a time would leave the other side of the projection area unused


# Laser Tag thing



proposed by Mehdi



![laser-bullet image](laser-bullet.png)


- players: 4
- genre: real time shooter(?)
- desc:
4 players split into 2 teams, collecting energy and firing bullets in real time

> **Energy:**
>	energy is collected by (collecting shapes on the ground, clearing a mini game on the wall)
>	more energy = (faster bullet, more bullet lifetime, longer bullet trail)

>**bullets:**
>	bullet fires after a timer reaches 0 
>	timer can start by one of two methods:
>	1. button on wall
>	2. coming close with a team mate

>**100% energy special bullet:**
rebounds even from the back of the play area to the other wall. even goes into VP-COUR and VP-JAR to bounce back 
`FriendlyFire = ON`: hitting self or a teammate loses a point
if the bullet hits two players at the same time the team that fired it gets 100% energy.
if the energy shape is far enough from the player then the player gets a reward for collecting it (how to measure the distance of the player from the energy shape?)

> **traps**
> increases the size of the affected player's hitbox (hit circle?) making them easier to hit with bullets


- **gameplay**

>bullet fires in the direction of the second player in the team, bullet rebounds based on energy (more energy = more bounces) enemy can move and avoid the bullet in real time while collecting energy

>each team has a certain (number of bullets, time) in possession and the game ends when the (bullets, time) run out and one team has more points

>in case of a draw the number of bullets becomes infinite until one team gains a point (golden goal)

>traps could appear from time to time


- **setup**

>walls: Heads Up Display showing the amount of points, energy bar,bullet trajectory before firing, timer (start button?) and 100% special bullet if available

>floor: energy shapes to collect, bullet trajectory after firing, player tracking points





# Kahoot

![interactive kahoot](interactive-kahoot.png)

- [Miro link](https://miro.com/app/board/uXjVHaO50GU=/?share_link_id=792621640516)
- Players: 50
- Genre: puzzle, quiz
- Desc:
Kahoot with elimination using body tracking



- Gameplay

> questions show on one wall, players go into spaces on the floor depending on what answer they choose. zones increase in size as more players go into them, at the end of the timer the correct answer is shown at the end and the players with the wrong choices get eliminated until one winner remains


- Setup:

> - Jar: Questions and zones assigned to answers
> - Floor: Zones and player amounts on the floor
> - Cour: Amount of rounds remaining and timer before the end of the round
