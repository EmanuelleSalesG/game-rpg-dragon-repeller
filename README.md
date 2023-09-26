# Dragon Repeller RPG
## Overview
Dragon Repeller is a text-based RPG game developed following the Full Stack course on Free Code Academy. 
The game's objective is to defeat the dragon that is preventing people from leaving the town. Players navigate 
through different locations, make choices, and engage in combat with various monsters.

## Game Mechanics
- Player Stats
- XP: 0
- Health: 100
- Gold: 50
- Current Weapon: Stick
- Inventory: [Stick]

## Weapons
- Stick (Power: 30)
- Dagger (Power: 30)
- Claw Hammer (Power: 50)
- Sword (Power: 100)

## Monsters
- Slime (Level: 2, Health: 15)
- Fanged Beast (Level: 8, Health: 60)
- Dragon (Level: 20, Health: 300)

## Locations
1. Town Square
- Buttons: Go to store, Go to cave, Fight dragon
- Text: You are in the town square. You see a sign that says "store".
2. Store
- Buttons: Buy 10 health (10 gold), Buy weapon health (30 gold), Go to town square
- Text: You enter the store
3. Cave
- Buttons: Fight slime, Fight fanged beast, Go to town square
- Text: You enter the cave. You see some monsters.
4. Fight
- Buttons: Attack, Dodge, Run
- Text: You are fighting a monster.

## Status
1. Kill Monster
- Buttons: Go to town square, Go to town square, Go to town square
- Text: The monster screams "Arg!" as it dies. You gain experience points and find gold.
2. Lose
- Buttons: REPLAY?, REPLAY?, REPLAY?
- Text: You die!
3. Win
- Buttons: REPLAY?, REPLAY?, REPLAY?
- Text: You defeat the dragon! YOU WIN THE GAME!
4. Easter Egg
- Buttons: 2, 8, Go town square?
- Text: You find a secret game. Pick a number above. Ten numbers will be randomly chosen between 0 and 10. If the number you choose matches one of the random numbers, you win!

## Functions
`update(location)`: Update UI based on the current location.
`goTown()`: Navigate to the town square.
`goStore()`: Navigate to the store.
`goCave()`: Navigate to the cave.
`buyHealth()`: Buy health if enough gold is available.
`buyWeapon()`: Buy a weapon if enough gold is available.
`sellWeapon()`: Sell a weapon for 15 gold.
`fightSlime(), fightBeast(), fightDragon()`: Initiate fights with respective monsters.
`goFight()`: Prepare for battle by updating UI with monster details.
`attack(), dodge(), defeatMonster()`: Handle combat mechanics.
`getMonsterAttackValue(level)`: Calculate monster's attack value based on level.
`isMonsterHit()`: Determine if the player's attack hits the monster.
`lose()`: Handle player's loss.
`winGame()`: Handle player's victory.
`restart()`: Reset player's stats and return to the town square.
`easterEgg()`: Trigger the Easter egg event.
`pickTwo(), pickEight()`: Handle Easter egg number selection.


Full stack development course Free Code Camp,
Emanuelle
