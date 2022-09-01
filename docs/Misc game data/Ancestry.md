# Ancestry

Ancestry is a something each character is created with at random.
There is a large table of possible ancestry each providing unique gameplay elements to each player. Ancestry have tiers from [ D -> S ] with S being considered highest tier and D being the lowest. It's possible to not have an ancestry at all. However their are points in the game where you will gain an opportunity to try your luck at getting one.

Here's some ancestry data we have so far:

```js
export const ancestry = [{
        id: 1,
        name: "Demon Parade",
        rarity: 'mythic',
        abilities: [{
            ability_id: 33,
            name: 'Demonic Presence',
        }],
        benefits: [{
            health_regen: 15
        }]
    },
    {
        id: 2,
        name: "Blood Enchanted Eyes",
        rarity: 'mythic',
        abilities: [{
                ability_id: 34,
                name: 'Mind Trick',
            },
            {
                ability_id: 35,
                name: "Demonic Torture"
            }
        ],
        benefits: [{
            health_regen: 10
        }]
    },
    {
        id: 3,
        name: "Aura Weaver",
        rarity: 'mythic',
        abilities: [{
                ability_id: 36,
                name: 'Aura of Protection',
            },
            {
                ability_id: 37,
                name: 'Aura of Power'
            }
        ],
        benefits: [{
            health_regen: 8
        }]
    },
    {
        id: 4,
        name: 'Skybreak Dragon',
        rarity: 'mythic',
        abilities: [{
                ability_id: 38,
                name: 'Dragon Symbol X: Engulf',
            },
            {
                ability_id: 39,
                name: 'Dragon Symbol Y: Breach',
            },
            {
                ability_id: 40,
                name: 'Dragon Symbol Z: Breath'
            }
        ],
        benefits: [{
            health_regen: 5
        }]
    },
    {
        id: 5,
        name: 'Extinction Herald',
        rarity: 'mythic',
        abilities: [{
                ability_id: 41,
                name: 'Incite Fear',
            },
            {
                ability_id: 42,
                name: 'Existential Dread',
            },
            {
                ability_id: 43,
                name: 'Ego Death',
            }
        ],
        benefits: [{
            health_regen: 3
        }]
    },
    {
        id: 6,
        name: 'Bloodsapped Phoenix',
        rarity: 'mythic',
        abilities: [{
                ability_id: 44,
                name: 'Phoenix\'s Fury',
            },
            {
                ability_id: 45,
                name: 'Phoenix\'s Flight',
            },
            {
                ability_id: 46,
                name: 'Phoenix\'s Rebirth'
            }
        ],
        benefits: [{
            health_regen: 2
        }]
    },
    {
        id: 7,
        name: 'Solar Soul',
        rarity: 'legendary',
        abilities: [{
                ability_id: 47,
                name: 'Solar Flare',
            },
            {
                ability_id: 48,
                name: 'Solar Flare',
            },
            {
                ability_id: 49,
                name: 'Solar Flare'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 8,
        name: 'Frostborn',
        rarity: 'legendary',
        abilities: [{
                ability_id: 50,
                name: 'Frostbite',
            },
            {
                ability_id: 51,
                name: 'Frostbite',
            },
            {
                ability_id: 52,
                name: 'Frostbite'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 9,
        name: 'Skull Collector',
        rarity: 'legendary',
        abilities: [{
                ability_id: 53,
                name: 'Skull Collector',
            },
            {
                ability_id: 54,
                name: 'Skull Collector',
            },
            {
                ability_id: 55,
                name: 'Skull Collector'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 10,
        name: 'Flesh Eater',
        rarity: 'legendary',
        abilities: [{
                ability_id: 56,
                name: 'Flesh Eater',
            },
            {
                ability_id: 57,
                name: 'Flesh Eater',
            },
            {
                ability_id: 58,
                name: 'Flesh Eater'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 11,
        name: 'Serpentine',
        rarity: 'epic',
        abilities: [{
                ability_id: 59,
                name: 'Constricting Tendrils',
            },
            {
                ability_id: 60,
                name: 'Constricting Tendrils',
            },
            {
                ability_id: 61,
                name: 'Constricting Tendrils'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 12,
        name: 'Swift Mind',
        rarity: 'epic',
        abilities: [{
                ability_id: 62,
                name: 'Swift Mind',
            },
            {
                ability_id: 63,
                name: 'Swift Mind',
            },
            {
                ability_id: 64,
                name: 'Swift Mind'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 13,
        name: 'Flesh Eater_2',
        rarity: 'epic',
        abilities: [{
                ability_id: 65,
                name: 'Flesh Eater',
            },
            {
                ability_id: 66,
                name: 'Flesh Eater',
            },
            {
                ability_id: 67,
                name: 'Flesh Eater'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 14,
        name: 'Elemental Guardian',
        rarity: 'rare',
        abilities: [{
                ability_id: 68,
                name: 'Elemental Guardian',
            },
            {
                ability_id: 69,
                name: 'Elemental Guardian',
            },
            {
                ability_id: 70,
                name: 'Elemental Guardian'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 15,
        name: 'Elemental Guardian_2',
        rarity: 'rare',
        abilities: [{
                ability_id: 71,
                name: 'Elemental Guardian',
            },
            {
                ability_id: 72,
                name: 'Elemental Guardian',
            },
            {
                ability_id: 73,
                name: 'Elemental Guardian'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 16,
        name: 'Time Splitter',
        rarity: 'uncommon',
        abilities: [{
                ability_id: 74,
                name: 'Time Splitter',
            },
            {
                ability_id: 75,
                name: 'Time Splitter',
            },
            {
                ability_id: 76,
                name: 'Time Splitter'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
    {
        id: 17,
        name: 'Time Splitter_2',
        rarity: 'uncommon',
        abilities: [{
                ability_id: 77,
                name: 'Time Splitter',
            },
            {
                ability_id: 78,
                name: 'Time Splitter',
            },
            {
                ability_id: 79,
                name: 'Time Splitter'
            }
        ],
        benefits: [{
            health_regen: 1
        }]
    },
]
```