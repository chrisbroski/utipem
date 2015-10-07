# Utipem

RPG system designed to start fast and play easily

## Purpose

What are the simplest rules required for role-playing games? All systems I have worked with either go overboard with simulation rules, requiring too much effort for character creation and adventuring, or eschew rules completely, leaving the fate of the players entirely in the hands of the GM. **Utipem** is a project to search for minimal rules of tabletop RPGs that can be understood by new players as easily as an average commercial board game.

## Core Rules

**Utipem** is based on cards. This allows the GM to easiy create any subset of all rules for their adventures, and players to only need to focus on what pertains to their characters. Magic the Gathering has shown us that an immensely complex game can be made manageable with a core rule set augmented by instructions clearly explained on each card.

### Character Card

There are no "stats", "abilities" or other types of inherent attributes on the character card, only descriptive information. The GM could enforce standard information for all characters such as race, age, height, gender and other obvious physical traits. The only piece of information required by the core rules of Utipem is that a character have a unique (meaning no other character in the adventure has it, not that it is weird) name.

The only other requirement for a player to start is to select training in a number of level I skills (typically 5.)

Notes may also need to be kept about a character's possessions and injuries.

### Turns

The opportunity to take a turn is given to all player characters first, except in the event of an undetected surprise. Once all players have attempted a skill, moved position, or passed their turn, non player characters may act at the GM's discretion. Skills that can be attempted in a turn are defined on each character's skill cards. Certain actions may trigger immediate types of responses such as dodging, parrying, or counter-attacking.

### Encounters

A situation that requires the players to take turns using skills to solve a problem is called an encounter. It ends when when the problem is resolved or all attempts fail and the players give up.

### Adventures

An adventure is a series of possible encounters created by the GM to form the basis of an interactive story. They may be as small as a handful of encounters, or as big as the GM and players have time for.

### Skill Cards

The main mechanic of Utipem (and where it derives the name) is the skill card. These cards can be added to a character at any time except during an active encounter. The effects of these can vary widely, but how they are acquired and developed stays the same.

#### Acquiring Skill Cards

New skills can be learned from a player or non-player character with expertise in that skill at a *professional* level or higher. Typically, this will take about a day's worth of training and some compensation to the trainer. Some skills can also be attempted without training, but at a lower success rate.

#### Skill Attempts

Attempting a skill takes one turn (unless otherwise noted.) Success at most skill attempts require rolling a certain number or higher with 2 6-sided dice (2d6.) Some skills give bonuses or penalties to other die rolls.

#### Dependent Skills

Some skills (typically labelled level II and II) have a training dependence: another skill must have expertise at a minimum of intermediate level in order to advance. Dependent skills only apply to one skill, but can be trained multiple times.

#### Expertise Levels

A Skill has a maximum of 6 levels of expertise with standard methods of increasing these levels.

##### Untrained

The lowest level of expertise is attempting a skill without any prior training. Any character with the essential prerequisites can attempt any skill at this level. Attempting a level II untrained skill without the proper training prerequisite subtracts 1 point from the attempt roll. Attempting a level III will penalize the attempt roll by 2 points.

##### Trained

This level is better that untrained, but not much. The character has no real experience. Skills can reach this level by receiving training with a character of *professional* level or higher. A character can also advance to this level from *untrained* by meeting the skill's training prerequisites and successfully performing the skill during an encounter at its untrained level. This must be a real, planned encounter in the adventure, not a staged practice encounter arranged by the players for the purpose of training.

##### Intermediate

Like promotion from *untrained* to *trained*, this skill level is attained when a character successfully performs a trained skill during a true encounter. 

##### Professional

Some skills require expertise in another skill at *intermediate* level or better. Having one dependent skill at *intermediate* level will promote the prerequisite skill to the *professional* level.

##### Expert

To have an *expert* level skill, a skill needs two dependent skills, at least one at *professional* level.

##### Master

To elevate to *master* expertise, a character needs at least three dependent skills, with at least one at *expert* level.

#### Card Information

All skill cards must include:

1. A unique name for the skill
2. A type, such as weapon, magic, armor, movement, awareness, etc.
3. A level representing how many lower level dependencies are required. I - III
4. A description of its effects
5. A table of effects at each level for at least *untrained*, *trained* and *intermediate* expertise levels.
6. A space after *trained* and *intermediate* to document the success of a skill during an encounter for the date and initials of the supervising GM.
7. Prerequisites to attempt, if any (typically a piece of equipment)
8. Prerequisites to train, if any (usually a more basic type of training)

#### Example Card

```
Short Sword                                Weapon I  
Inflict slashing damage to a random anatomy.
Engages with target character.
Target allowed defensive maneuver.

U: 9
T: 8 _____
I: 7 _____
P: 6
E: 5
M: 4

Attempt prereq: Short sword in hand
```

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

Moving or attempting a skill that targets another while engaged grants the engaged character one free skill attempt targeting you.

## Combat

The above rules should complete all basic rules needed to play in the Utipem system. They don't yet, because this is a work in progress, but they should. All the GM needs to do is create their adventure and skill cards. Skills can be anything depending on the setting. I am going to start with example skills based on medieval combat, which include the Short Sword skill card above.

### Random Anatomy

To understand the Weapon type cards, the first thing I must specify is how to determine a random body type. Simply roll a 6-sided die.

#### Humanoid creatures

1. Head
2. Chest
3. Right arm
4. Left arm
5. Right leg
6. Left leg

#### Quadrupeds

1. Head
2. Chest
3. Chest
4. Abdomen
5. Abdomen
6. Leg

### Damage

There are no hit points in Utipem. You can't survive being cut in two with a battle-axe just because you have experience in that sort of thing. If you get a sword through your face, you die. I don't care how many kobolds you've slain.

Standard damage, like random anatomy, is determined by a 6-sided die.

1. (or less) None
2. 'Tis but a scratch
3. It's only a flesh wound
4. That's gonna leave a mark
5. Mortally wounded
6. (or more) Severed/pulverized/destroyed oh god the humanity

Effects vary by what body part was targeted, but in general, here is what they mean:

#### None

Nothing but the memory of how lucky you were.

#### 'Tis But a Scratch

No effects other than the ability to claim you were injured in battle, and for you team members to tease you about how minor your injury was.

#### It's Only a Flesh Wound

This is going to need attention as soon as possible so it doesn't turn nasty. But a little cleaning and bandaging will fix it right up. (Successful field dressing.) If not, roll a 6-sided die 24 hours later. If it is less than 3, it elevates to a level 4 injury.

#### That's Gonna Leave a Mark

Touché! A solid hit that the character will feel. It will need attention like level 3, but probably requires stiches in addition to the bandage. It will also have effects that are immediate and ongoing depending on the part of the anatomy that was damaged.

* Head: All skills at -1 for 7 days. Permanent scar.
* Chest/Abdomen: All skills at -1 for 7 days. Knocked to the ground.
* Arms: -1 to all skills using the arm for 7 days (additive with head/chest injuries)
* Legs: -1 to all movement skills for 7 days (additive for each leg and head/chest injuries)

These require medical attention. (Successful field dressing.) If none is given, roll a 6-sided die after 24 hours. If it is less than 4, it elevates to a level 5 injury.

For each day that the injured body part is rested, it reduces the duration of the skill penalty by one day.

#### Mortally Wounded

If a mortally wounded character does not receive medical attention soon after the encounter ends, that character will bleed out and die.

All function in the injured anatomy is temporarily lost. If the head or chest is injured, the character is unconscious. If an arm is injured, no skills requiring that arm may be attempted. If the abdomen or a leg is injured, characters cannot move or stand on their own. This effect lasts for 7 days, minus each day of rest. Head and chest injuries don't leave the character in a coma that entire time. After given medical attention, they can speak and drink fluids, but are otherwise incapacitated.

If the mortally wounded character does not receive at least two days of rest, roll a 6-sided die. On a 1 or 2, they die.

#### Annihilated

If a character has a level 6 injury to the head, chest, or abdomen, there's only one thing you can do: go through his clothes and look for loose change. If it happens to an appendage (an arm or leg) the character is lucky because peg legs and hook hands are really in this season. Like #5, major injuries to the extremities need immediate attention or the character will die from blood loss. After a week of rest, the character can get back in the action minus some permanent effects. -2 to all movement skills for each wooden leg, and complete loss of function to missing arms. On the bright side, any further damage to prosthetic limbs won't hurt at all.

### Engagement

If a character attempts a skill on a target character that requires contact, both characters become engaged.

#### Disengaging

If either character attempts a skill that targets a character other than the one they are engaged with, after that skill attempt is completed, the engaged character gets to attempt a skill that targets the character that just broke engagement in addition to the skill allowed on their normal turn. They are no longer considered engaged with the original character (and may be engaged with a new target.)

Some skills grant disengagement. When disengaged by a successful skill attempt, no penalty skill is given to the previously engaged character.

## Basic Skills for a Non-Magical Medieval Campaign

A fantasy campaign without magic seems a little boring, but it should still be playable.

### Player cards

Sticking with the cards theme, we could start our players off with blank character cards plus the basic rules. This page is probably easier to handle if it is not cut up into individual cards.

[Player Cards](player.html)

### Weapons

[A small collection of basic weapons](weapons1.html)

Some weapons have additional effects on certain damage rolls. These effects happen on either natural or modified damage results. Check to see if the effect applies to the original result of the die roll, and again after all penalties and bonuses to the roll have been applied.

[Other combat skills](combat.html)

Established weapons and armor shops will offer training in most of their products. If you find something on your own or buy from a seedy second-hand vendor, you will have to figure out how to use equipment through trial-and-error.

[Armor and defensive skills](defense.html)

If you want to stay alive long enough to have a story, you will need to take measures to prevent and reduce injuries. Armor and dodging are effective but different ways to stay alive during combat.

[Medical and awareness skills](medaware.html)

Somebody in your group should know how to patch up a wound. For success, it can be advantageous to use your mind as well as your sword arm.
