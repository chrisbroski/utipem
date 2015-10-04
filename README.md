# Utipem

RPG system designed to start fast and play easily

## Purpose

What are the simplest rules required for role-playing games? All systems I have worked with either go overboard with simulation rules, requiring too much effort for character creation and adventuring, or eschew rules completely, leaving the fate of the players entirely in the hands of the GM. **Utipem** is a project to search for minimal rules of tabletop RPGs that can be understood by new players as eaily as an average commercial board game.

## Core Rules

**Utipem** is based on cards. This allows the GM to easiy create any subset of all rules for their adventures, and players to only need to focus on what pertains to their characters. Magic the Gathering has shown us that an immensely complex game can be made managable with a core rule set augmented by instructions clearly explained on each card.

### Character Card

There are no "stats", "abilities" or other types of inherent attributes on the character card, only descriptive information. The GM could enforce standard information for all characters such as race, age, height, gender and other obvious physical traits. The only piece of information required by the core rules of Utipem is that a character have a unique (meaning no other character in the adventure has it, not that it is weird) name.

The only other requirement for a player to start is to select training in a number of level I skills (typically 5.)

Notes may also need to be kept about a characters possessions and injuries.

### Turns

The opportunity to take a turn is given to all player characters first, except in the event of an undetected surprise. Once all players have attempted a skill, moved position, or passed their turn, non player characters may act at the GM's discretion. Skills that can be attempted in a turn are defined on each character's skill cards. Certain actions may trigger immediate types of responses such as dodging, parrying, or counter-attacking.

### Encounters

A situation that requires the players to take turns using skills to solve a problem is called an encounter. It ends when when the problem is resolved or all attempts fail and the players give up.

### Adventures

An adventure is a series of possible encounters created by the GM to form the basis of an interactive story. They may be as small as a handful of encounters, or as big as the GM and players have time for.

### Skill Cards

The main mechanic of Utipem (and where it derives the name) is the skill card. These cards can be added to a character at any time except during an active encounter. The effects of these can vary widely, but how they are acquired and developed stays the same.

#### Acquiring Skill Cards

New skills can be learned from a player or non-player character with expertise in that skill at a *professional* level or higher. Typically this will take about a day's worth of training and some compensation to the trainer. Some skills can also be attempted without training, but at a lower success rate.

#### Expertise Levels

A Skill has a maximum of 6 levels of expertise with standard methods of increasing these levels.

##### Untrained

The lowest level of expertise is attempting a skill without any prior training. Any character with the essential prerequisites can attempt any skill at this level.

##### Trained

This level is better that untrained, but not much. The character has no real experience. Skills can reach this level by receiving training with a character of *professional* level or higher. A character can also advance to this level from *untrained* by possessing training prequesites and successfully performing the skill during an encounter. This must be a planned encounter in the adventure, not a staged practice encounter arranged by the players for the purpose of training.

##### Intermediate

Like promotion from *untrained* to *trained*, this skill level is attained when a character successfully performs a trained skill during a true encounter. 

##### Professional

Some skills require expertise in another skill at *intermediate* level or better. Having one dependant skill at *intermediate* level will promote the prerequisite skill to the *professional* level.

##### Expert

To have an *expert* level skill, a skill needs two dependant skills, at least one at *professional* level.

##### Master

To elevate to *master* expertise, a character needs at least three dependant skills, with at least one at *expert* level.

#### Card Information

All skill cards must include:

1. A unique name for the skill
2. A type, such as weapon, magic, armor, movement, etc.
3. A level representing how many lower level dependencies are required. I - III
4. A description of its effects
5. A table of effects at each level for at least *untrained*, *trained* and *intermediate* expertise levels.
6. A space after *trained* and *intermediate* to document the success of a skill during an encounter for the date and initials of the supervising GM.
7. Prerequisities to attempt, if any (typically a piece of equipment)
8. Prerequisites to train, if any (usually a more basic type of training)

#### Example Card

    Short Sword  
    Weapon (slashing) I  
    On >= 2d6, deal target damage to a random anatomy.  
    Target receives opportunity for a defensive maneuver.
    
    U: 9
    T: 8 _____
    I: 7 _____
    P: 6
    E: 5
    M: 4
    
    Attempt prereq: Short sword in hand

Damage and random anatomy will be explained below.

### Movement and Distance

There are no maps or miniatures in Utipem. There are five general types of distances:

1. **Far away** - So far away that nothing can be seen (At another location, somewhere else, back at the ranch, etc.)
2. **Distant** - Large objects can be seen without detail (In the distance, across the way, just outside, etc.)
3. **Medium** - People can be seen clearly, but not interacted with without yelling or throwing something. (In the room, within earshot, etc.)
4. **Close** - At a comfortable talking distance. A quick movement can put the two in contact distance.
5. **Engaged** - Things are in contact, wrestling, whispering, etc.

One turn of movement can change the distance between a character and a target by one level, with the exception of far away. That will depend on how far away they are.

It also takes one movement turn to stand from lying or sitting on the ground. 

## Combat

The above rules should complete all basic rules needed to play in the Utipem system. They don't yet, because this is a work in progress, but they should. All the GM needs to do is create their adventure and skill cards. Skills can be anything depending on the setting. I am going to start with example skills based on medieval combat, which include the Short Sword skill card above.

### Random Anatomy

To understand the Weapon type cards, the first thing I must specify is how to determine a random body type. Simply roll a 6-sided die.

1. Head
2. Chest
3. Right arm
4. Left arm
5. Right leg
6. Left leg

### Damage

There are no hit points in Utipem. You can't survive being cut in two with a battle-axe just because you have experience in that sort of thing. If you get a sword through your face, you die. I don't care how many kobolds you've slain.

Standard damage, like random anatomy, is determined by a 6-sided die.

1. (or less) None
2. 'Tis but a scratch
3. It's only a flesh wound
4. That's gonna leave a mark
5. Mortally wounded
6. (or more) Severed/pulverized/destroyed oh god the humanity

Effects vary by what body part was targetted, but in general, here is what they mean:

#### None

Nothing but the memory of how lucky you were.

#### 'Tis But a Scratch

No effects other than the ability to claim you were injured in battle, and for you team members to tease you about how minor your injury was.

#### It's Only a Flesh Wound

This is going to need attention as soon as possible so it doesn't turn nasty. But a little cleaning and bandaging will fix it right up. (Successful field dressing.) If not, roll a 6-sided die 24 hours later. If it is less than 3, it elevates to a level 4 injury.

#### That's Gonna Leave a Mark

Touche! A solid hit that the character will feel. It will need attention like level 3, but probably requires stiches in addition to the bandage. It will also have effects that are immediate and ongoing depending on the part of the anatomy that was damaged.

* Head: All skills at -1 for 7 days. Permanent scar.
* Chest: All skils at -1 for 7 days. Knocked to the ground.
* Arms: -1 to all skills using the arm for 7 days (additive with head/chest injuries)
* Legs: -1 to all movement skills for 7 days (additive for each leg and head/chest injuries)

These require medical attention. (Successful field dressing.) If none is given, roll a 6-sided die after 24 hours. If it is less than 4, it elevates to a level 5 injury.

For each day that the injured body part is rested, it reduces the duration of the skill penalty by one day.

#### Mortally Wounded

If a mortally wounded character does not receive medical attention soon after the encounter ends, that character will bleed out and die.

All function in the injured anatomy is temporarily lost. If the head or chest is injured, the character is unconscious. If an arm is injured, no skills requiring that arm may be attempted. If a leg is injured, characters cannot move or stand on their own. This effect lasts for 7 days, minus each day of rest. Head and chest injuries don't leave the character in a coma that entire time. After given medical attention, they can speak and drink fluids, but are otherwise incapacitated.

If the mortally wounded character does not receive at least two days of rest, roll a 6-sided die. On a 1 or 2, they die.

#### Annihilated

If a character has a level 6 injury to the head or chest, there's only one thing you can do: go through his clothes and look for loose change. If it happens to an appendage, the character is lucky because peg legs and hook hands are really in this season. Like #5, major injuries to the extremities need immediate attention or the character will die from blood loss. After a week of rest, the character can get back in the action minus some permanent effects. -2 to all movement skills for each wooden leg, and complete loss of function to missing arms. On the bright side, any further damage to prosthetic limbs won't hurt at all.

### More Weapons

Now that we know more about how combat works, let's design some skill cards.

```
Dagger
Weapon (pierce) I
On >= 2d6, deal target damage - 1 to a random anatomy.  
Target receives opportunity for a defensive maneuver.
Common, useful, and easy to conceal

U: 9
T: 8 _____
I: 7 _____
P: 6
E: 5
M: 4

Attempt prereq: Dagger in hand
```

```
Mace
Weapon (bash) I
On >= 2d6, deal target damage to a random anatomy.  
Target receives opportunity for a defensive maneuver.

U: 9
T: 8 _____
I: 7 _____
P: 6
E: 5
M: 4

Attempt prereq: Mace in hand
```

```
Spear
Weapon (pierce) I
On >= 2d6, deal target damage to a random anatomy.  
Target receives opportunity for a defensive maneuver.

U: 9
T: 8 _____
I: 7 _____
P: 6
E: 5
M: 4

Attempt prereq: Spear in both hands
```

```
Bow and Arrow
Weapon (pierce) I
On >= 2d6, deal target damage to a random anatomy.  
Target receives opportunity for a defensive maneuver.  
Cannot parry except with shield
Can attack from medium range
Misses on an engaged target hits the other character

U: 9
T: 8 _____
I: 7 _____
P: 6
E: 5
M: 4

Attempt prereq: Bow in both hands with arrow
```

```
Longsword
Weapon (slash) II
On >= 2d6, deal target damage to a random anatomy.  
Damage is determined by the higher of two die rolls.
Target receives opportunity for a defensive maneuver.
+1 to parry

U: 9
T: 8 _____
I: 7 _____
P: 6
E: 5
M: 4

Attempt prereq: Longsword in hand
Train prereq: Short sword at intermediate expertise
```

### Armor

Now that we know about the sort of insane damage these weapon can do, let's see what can be done to prevent it.

```
Leather and Chain Helmet
Armor I
-1 damage to head
-2 damage from slashing weapons
-1 to awareness skills
Success = any head damage

U: on 5 or 6 damage, knocked out 1 turn
T: on 5 or 6 damage, lose next turn _____
I:  _____
P: Lose awareness penalty

Attempt prereq: Leather and chain helmet on head
```

```
Leather and Chain Breastplate
Armor I
-1 damage to chest
-2 damage from slashing weapons
Success = any chest damage

U: -1 to all skills, -2 to movement skills
T: -2 to movement skills _____
I: -1 to movement skills _____

Attempt prereq: Leather and chain breastplate worn
```

```
Metal Breastplate
Armor II
-1 damage to chest
-3 damage from slashing weapons
Success = any chest damage

U: -2 to all skills, -3 to movement skills
T: -3 to movement skills _____
I: -2 to movement skills _____

Attempt prereq: Metal breastplate worn
```

### Defensive movements

```
Dodge
Movement I
Success = Weapon strike misses

U: 10
T: 9 _____
I: 8 _____
P: 7
E: 6
M: 5
```

```
Parry
Weapon II
Success = Weapon strike misses
Applies only to a specific weapon. Must be learned separately for each weapon.

U: 10
T: 9 _____
I: 8 _____
P: 7
E: 6
M: 5

Attempt prereq: Holding any shield or weapon
Train prereq: Intermediate weapon expertise or holding shield
```

```
Shield
Armor I
Damage -1 to weilded hand
Success = parry with shield

U: -1 to parry
T: _____
I: +1 to parry _____
P: +1 to parry
E: +2 to parry
M: +3 to parry

Attempt prereq: Holding any shield
```

```
Tumble
Dodge II
Dodge and move simultaneously

U: 10
T: 9 _____
I: 8 _____
P: 7
E: 6
M: 5

Attempt prereq: Dodge intermediate
```

### Healing and Medicine

```

```
