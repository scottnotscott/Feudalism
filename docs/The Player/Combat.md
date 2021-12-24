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
* Player1 and Player2 each turn will select 3 actions.
* The turn system then executes each players action
* one after the other until all actions have complete
* it then moves to turn 2 where it repeats the sequence
* until someone either flees or dies.
*/

|---------------------------------|
| Player1 -> Engages -> Player2   |
|--------------TURN 1-------------|
| Player1 Action1: Buff Magic     |
| Player2 Action1: Melee Ability  |
|               ---               |
| Player1 Action2: Buff Defence   |
| Player2 Action2: Buff Melee     |
|               ---               |
| Player1 Action3: Magic Ability  |
| Player2 Action3: Melee Ability  |
|--------------TURN 1-------------|

|---------------------------------|
|         Combat Continues        |
|--------------TURN 2-------------|
| Player1 Action1: Buff Magic     |
| Player2 Action1: Melee Ability  |
|               ---               |
| Player1 Action2: Buff Defence   |
| Player2 Action2: Buff Melee     |
|               ---               |
| Player1 Action3: Magic Ability  |
| Player2 Action3: Melee Ability  |
|--------------TURN 2-------------|

```