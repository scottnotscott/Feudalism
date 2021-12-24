<h1> Combat General Information </h1>

The player has a number of combat related stats, they are Melee, Range & Magic stats for combat offensiveness. And Defence and Resistance for combat defensiveness. They can each be trained to 99. You can experience in combat stats by using the specific attack style e.g. using magic in combat with NPC's and real players will gain you magic experience. The amount of experience earned in combat depends on a number of things but mainly the respective total level of the NPC or player that you are in combat with. You will have weapons and armour to augment your stats. Some items may provide additional abilities that can be used in combat. Some abilities will be much harder to get than others. Some ways you might unlock new abilities are: Completing Quests, Defeating Bosses and more.
Combat will end when a player spends an action on the 'Flee' ability. This will attempt to disengage the user from Combat. Should a battle commence and nobody flees then the victor is decided by death. Players have access a number of ways to support themselves in combat, Alchemy can be trained to give the user access to powerful temporary elixirs.

<h2> Player Vs Player Flow </h2>

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
```
Turn 1
    Player 1 does action1
        then
            Player2 does action1
                then 
                    Player1 does action2
                        then
                            Player2 does action2
                                then
                                    Player1 does action3
                                        then
                                            Player2 does action3
```

You choose to attack another player.
You select 3 actions for turn 1, click lock in, 
it does your first action, then the enemies first action, 
then your second action then the enemies second action, 
does ur third action then does enemy third action, 
turn 2 starts, select 3 more moves
repeat until someone dies or flees