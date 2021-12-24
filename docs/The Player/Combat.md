<h1> Player vs Player </h1>

```
Player1(experienced)          Player2(noob)
                ===TURN ONE===
Action1: Raised def        Action1: Attack enemy
Action2: Raised atk        Action2: Attack enemy
Action3: Attack enemy      Action3: Attack enemy
                ===TURN TWO===
Action1: Healing Pot    Action1: Attack enemy
Action2: Attack enemy   Action2: Heal ability
Action3: Call for help  Action3: Raised def
                ===TURN 3===                      <=== Player3 *joined player1's call for help
Action1: Attack enemy   Action1: Attack enemy          Action1: Heal player1
Action2: Attack enemy   Action2: Attack enemy          Action2: Attack enemy
Action3: Attack enemy   Action3: Attack enemy          Action3: Attack enemy
```

Players will have access to a number of abilities that can be unlocked by levels or by achieving game specific things. Some abilities will be much harder to get than others. Some ways you might unlock new abilities are: Completing Quests, Defeating Bosses and more.
Combat will end when a player spends an action on the ability 'Flee' which every player starts with. This will attempt to disengage the user from Combat. Should a battle commence and nobody flees then the victor is decided by death. Players have access a number of ways to support themselves in combat, Alchemy can be trained to give the user access to powerful temporary elixirs. If you are dying in combat too much 

```
/*
* Player1 and Player2 each turn will  have 
* 30 seconds to select 3 actions.
* The turn system then executes each players action
* one after the other until all actions have complete
* it then moves to turn 2 where it repeats the sequence
* until someone either flees or dies.
* Each action can be anything you can normally do in combat
* Such as attempting to flee, using abilities to attack, buff or heal and calling for help
*/

|---------------------------------|
| Player1 -> Engages -> Player2   |
|       MOVE SELECTION STAGE      |
|-----------TURN 1 START----------|
| Player1 Action1: Buff Magic     | <-- Player1 selected to buff their Magic stat with an ability first
| Player2 Action1: Melee Ability  | <-- Player2 selected to attack Player1 using a Melee ability first
|               ---               |
| Player1 Action2: Buff Defence   | <-- Player1 selected to buff their Defence stat with an ability second
| Player2 Action2: Buff Melee     | <-- Player2 selected to buff their Melee stat with an ability second
|               ---               |
| Player1 Action3: Magic Ability  | <-- Player1 selected to attack Player2 using a Magic ability third
| Player2 Action3: Melee Ability  | <-- Player2 selected to attack Player1 using a Melee ability third
|---------------------------------|

/*
* 30 seconds have now elapsed and the turn selection stage is over
* the selected actions are then executed in order dictated by the aggressor
* The aggressor due to attacking first has their turn execute first
*/

|---------------------------------|
|         EXECUTION STAGE         |
|---------------------------------|
|    Executes Player1 Action1     | <-- Player1 uses Buff Magic ability increasing their Magic stat
|    Executes Player2 Action1     | <-- Player2 uses Melee ability deals dmg to Player1
|               ---               |
|    Executes Player1 Action2     | <-- Player1 uses Buff Defence ability increasing their Defence stat
|    Executes Player2 Action2     | <-- Player2 uses Buff Melee ability increasing their Melee stat
|               ---               |
|    Executes Player1 Action3     | <-- Player1 uses Magic ability deals dmg to Player2
|    Executes Player2 Action3     | <-- Player2 uses Melee ability deals damage to Player1
|------------TURN 1 END-----------|

/* 
* This is Turn One in its entirety.
* Turn Two would begin next with
* the players having 30 seconds to choose
* their next 3 actions.
* Reminder: Players can use abilities, eat food, drink potions, flee & call for help during combat.
* Each of the above consumes one action. 
*/

```