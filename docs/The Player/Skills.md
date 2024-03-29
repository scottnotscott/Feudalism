## Skills

### Gathering skills
Acquire resources, sell them or donate them to your village supply.

### Woodcutting

Woodcutting is a gathering skill which has a max level of 99.
There are multiple tiers of tree you can cut which are gated by your woodcutting level.
Each tree has a level requirement check and a tool requirement. 

a tip

    Obtain tools by purchasing them in the marketplace.


#### Oak Tree

![Oak Tree](../img/oak.png)

    id: 1,
    name: 'Oak Tree',
    examine: 'An Oak tree, provides Oak Logs.',
    LevelRequirement: 0,
    BaseExperiencePerAction: 15,
    BaseActionTime: 10,
    drops: '1x Oak log',
    succRate: 67,
    type: 'solo',
    tool: 'Bronze Axe',

The Oak tree is the first woodcutting activity the player can do. However it is very useful. Oak is a valuable component for the village supply. The emperor of the village can use this to provide buffs to the villagers which are useful for activities such as war or resource masses. Oak logs can be used in the crafting skill, can be donated to the village as a resource or can be sold on the marketplace. It has many uses. The higher your woodcutting the level the higher the success chance of cutting the tree is. The Woodcutting potion created using the Alchemy skill gives the player a buff to the mining skill providing experience boosts for a period of time. The player can acquire buffs for all of their skills and most of these are created in Alchemy.

#### Willow Tree

![Willow Tree](../img/willow.png)

    id: 2,
    name: 'Willow Tree',
    examine: 'A Willow tree, provides Willow Logs.',
    LevelRequirement: 15,
    BaseExperiencePerAction: 30,
    BaseActionTime: 10,
    drops: '1x Willow log',
    succRate: 67,
    type: 'solo',
    tool: 'Oak Axe',

The Willow tree is the second woodcutting activity the player can do. It generates the Willow log resource which is a valuable component. It can be donated to the village supply, used in a number of artisan skills or can be sold to the marketplace or other players.

#### Pine Tree

![Pine Tree](../img/pine.png)

    id: 3,
    name: 'Pine Tree',
    examine: 'A Pine tree, provides Pine Logs.',
    LevelRequirement: 30,
    BaseExperiencePerAction: 65,
    BaseActionTime: 10,
    drops: '1x Pine log',
    succRate: 67,
    type: 'solo',
    tool: 'Willow Axe',

The Pine tree is the third woodcutting activity the player can do. It generates the Pine log resource which isn't very useful, it does however provide very good experience. It cannot be donated to the village supply, it can however be sold on the marketplace to players or to an NPC.

#### Mahogany Tree

![Mahogany Tree](../img/mahogany.png)

    id: 4,
    name: 'Mahogany Tree',
    examine: 'A Mahogany tree, provides Mahogany Logs.',
    LevelRequirement: 50,
    BaseExperiencePerAction: 43,
    BaseActionTime: 8,
    drops: '1x Mahogany log',
    succRate: 67,
    type: 'solo',
    tool: 'Pine Axe',
    

The Mahogany tree is the fourth woodcutting activity the player can do. It generates the Mahogony log resource which is useful. It can be used with the foraging skill, it can also be sold on the marketplace.

#### The BloodOak Tree

![Bloodoak Tree](../img/bloodoak.png)

    id: 5,
    name: 'BloodOak Tree',
    examine: 'A BloodOak tree, you can see it rotting.',
    LevelRequirement: 67,
    BaseExperiencePerAction: 85
    BaseActionTime: 7.5,
    drops: '1x Bloodsap',
    succRate: 67,
    type: 'group',
    tool: 'Wyr Axe',

The bloodOak Tree is the fifth woodcutting activity the player can do. It is also the first group woodcutting activity. The BloodOak tree is a group activity where multiple players work together chopping the rot from the bloodOak tree. If the players chop a certain amount of rot from the BloodOak then it will spit out Bloodsap to the player. This bloodsap is a key component in wars, it is a base component in healing potions created in the Artisan Alchemy skill. Bloodsap is very valuable. It can be donated to the village supply for Village medics to heal dead villagers. Or it can be used in the Alchemy skill to create various healing items. It can also be sold on the marketplace.

### Fishing

Fishing is a gathering skill which has a max level of 99. There are multiple tiers of fish you can catch which is gated by your fishing level and your fishing rod. Some techniques may require bait purchasable from the market or gatherable from other skills namely foraging.

a tip

    You can obtain new fishing rods from the marketplace.


#### Sea Bed Foraging

    id: 1,
    name: 'Sea bed foraging',
    examine: 'Scrape along the Sea bed, see what you can find.',
    LevelRequirement: 0,
    BaseExperiencePerAction: 15,
    BaseActionTime: 10
    drops: 'Lump of Kelp',
    succRate: 67,
    type: 'solo',
    tool: 'none',
    component: 'none',

Sea Bed Foraging is the first fishing activity the player can do. It rewards XP and Kelp. Kelp is a valuable component in the Cooking and Alchemy skills and can also be given to the village supply as a donation for the Village war effort. Fish can be sold on the various marketplaces. Eating cooked Fish will heal the player and in some cases provide stat buffs and other effects.

#### Worm Fishing

    id: 2,
    name: 'Worm fishing',
    examine: 'Use a worm as bait on your rod.',
    LevelRequirement: 15,
    BaseExperiencePerAction: 30,
    BaseActionTime: 10,
    drops: 'Raw Minnow',
    succRate: 67,
    type: 'solo',
    tool: 'basic wooden rod',
    component: 'worm',

Worm Fishing is the second fishing activity the player can do. It requires a basic fishing rod which can be crafted using the Crafting skill or can be purchased from a [Village Marketplace](Market.md) or the [Global Market](Market.md). Worm fishing awards XP and the Raw Minnow fish which can be used in the Cooking skill. Cooked Minnows can be used to heal the player and are useful in early game combat.

#### Crustacean Hunting

    id: 3,
    name: 'Crustacean hunting',
    examine: 'Scrape the Sea bed again, this time stab stuff.',
    LevelRequirement: 35,
    BaseExperiencePerAction: 60,
    BaseActionTime: 10,
    drops: 'Raw Crab Claw',
    succRate: 67,
    type: 'solo',
    tool: 'makeshift spear',
    component: 'none',

Crustacean hunting is the 3rd fishing activity the player can do. It requires a Makeshift Spear which can be crafted using the Crafting skill or can be purchased from a [Village Marketplace](Market.md) or the [Global Market](Market.md).

#### Turtle Punching

    id: 4,
    name: 'Turtle Punching',
    examine: 'Sadly not that sophisticated, no weapon requirement tho',
    LevelRequirement: 55,
    BaseExperiencePerAction: 100,
    BaseActionTime: 10,
    drops: 'Raw Turtle',
    succRate: 67,
    type: 'solo',
    tool: 'none',
    component: 'none'

Turtle punching is a placeholder name. It provides XP and Raw Turtle, a valuable healing food when used with the Cooking skill. 

#### Deep Sea Diving

    id: 5,
    name: 'Deep Sea Diving',
    examine: 'Dive for sea treasures, hopefully you brought enough Air Sacs.',
    LevelRequirement: 77,
    BaseExperiencePerAction: 550,
    BaseActionTime: 35,
    drops: [rareloottable],
    succRate: 67,
    type: 'group',
    tool: 'diving suit',
    component: 'Air Sac'

Deep Sea Diving is the first Group skill activity for Fishing. This activity can only be started with a minimum of three players.
Deep Sea Diving requires a level of 77 and the player to own the Diving Suit and Air Sacs. The Diving suit is a rare drop from the Sea Horror Boss who also drops Air Sacs. Deep Sea Diving functions by 10 seconds being added for each player in the instance adding to the total Base Action Time of the skill up to a maximum of 60 seconds for 6 players. You will receive the base amount of XP once the full team has completed their action, however you will roll from the [rareloottable] each time an individual completes their action. So in a team of 6, upon completion you will have recieved the Total XP once, but a rare drop chance 6 times.