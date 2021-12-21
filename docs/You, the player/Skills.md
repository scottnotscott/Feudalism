## Skills

### Gathering skills
Acquire resources, sell them or donate them to your village supply.

### Woodcutting

Woodcutting is a gathering skill which has a max level of 99.
There are multiple tiers of tree you can cut which are gated by your woodcutting level.
Each tree has a level requirement check and a tool requirement. 

a tip

    Obtain tools by purchasing them in the marketplace.


Skill information:

    id: 1,
    name: 'Oak Tree',
    examine: 'An Oak tree, provides Oak logs.',
    Level Requirement: 0,
    Base Experience Per Action: 15,
    Base Action Time: 10,
    drops: '1x Oak log',
    succRate: 67,
    type: 'solo',
    tool: 'Bronze Axe',

    id: 2,
    name: 'Willow Tree',
    examine: 'A Willow tree, provides Willow logs.',
    Level Requirement: 15,
    Base Experience Per Action: 30,
    Base Action Time: 10,
    drops: '1x Willow log',
    succRate: 67,
    type: 'solo',
    tool: 'Oak Axe',

    id: 3,
    name: 'Pine Tree',
    examine: 'A Pine tree, provides Pine logs.',
    Level Requirement: 30,
    Base Experience Per Action: 65,
    Base Action Time: 10,
    drops: '1x Pine log',
    succRate: 67,
    type: 'solo',
    tool: 'Willow Axe',

    id: 4,
    name: 'Mahogany Tree',
    examine: 'A Mahogany tree, provides Mahogany logs.',
    Level Requirement: 50,
    Base Experience Per Action: 43,
    Base Action Time: 8,
    drops: '1x Mahogany log',
    succRate: 67,
    type: 'solo',
    tool: 'Pine Axe',

    id: 5,
    name: 'BloodOak Tree',
    examine: 'A BloodOak tree, you can see it rotting.',
    Level Requirement: 67,
    Base Experience Per Action: 85
    Base Action Time: 7.5,
    drops: '1x Bloodsap',
    succRate: 67,
    type: 'group',
    tool: 'Wyr Axe',

#### Oak Tree

    id: 1,
    name: 'Oak Tree',
    examine: 'An Oak tree, provides Oak Logs.',
    Level Requirement: 0,
    Base Experience Per Action: 15,
    Base Action Time: 10,
    drops: '1x Oak log',
    succRate: 67,
    type: 'solo',
    tool: 'Bronze Axe',

The Oak tree is the first woodcutting activity the player can do. However it is very useful. Oak is a valuable component for the village supply. The emperor of the village can use this to provide buffs to the villagers which are useful for activities such as war or resource masses. Oak logs can be used in the crafting skill, can be donated to the village as a resource or can be sold on the marketplace. It has many uses. The higher your woodcutting the level the higher the success chance of cutting the tree is. The Woodcutting potion created using the Alchemy skill gives the player a buff to the mining skill providing experience boosts for a period of time. The player can acquire buffs for all of their skills and most of these are created in Alchemy.

#### Willow Tree

    id: 2,
    name: 'Willow Tree',
    examine: 'A Willow tree, provides Willow Logs.',
    Level Requirement: 15,
    Base Experience Per Action: 30,
    Base Action Time: 10,
    drops: '1x Willow log',
    succRate: 67,
    type: 'solo',
    tool: 'Oak Axe',

The Willow tree is the second woodcutting activity the player can do. It generates the Willow log resource which is a valuable component. It can be donated to the village supply, used in a number of artisan skills or can be sold to the marketplace or other players.

#### Pine Tree

    id: 3,
    name: 'Pine Tree',
    examine: 'A Pine tree, provides Pine Logs.',
    Level Requirement: 30,
    Base Experience Per Action: 65,
    Base Action Time: 10,
    drops: '1x Pine log',
    succRate: 67,
    type: 'solo',
    tool: 'Willow Axe',

The Pine tree is the third woodcutting activity the player can do. It generates the Pine log resource which isn't very useful, it does however provide very good experience. It cannot be donated to the village supply, it can however be sold on the marketplace to players or to an NPC.

#### Mahogany Tree

    id: 4,
    name: 'Mahogany Tree',
    examine: 'A Mahogany tree, provides Mahogany Logs.',
    Level Requirement: 50,
    Base Experience Per Action: 43,
    Base Action Time: 8,
    drops: '1x Mahogany log',
    succRate: 67,
    type: 'solo',
    tool: 'Pine Axe',
    

The Mahogany tree is the fourth woodcutting activity the player can do. It generates the Mahogony log resource which is useful. It can be used with the foraging skill, it can also be sold on the marketplace.

#### The BloodOak Tree

    id: 5,
    name: 'BloodOak Tree',
    examine: 'A BloodOak tree, you can see it rotting.',
    Level Requirement: 67,
    Base Experience Per Action: 85
    Base Action Time: 7.5,
    drops: '1x Bloodsap',
    succRate: 67,
    type: 'group',
    tool: 'Wyr Axe',

The bloodOak Tree is the fifth woodcutting activity the player can do. It is also the first group woodcutting activity. The BloodOak tree is a group activity where multiple players work together chopping the rot from the bloodOak tree. If the players chop a certain amount of rot from the BloodOak then it will spit out Bloodsap to the player. This bloodsap is a key component in wars, it is a base component in healing potions created in the Artisan Alchemy skill. Bloodsap is very valuable. It can be donated to the village supply for Village medics to heal dead villagers. Or it can be used in the Alchemy skill to create various healing items. It can also be sold on the marketplace.

### Fishing

Fishing is a gathering skill which has a max level of 99. There are multiple tiers of fish you can catch which is gated by your fishing level and your fishing rod. Some techniques may require bait purchasable from the market or gatherable from other skills namely foraging.

a tip

    You can obtain new fishing rods from the marketplace.

Skill information:

    id: 1,
    name: 'Sea bed foraging',
    examine: 'Scrape along the Sea bed, see what you can find.',
    Level Requirement: 0,
    Base Experience Per Action: 15,
    Base Action Time: 10
    drops: 'Lump of Kelp',
    succRate: 67,
    type: 'solo',
    tool: 'none',
    component: 'none',

    id: 2,
    name: 'Worm fishing',
    examine: 'Use a worm as bait on your rod.',
    Level Requirement: 15,
    Base Experience Per Action: 30,
    Base Action Time: 10,
    drops: 'Raw Minnow',
    succRate: 67,
    type: 'solo',
    tool: 'basic wooden rod',
    component: 'worm',

    id: 3,
    name: 'Crustacean hunting',
    examine: 'Scrape the Sea bed again, this time stab stuff.',
    Level Requirement: 35,
    Base Experience Per Action: 60,
    Base Action Time: 10,
    drops: 'Raw Crab Claw',
    succRate: 67,
    type: 'solo',
    tool: 'makeshift spear',
    component: 'none',

    id: 4,
    name: 'Turtle Punching',
    examine: 'Sadly not that sophisticated, no weapon requirement tho',
    Level Requirement: 55,
    Base Experience Per Action: 100,
    Base Action Time: 10,
    drops: 'Raw Turtle',
    succRate: 67,
    type: 'solo',
    tool: 'none',
    component: 'none'

    id: 5,
    name: 'Deep Sea Diving',
    examine: 'Dive for sea treasures, hopefully you brought enough Air Sacs.',
    Level Requirement: 77,
    Base Experience Per Action: 550,
    Base Action Time: 35,
    drops: [rareloottable],
    succRate: 67,
    type: 'group',
    tool: 'diving suit',
    component: 'Air Sac'

#### Sea Bed Foraging