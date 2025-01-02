# Attacks & Defense

## Attacks

When a creature makes an Attack, it can do so by choosing a target within the Attack’s Range (Melee or Ranged) and by making a Check (Attack or Spell). How the Attack is resolved is determined by its Type and its Range. 

### Attack Types

There are 2 types of Attacks: Martial and Spell.

#### Martial Attacks

A creature makes a Martial Attack when it makes an Attack Check using a Weapon or Unarmed Strike against a target’s Defense.

*   **Unarmed Strike:** A Martial Attack made using any part of a creature’s own body, such as a punch, elbow, kick, knee, or headbutt.
*   **Weapon Attack:** A Martial Attack made using a Weapon, such as an Axe, Sword, or Bow. You can draw a Weapon as part of an Attack made using it.

#### Spell Attacks

A creature makes a Spell Attack when it makes a Spell Check against a target’s Defense (see “Spell Checks”).

### Attack Ranges

There are 2 types of Attack Ranges: Melee and Ranged.

#### Melee Attack

When a creature makes a Melee Attack it can do so against a target within its Melee Range. A creature’s Melee Range is 1 Space, unless otherwise stated (see "Spaces & Distance").

#### Ranged Attack

When a creature makes a Ranged Attack it can do so against a target within its Range. The Range is determined by the type of Weapon it’s Attacking with or by consulting the Feature or Spell it’s using to make the Ranged Attack.

*   **Close Quarters:** A creature has DisADV on Ranged Attacks while an enemy is within 1 Space of it, provided the enemy isn’t Incapacitated.

#### Weapon Ranges

A Weapon that can be used to make a Ranged Attack has a Range shown in parentheses after its Ammo or Thrown property (see “Weapons”).

*   **Normal Range:** The first number in the parentheses is a Weapon’s normal range. You can make an attack against any target within this range.
*   **Long Range:** The second number in the parentheses is a Weapon’s long range. You can make an attack with DisADV against targets within this range.

You can’t make attacks against targets beyond your Weapon’s long range.

> **Example:** A Short Bow has a range of (15/45), which means that they can make Attacks against targets between 1 and 20 Spaces, can make Attacks with DisADV against targets between 21 and 60 Spaces, and they can’t Attack targets that are 61 Spaces or farther away.

### Determining if an Attack Hits

When a creature makes an Attack, the result of the Attack Check or Spell Check is compared to the target’s Defense to determine whether or not the Attack hits the target. The Attack hits if the result of the Attack Check is equal to or greater than the target’s Defense.

> **Example:** A Level 4 Fighter’s highest Attribute is a 3 (Prime Modifier) and their Combat Mastery is 2 (1/2 its level). When the Fighter makes an Attack Check using a Longsword, they roll a d20 and add 5 (2+3). If they roll a 10 on the d20, the result is 15 (10 + 5). If the target’s Physical Defense is 15 or lower, the Attack hits, otherwise it misses.

## Defenses

Creatures have 2 types of Defense: Physical Defense and Mystical Defense. Each type of Defense has a value that represents how difficult it is to hit a target.

When a creature makes an Attack Check or Spell Check (see "attack check") to attempt to deal damage to a target, the creature’s Check is compared against the target’s Defense to determine if the Attack hits the target.

> **DC Tip:** Below are the 2 different types of Defense and which damage types usually target them. There can be unique instances where a damage type targets a different defense than usual, but each ability will always say which type of Defense it targets.

### Physical Defense

Physical Defense (PD) represents the difficulty of hitting a creature with physical or elemental attacks that affect the body, such as:

> **Example:** Being hit by a Weapon, burnt by a Fireball, or struck by a toxic needle.

*   Bludgeoning
*   Cold
*   Corrosion
*   Fire
*   Lightning
*   Piercing
*   Poison
*   Slashing

#### Physical Defense Formula

A Characters Physical Defense can be determined by their Base Defense, Combat Mastery, Agility, Armor Bonus (if applicable), and if they’re wielding a Shield.

*   **Base of 8:** A character starts off with a base PD of 8, which is what a typical Commoner’s PD would be.
*   **Combat Mastery:** The character adds its Combat Mastery to account for how experienced it is at protecting itself from danger in combat. Unless a creature has Mastery in Heavy Armor, it doesn’t add its Combat Mastery to its PD while wearing Heavy Armor.
*   **Agility Attribute:** A character adds its Agility to its PD to account for how well it can dodge attacks.
*   **Armor Bonus:** A character wearing Armor adds the Armor Bonus granted by its Armor.

**Physical Defense Formula:**

```
8 + Combat Mastery + Agility + Armor Bonus
```

> **DC Tip:** The Armor Bonus for Novice Armor at Level 1 is +1.

#### Shields

A character wearing a Shield adds the Shield Bonus granted by its Shield to any Physical Defense formula it’s using.

### Mystical Defense

Mystical Defense (MD) represents the difficulty of hitting a creature with supernatural sources of damage that affect the mind or soul, such as:

> **Example:** A psychic assault on your mind, seared by divine light, or withered by unholy magic.

*   Psychic
*   Radiant
*   Sonic
*   Umbral

#### Mystical Defense Formula

A creature’s MD can be determined by its Combat Mastery, Charisma, and Intelligence.

*   **Base of 8:** A character starts off with a base MD of 8, which is what a typical Commoner’s MD would be.
*   **Combat Mastery:** The character adds its Combat Mastery to account for how experienced it is at protecting its mind from invasive thoughts and mind-altering effects.
*   **Attribute Scores:** A character adds its Charisma to its MD to account for how resistant it is to manipulation and its Intelligence to account for its resistance to being mentally overwhelmed.

**Mystical Defense Formula:**

```
8 + Combat Mastery + Charisma + Intelligence
```

### Damage Reduction (DR)

Damage Reduction (DR) reduces the damage of an Attack by an amount equal to the DR value (minimum of 0). A Heavy Hit (5 or more over the Defense) or Critical Hit (a 20 on the d20) bypasses DR and deals full damage (see Damage section for more on Heavy and Critical Hits).

There are 2 types of Damage Reduction:

*   **Physical Damage Reduction:** PDR protects you from the following damage types: Bludgeoning, Cold, Corrosion, Fire, Lightning, Piercing, Poison, and Slashing.
*   **Mystical Damage Reduction:** MDR protects you from the following damage types: Psychic, Radiant, Sonic, and Umbral.

> **Example:** A creature makes an Attack Check to hit a target with a PD of 10. The result of their Attack Check is 12, which hits the target. The target has a PDR of 3, reducing the damage taken by 3. Alternatively, if the result of the Attack Check was 15, it would be 5 over the target’s PD of 10, making it a Heavy Hit. In this scenario, the PDR is bypassed and doesn’t reduce the damage. 
