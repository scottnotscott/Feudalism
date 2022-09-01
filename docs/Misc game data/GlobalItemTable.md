# Global Item Table

```js
export const globalItemTable = [{
    id: 1,
    name: 'Iron Sword',
    rarity: 'common',
    type: 'mainhandWeapon',
    stats: {
        melee: 10,
        strength: 5
    },
    statRequired: {
        melee: 5
    }
},
{
    id: 2,
    name: 'Health Potion (sm)',
    rarity: 'common',
    type: 'consumable',
    stats: {
        health: 100
    },
    usable: true
},
{
    id: 3,
    name: 'Iron Helmet',
    rarity: 'common',
    type: 'head',
    stats: {
        physicalDefence: 6,
        magicDefence: 3,
        rangedDefence: 6
    },
    statRequired: {
        physicalDefence: 5
    }
},
{
    id: 4,
    name: 'Ancestry Scroll',
    rarity: 'mythic',
    type: 'consumable',
    usable: true,
    tradable: false
}
]
```