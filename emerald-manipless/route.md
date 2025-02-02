:::tracker{species="Mudkip" generation=3 baseStats="[[50, 70, 50, 50, 50, 40], [70, 85, 70, 60, 70, 50], [100, 110, 90, 85, 90, 60]]"}
5: 
  6  -> 0,  0,  0,  0,  0,  2
  7  -> 0,  1,  0,  0,  0,  2
  8  -> 0,  2,  0,  0,  0,  2
  9  -> 0,  2,  1,  0,  0,  2
  10  -> 0,  2,  1,  0,  0,  2
  11  -> 0,  2,  3,  0,  0,  2
  12  -> 0,  2,  5,  0,  0,  2
  13  -> 0,  2,  6,  0,  0,  2
  14  -> 0,  2,  8,  0,  0,  2
  15  -> 0,  2,  9,  0,  0,  2
  16  -> 0,  3,  11,  0,  0,  2
  17  -> 0,  5,  11,  0,  0,  3
  18  -> 0,  5,  11,  0,  0,  5
  19  -> 0,  5,  11,  0,  0,  7
  20  -> 0,  5,  11,  1,  0,  9
  21  -> 0,  5,  11,  3,  0,  11
  22  -> 0,  5,  12,  4,  0,  13
  23  -> 1,  5,  12,  6,  0,  15
  24  -> 1,  5,  12,  6,  0,  17
  25  -> 1,  6,  15,  7,  0,  17
  26  -> 2,  6,  15,  10,  0,  17
  27  -> 2,  9,  15,  12,  0,  19
  28  -> 2,  10,  15,  15,  0,  20
  29  -> 2,  11,  17,  18,  0,  20
  30  -> 2,  11,  17,  18,  0,  20
  31  -> 3,  14,  17,  19,  0,  23
  32  -> 3,  14,  17,  20,  0,  27
  33  -> 6,  18,  17,  20,  0,  28
  34  -> 6,  18,  17,  20,  0,  28
  35  -> 6,  18,  17,  20,  0,  28
  36  -> 6,  18,  17,  20,  0,  28
  37  -> 6,  21,  19,  21,  0,  32
  38  -> 10,  22,  21,  22,  1,  33
  39  -> 10,  23,  25,  22,  3,  33
  40  -> 11,  28,  25,  25,  5,  37
  41  -> 11,  31,  25,  26,  5,  41
  42  -> 11,  37,  25,  27,  5,  46
  43  -> 11,  37,  25,  27,  5,  46
  44  -> 11,  37,  25,  27,  5,  46
  45  -> 11,  39,  25,  34,  5,  47
  46  -> 11,  41,  25,  37,  8,  48
  47  -> 11,  50,  25,  39,  9,  49
:::

:::tracker{species="Rayquaza" generation=3 baseStats="[[105, 150, 90, 150, 90, 95]]" }
70: 
  71  -> 5, 3, 2, 8, 5, 2
  72  -> 7, 14, 2, 10, 10, 3
  73  -> 18, 20, 5, 10, 12, 5
:::

# Pokémon Emerald Any% Manipless Route

**Prepared by bounxii#5939**

**Ported to Ranger by HunarPG#2786**

**Credits for these notes:**
  - **Bounxii for the original notes**

**If the route does not say to learn a move explicitly, do not learn it**

**Always delete your save (UP+B+Select on Title screen)**

**Before starting your run, make sure to set the following options:**
  - Text: Fast
  - Battle Scene: Off
  - Battle Style: SET
  - Button Mode: L=A

## Intro
  - **Pick Girl**
  - Give yourself a 1 character name
  - Hold Right to exit the truck
  - Pick PC Potion
  - Go down stairs, then visit Rival’s house, leave his room immediately, then go north for the starter
  - Save in front of the bag (one tile away also works if you move and use the bag immediately)

## Mudkip

**Minimum Requirements**
 - 13 atk, 10 spatk, 10 speed
 - 13 atk, 11 spatk, 9  speed
 - 14 atk, 10 spatk, 9  speed

Defeat Zigzagoon

Nickname your Mudkip 1 character

## Rival 1

Go north to beat Rival 1(talk to him from the left) 

:::::::trainer[Rival 1]
  :::::pokemon[Treecko]
    - Tackle spam
    ::damage[Treecko's Pound]{source="Mudkip" offensive=false movePower=40 level=5 opponentLevel=5 opponentStat=8 special=false stab=false}
  :::::
:::::::

Go south again, adjusting 1 tile right before talking to Rival in Oldale

Meet Rival at lab, then get the Running Shoes from mom (walk to the row below her then over and up to her left)
  - Can take mom heal if really low and want to play safe

Go back to Oldale and use the west exit

## Route 102

:::::::trainer[Youngster Calvin]
  :::::pokemon[Poochyena]
    :::if{source="Mudkip" condition="atk=(x / 20-26 / 0-9)"}
    - Tackle x4
    - 0% to 3HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 27-31 / 10-31)"}
    - Tackle x3(x4)
    - 84.5% to 3HKO
    :::
    ::damage[Poochyena's Tackle]{source="Mudkip" offensive=false movePower=35 level=6 opponentLevel=5 opponentStat=11 special=false stab=false type=normal}
  :::::
:::::::

Avoid the other Trainers, the Spinner can only turn right or down, go down out of the grass after her

**If you see a Level 4 Ralts or Lotad and you can survive a few hits from Lotad(Ralts only knows growl), KO it**

::variable{name="earlyexp" type="boolean" title="Did you get exp from a ralts or lotad?" defaultValue=false}

## Petalburg City

Enter Petalburg Mart

:::card{theme=neutral}
### Shopping
#### Buy:
  - 5 Potions (v)
  - 3 Repels (vvvvv)
:::

Go to the gym to help out Wally, then leave via the west exit to Route 103

## Route 103 and Petalburg Forest

Walk around the grass using the beach (the Youngster is a trainer!)

Go to the upper grass on the lower half

Menu:
  - Use Potion(if low)
  - Use Repel

In the forest run manip the first trainer and follow the path

:::::::trainer[Team Aqua Grunt]
  :::::pokemon[Poochyena]
    ::::if{source="Mudkip" condition="!$earlyexp"}
    - Tackle x5
    ::damage[Poochyena's Tackle]{source="Mudkip" offensive=false movePower=35 level=7 opponentLevel=9 opponentStat=15 special=false stab=false type=normal}
    ::::
    ::::if{source="Mudkip" condition="$earlyexp"}
    - Tackle x4(x5)
    :::if{source="Mudkip" condition="atk=(x / 20-31 / 0-22)"}
    Mudkip's Tackle is 18.9% to 4HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 23-31)"}
    Mudkip's Tackle is 99.9% to 4HKO
    :::
    ::damage[Poochyena's Tackle]{source="Mudkip" offensive=false movePower=35 level=8 opponentLevel=9 opponentStat=15 special=false stab=false type=normal}
    ::::
  :::::
:::::::

Run Manip the next trainer and exit

**Grab Bullet Seed TM from the guy near berry trees**

Run Manip or just dodge the rotato, then go up the water to avoid the Lass

The double battle won’t happen, as you do not have a 2nd Pokemon yet

## Rustbro City

Head to Rustbro Gym

Go through the maze and talk to battle the first youngster

:::::::trainer[Youngster Josh]
  :::::pokemon[Geodude]
    - Mud Slap x6
    ::damage[Geodude's Tackle]{source="Mudkip" offensive=false movePower=35 level=8 opponentLevel=10 opponentStat=19 special=false stab=false type=normal}
  :::::
:::::::

:::::::trainer[Youngster Tommy]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Geodude]
    - Water Gun
  :::::
:::::::

:::::::trainer[Hiker Marc]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Geodude]
    - Water Gun
  :::::
:::::::

**Potion before Roxanne if needed**

:::::::trainer[Leader Roxanne]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Nosepass]
    :::if{source="Mudkip" condition="speed=(x / 20-31 / 5-31)"}
    - Growl if you are in range to die to Rock Tomb x2
    :::
    - Water Gun Spam
    - Heal when you die to Rock Tomb
    :::if{source="Mudkip" condition="!$earlyexp"}
    ::damage[Nosepass's Tackle]{source="Mudkip" offensive=false movePower=35 level=13 opponentLevel=15 opponentStat=24 special=false stab=false type=normal}
    ::damage[Nosepass's Rock Tomb]{source="Mudkip" offensive=false movePower=50 level=13 opponentLevel=15 opponentStat=24 special=false stab=true type=normal}
    :::
    :::if{source="Mudkip" condition="$earlyexp"}
    ::damage[Nosepass's Tackle]{source="Mudkip" offensive=false movePower=35 level=14 opponentLevel=15 opponentStat=24 special=false stab=false type=normal}
    ::damage[Nosepass's Rock Tomb]{source="Mudkip" offensive=false movePower=50 level=14 opponentLevel=15 opponentStat=24 special=false stab=true type=normal}
    :::
  :::::
:::::::

Exit the Gym and go to the left

After the cutscene run along the left wall of the gym around the corner

Talk to the Devon guy

## Saving Peeko

Repel before the grass

Avoid the rotating Bug Catcher

Run Manip the Lass

Talk to the bottom Hiker to battle him

:::::::trainer[Hiker Clark]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
:::::::

Avoid the spinner and fight the top Hiker

:::::::trainer[Hiker Devan]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Geodude]
    - Water Gun
  :::::
:::::::

Enter Rusturf Tunnel

:::::::trainer[Team Aqua Grunt]
  :::::pokemon[Poochyena]
    - Water Gun*(x2)
    ::damage[Mudkip's Water Gun in Torrent]{source="Mudkip" offensive=true movePower=40 level=15 opponentLevel=11 healthThreshold=28 special=true opponentStat=11 stab=true torrent=true type=water}
  :::::
:::::::

Exit Rusturf Tunnel

## Devon Goods

:::if{source="Mudkip" condition="!$earlyexp"}
You need to KO one Pokemon to get to Level 16 before Dewford
 - Either do it after the current repel expires
 - Or do it on Route 104(Grass after exiting Forest)
:::

Repel again when the current expires

Use the ledge to skip past the Youngster and run back

Bag manipping or pause manipping Karen and using the lower path run manip Bug Catcher Jose

Meet the Devon guy

Go through the Pokenav Tutorial

Enter the Pokemart

:::card{theme=neutral}
### Shopping
#### Sell:
  - TM 09 Bullet See
  - Tm 39 Rock Tomb

#### Buy:
  - 4 Super Potions(vv)
  - 2 Antidotes(v)
  - 2 X Speeds (vvvvv)
  - 3 X Attacks(v)
  - Max(5) Repels (^^)
:::

Go down directly talk to Rival
  - Say no to battling him(Mash B)

Go towards Briney's Cottage
  - Avoid all trainers along the way

Get beach Potion

Head to Dewford
  - Enter Pokemon Center to set death warp

Enter Granite Cave
  - Grab Escape Rope

Escape rope out after talking to Steven
  - Sail to Slateport

Get beach Revive

Get Soft Sand

Head to shipyard

Equip Soft sand after exiting shipyard
  - Go to museum and talk to Mr briney

:::::::trainer[Team Aqua Grunt]
  :::::pokemon[Carvanha]
    - Mud Shot
    :::if{source="Mudkip" condition="speed=(20-24 / 0-6 / x)"}
    - You are speed Tied
    :::
    :::if{source="Mudkip" condition="speed=(25-31 / 7-31 / 0-31)"}
    - You are faster
    :::
    ::damage[Carvanha's Bite]{source="Mudkip" offensive=false movePower=60 level=16 evolution=1 opponentLevel=15 opponentStat=24 special=true stab=true type=dark}
  :::::
:::::::

:::::::trainer[Team Aqua Grunt]
  :::::pokemon[Zubat]
    - Tackle x2
    :::if{source="Mudkip" condition="atk=(x / 20-23 / 0-4)"}
    - Marshtomp Tackle is 41.4% to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 24-31 / 5-17)"}
    - Marshtomp Tackle is 90.2% to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 18-29)"}
    - Marshtomp Tackle is 99.6% to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 30-31)"}
    - Marshtomp Tackle is 100% to 2HKO
    :::
  :::::
  :::::pokemon[Carvanha]
    - Mud Shot
  :::::
:::::::

## Rival 2

Exit Museum

Go to Route 110
  - Fight next trainers as double battle

:::::::trainer[Team Aqua Grunt]
  :::::pokemon[Plusle and Minun]
    - Mud Shot Spam
  :::::
:::::::

Before Grass
  - Repel
  - Heal above 44 HP
  - Put Cursor on X Attack

Pass the youngster
  - Grab Full Heal before Rival

:::::::trainer[Rival 2]
  :::::pokemon[Slugma]
    - X Attack x2 + X Speed + Mud Slap
    - Full Heal if burned(don't full heal if asleep)
    - Heal to survive Absorb before killing
    :::
  :::::
  :::::pokemon[Grovyle]
    - Mud Shot + Mud Shot/Tackle
    :::if{source="Mudkip" condition="atk=(x / 20-23 / 0-7)"}
    - Marshtop's Mud Shot + Tackle isn't a 100% range
    :::
    :::if{source="Mudkip" condition="atk=(x / 20-23 / 8-31)"}
    - Marshtop's Mud Shot + Tackle is a 100% range
    :::
  :::::
  :::::pokemon[Wingull]
    - Tackle(x2)
    - Can Water Gun turn 2 to avoid missing
    ::damage[Marshtomp's Tackle (+2)]{source="Mudkip" offensive=true movePower=35 level=20 evolution=1 opponentLevel=18 opponentStat=16 healthThreshold=43 combatStages=2 statModifier=1.1 special=false stab=false type=normal}
  :::::
:::::::

:::::::trainer[Triathlete Alyssa]
  :::::pokemon[Magnemite]
    - Mud-Slap / Water Gun*
    ::damage[Marshtomp's Water Gun in Torrent]{source="Mudkip" offensive=true movePower=40 level=20 evolution=1 opponentLevel=15 opponentStat=18 healthThreshold=32 torrent=true special=true stab=true type=water}
  :::::
:::::::

:::::::trainer[Psychic Edward]
  :::::pokemon[Abra]
    - Tackle / Mud-Slap
    ::damage[Marshtomp's Mud-Slap]{source="Mudkip" offensive=true movePower=20 level=20 evolution=1 opponentLevel=15 opponentStat=9 healthThreshold=32 special=false statModifier=1.1 otherPowerModifier=1.1 stab=true type=ground}
  :::::
:::::::

Grab Elixir and head to Mauville

## Mauville City

Grab HM for Rock Smash

Grab Mach Bike and Menu
  - Teach Rock Smash over Tackle
  - Register and Use Mach Bike

Go East and fight the youngster

:::::::trainer[Youngster Deadndre]
  :::::pokemon[Zigzagoon]
    - Mud Shot / Water Gun*
    ::damage[Marshtomp's Water Gun in Torrent]{source="Mudkip" offensive=true movePower=40 level=20 evolution=1 opponentLevel=14 opponentStat=16 healthThreshold=34 torrent=true special=true stab=true type=water}
  :::::
  :::::pokemon[Aron]
    - Water Gun
  :::::
  :::::pokemon[Electrike]
    - Mud Shot / Water Gun*
    ::damage[Marshtomp's Water Gun in Torrent]{source="Mudkip" offensive=true movePower=40 level=21 evolution=1 opponentLevel=14 opponentStat=16 healthThreshold=35 torrent=true special=true stab=true type=water}
  :::::
:::::::

Go towards the gym
  - Talk to fight with Wally

:::::::trainer[Rival Wally]
  :::::pokemon[Ralts]
    - Mud Shot / Water Gun*
    ::damage[Marshtomp's Water Gun in Torrent]{source="Mudkip" offensive=true movePower=40 level=21 evolution=1 opponentLevel=16 opponentStat=14 healthThreshold=35 torrent=true special=true stab=true type=water}
  :::::
:::::::

Enter the Gym

:::::::trainer[Youngster Ben]
  :::::pokemon[Zigzagoon]
    - Mud Shot(+Water Gun) / Water Gun* x2(guranteed 2HKO)
    :::if{source="Mudkip" condition="speed=(20-26 / 0-7 / x)"}
    - You are slower
    :::
    :::if{source="Mudkip" condition="speed=(27-31 / 8-12 / 0-2)"}
    - You are speed tied
    :::
    :::if{source="Mudkip" condition="speed=(x / 13-31 / 3-31)"}
    - You are faster
    :::
    ::damage[Marshtomp's Mud Shot]{source="Mudkip" offensive=true movePower=55 level=21 evolution=1 opponentLevel=17 opponentStat=22 healthThreshold=42 special=false statModifier=1.1 otherPowerModifier=1.1 stab=true type=ground}
  :::::
  :::::pokemon[Gulpin]
    - (Water Gun) + Mud Shot
    - Water gun Turn 1 if got growled
    ::damage[Marshtomp's Mud Shot(-1)]{source="Mudkip" offensive=true movePower=55 level=22 evolution=1 opponentLevel=17 opponentStat=26 healthThreshold=53 special=false statModifier=1.1 otherPowerModifier=1.1 combatStages=-1 stab=true type=ground effectiveness=2}
  :::::
:::::::

:::::::trainer[Leader Wattson]
  :::::pokemon[Voltorb]
    - X Speed + X Attack + Mud Shot
    :::if{source="Mudkip" condition="speed=(20-31 / 0-24 / 0-10)"}
    - You are slower at +1
    :::
    :::if{source="Mudkip" condition="speed=(x/ 25-28 / 11-15)"}
    - You are speed tied at +1
    :::
    :::if{source="Mudkip" condition="speed=(x/ 29-31 / 16-31)"}
    - You are faster at +1
    :::
  :::::
  :::::pokemon[Electrike]
    - Mud Shot
  :::::
  :::::pokemon[Magneton]
    - Mud Shot
    :::if{source="Mudkip" condition="speed=(x / 0-1 / x)"}
    - You are slower at +1
    :::
    :::if{source="Mudkip" condition="speed=(20-31 / 2-31 / 0-31)"}
    - You are faster at +1
    :::
  :::::
  :::::pokemon[Manectric]
    - Mud Shot(x2)
    :::if{source="Mudkip" condition="speed=(0-31 / 0-31 / 0-23)"}
    - You are slower at +1
    :::
    :::if{source="Mudkip" condition="speed=(x / x / 24-27)"}
    - You are speed tied at +1
    :::
    :::if{source="Mudkip" condition="speed=(x / x / 28-31)"}
    - You are faster at +1
    :::
    ::damage[Marshtomp's Mud Shot(+1)]{source="Mudkip" offensive=true movePower=55 level=23 evolution=1 opponentLevel=24 opponentStat=41 healthThreshold=74 special=false statModifier=1.1 otherPowerModifier=1.1 combatStages=1 stab=true type=ground effectiveness=2}
    ::damage[Manectric's Quick Attack]{source="Mudkip" offensive=false movePower=40 level=23 evolution=1 opponentLevel=24 opponentStat=52 special=false stab=false type=normal}
    ::damage[Manectric's Quick Attack(+1)]{source="Mudkip" offensive=false movePower=40 level=23 opponentCombatStages=1 evolution=1 opponentLevel=24 opponentStat=52 special=false stab=false type=normal}
  :::::
:::::::

## Route 111

Exit the gym
  - Head to Route 111(North)

Grab this Elixir

Use Rock Smash to break the rocks

Head North
  - Bike past the first Spinner (won’t spin yet)
  - Adjust 1 tile to the left to dodge the next one

Stop at the stone wall where pictured and Repel

Bike past the Rotato (top path) and bonk into the stairs/sign
  - Run to bike or bag manip the Hiker on the left to enter Fiery Path

After Fiery Path bag manip the double Spinners(Repel runs out in front of them)
  - And in the next Route bike south up to a rock, to reset the 3rd spinner for a load manip

Continuing north avoid CTB by biking below her 
  - Use another Repel at the start of Route 113 next to a rock where the ash grass starts

Following this path perfectly avoids all optionals without run/bag manips

## Fallarbor

Pickup this Nugget in Fallarbor

:::card{theme=neutral}
### Shopping
#### Sell:
  - 2 Elixirs
  - Nugget
  - TM 34 Shock Wave
  - TM 47 Steel Wing
#### Buy:
  - 3 Escape Rope(vvvv)
  - 16 Super Repels(v)
  - 11 X Specials(v)
  - 4-6 X Speed(v)
  - 5 X Attacks(v)
  - 2 Guard Specs(vvv)
::::

**Grab only 10 X Specials if you forgot the 2nd elixir**
**Grab only 4 X Attacks if you forgot the 2nd elixir**

:::if{source="Mudkip" condition="speed=(20-30 / 0-11 / 0)"}
**6 X Speeds(5 if you forgot the 2nd elixir)**
:::
:::if{source="Mudkip" condition="speed=(31 / 12-17 / 1-6)"}
**5 X Speeds**(4 if you forgot the 2nd elixir)
:::
:::if{source="Mudkip" condition="speed=(x / 18-31 / 7-31)"}
**4 X Speeds**
:::

Exit the Mart

## Meteor Falls

Bike towards Meteor Falls

Catch a Swablu in the grass before Meteor Falls
  - Use Water Gun to weaken
  - Use Great Ball to catch

Menu after catching it
  - Heal to full
  - Super Repel

Go up the stairs
  - Avoid the ratoto
  - Talk to fight the Hiker

:::::::trainer[Hiker Lucas]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Numel]
    - Water Gun
  :::::
:::::::

Avoid the spinner and the next trainer
  - Enter Meteor Falls

After the cutscene leave through left exit
  - Head towards Rusturf Tunnel

Break the rock smash rock to get HM for Strength
  - Grab this Max Ether

**Menu before Hiker if 0 Mud Shot PP Left**
  - Teach Strength over Mud-Slap
  - Heal to full
  - Max Ether Mud Shot

Go down to fight the Hiker

:::::::trainer[Hiker Mike]
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Geodude]
    - Water Gun
  :::::
  :::::pokemon[Machop]
    - Mud Shot
    ::damage[Marshtomp's Mud Shot]{source="Mudkip" offensive=true movePower=55 level=24 evolution=1 opponentLevel=16 opponentStat=21 healthThreshold=48 special=false statModifier=1.1 otherPowerModifier=1.1 stab=true type=ground}
  :::::
:::::::

Exit Rusturf Tunnel

## Verdanturf Town - Mount Chimney 

Head to Mauville

Menu one tile right of Mauville City Sign
  - Teach Strength over Mud-Slap
  - Heal to full
  - Use Carbos if you Grabbed it
  - Max Ether Mud Shot(if didn't use it before)
  - Super Repel

Fight the trainer just below the youngster you fought before fighting Wally

:::::::trainer[Aroma Lady Rose]
  :::::pokemon[Roselia]
    - Strength
  :::::
  :::::pokemon[Roselia]
    - Strength
  :::::
  :::::pokemon[Shroomish]
    - Strength
  :::::
:::::::

Head towards Mount Chimney
  - If got effect spored by Shroomish and no full heals enter trainer hill and heal
  - You can run here

Use Repel before smasing the rock smash rock

Go up to Mount Chimney

:::::::trainer[Magma Grunt]
  :::::pokemon[Numel]
    - Water Gun
  :::::
:::::::

:::::::trainer[Magma Grunt]
  :::::pokemon[Zubat]
    - Strength
  :::::
:::::::

:::::::trainer[Magma Admin Tabitha]
  :::::pokemon[Numel]
    - Water Gun
  :::::
  :::::pokemon[Poochyena]
    - Strength
  :::::
  :::::pokemon[Zubat]
    - Strength
    ::damage[Marshtomp's Strength]{source="Mudkip" offensive=true movePower=80 level=26 evolution=1 opponentLevel=22 opponentStat=21 healthThreshold=50 special=false statModifier=1.1 stab=false type=normal}
  :::::
  :::::pokemon[Numel]
    - Water Gun
  :::::
:::::::

Before Fighting Maxie
  - Menu to swap Swablu to slot 1

:::::::trainer[Magma Leader Maxie]
  :::::pokemon[Mightyena]
    - Guard Spec and bring Marshtomp out after swablu faints
    :::if{source="Mudkip" condition="atk=(x / 20-21 / 0-2)"}
    - Mud Shot x2
    :::
    :::if{source="Mudkip" condition="atk=(x / 21-31 / 3-13)"}
    - Mud Shot + Strength
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 14-17)"}
    - Strength x2
    - It's a 94.1% range
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 18-31)"}
    - Strength x2
    :::
  :::::
  :::::pokemon[Zubat]
    - Strength
  :::::
  :::::pokemon[Camerupt]
    - Mud Shot / Water Gun*
    ::damage[Marshtomp's Water Gun in Torrent]{source="Mudkip" offensive=true movePower=40 level=27 evolution=1 opponentLevel=25 opponentStat=47 healthThreshold=74 torrent=true special=true stab=true type=water effectiveness=4}
  :::::
:::::::

# Lavaridge Town

Head south towards Lavaridge

Go through Jagged Path follow this path

Enter Lavaridge gym and follow this path

Before Flannery
  - Swap Marshtomp to top
  - heal above 70 HP

:::::::trainer[Gym leader Flannery]
  :::::pokemon[Numel]
    - Water Gun
  :::::
  :::::pokemon[Slugma]
    - Setup to +3 to +6 with X Specials depending on torkoal ranges
    - Water Gun
    - Stall for Poison if needed
    :::if{source="Mudkip" condition="hp=(x / 0-9 / x)"}
    - Poison does 9 damage per turn
    :::
    :::if{source="Mudkip" condition="hp=(x / 10-31 / x)"}
    - Poison does 10 damage per turn
    :::
    ::damage[Marshtomp's Water Gun(+4)]{source="Mudkip" offensive=true movePower=40 level=28 evolution=1 opponentLevel=29 opponentStat=54 healthThreshold=88 torrent=false special=true combatStages=4 stab=true type=water effectiveness=2}
    ::damage[Marshtomp's Water Gun(+5)]{source="Mudkip" offensive=true movePower=40 level=28 evolution=1 opponentLevel=29 opponentStat=54 healthThreshold=88 torrent=false special=true combatStages=5 stab=true type=water effectiveness=2}
    ::damage[Marshtomp's Water Gun(+6)]{source="Mudkip" offensive=true movePower=40 level=28 evolution=1 opponentLevel=29 opponentStat=54 healthThreshold=88 torrent=false special=true combatStages=6 stab=true type=water effectiveness=2}
    ::damage[Marshtomp's Water Gun*(+3)]{source="Mudkip" offensive=true movePower=40 level=28 evolution=1 opponentLevel=29 opponentStat=54 healthThreshold=88 torrent=true special=true combatStages=3 stab=true type=water effectiveness=2}
    ::damage[Marshtomp's Water Gun*(+4)]{source="Mudkip" offensive=true movePower=40 level=28 evolution=1 opponentLevel=29 opponentStat=54 healthThreshold=88 torrent=true special=true combatStages=4 stab=true type=water effectiveness=2}
    ::damage[Marshtomp's Water Gun*(+5)]{source="Mudkip" offensive=true movePower=40 level=28 evolution=1 opponentLevel=29 opponentStat=54 healthThreshold=88 torrent=true special=true combatStages=5 stab=true type=water effectiveness=2}
  :::::
  :::::pokemon[Camerupt]
    - Water Gun
  :::::
  :::::pokemon[Torkoal]
    - Water Gun* / Water Gun
  :::::
:::::::

**Need minimum 32 HP to reach Rare Candy without fainting**

**Need minimum 18 HP to reach Camper without fainting**

Head to Lavardige Heb Shop

:::card{theme=neutral}
### Shopping
#### Buy:
  - 6 Heal Powders(vv)
  - 4 Energy Roots(^)
  - Max Energy Powders(^)
:::

Menu before Camper
  - Super Repel
  - Heal if needed

Grab Desert Candy

Bike till you whiteout

## Dewford Town

Menu:
  - Rare Candy to Level 30

:::::::trainer[Leader Brawly]
  :::::pokemon[Machop]
    - Strength
  :::::
  :::::pokemon[Meditite]
    - Strength
  :::::
  :::::pokemon[Makuhita]
    - Strength
  ::damage[Marshtomp's Strength]{source="Mudkip" offensive=true movePower=80 level=30 evolution=1 opponentLevel=19 opponentStat=22 healthThreshold=60 special=false statModifier=1.1 stab=false type=normal}
  :::::
:::::::

## Petalburg City

Head to Petalburg Gym

Go through the left door

:::::::trainer[Cool Trainer Randall]
  :::::pokemon[Swellow]
    - Strength (+Water Gun) + Strength
    :::if{source="Mudkip" condition="atk=(x / x / 0-1)"}
    - Strength is 32% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 20-24 / 2-7)"}
    - Strength is 54.7% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 25-31 / 8-11)"}
    - Strength is 77.3% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 12-17)"}
    - Strength is 90.6% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 18-21)"}
    - Strength is 98.4% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 22-31)"}
    - Strength is 100% range to 2HKO
    :::
    ::damage[Swellow's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=30 evolution=1 opponentLevel=26 opponentStat=57 special=false stab=true type=flying}
    ::damage[Swellow's Quick Attack]{source="Mudkip" offensive=false movePower=40 level=30 evolution=1 opponentLevel=26 opponentStat=57 special=false stab=true type=normal}
  :::::
:::::::

Take the left door

:::::::trainer[Cool Trainer Parker]
  :::::pokemon[Spinda]
    - Mud Shot (+Water Gun/Rock Smash if Torrent) + Mud Shot
    :::if{source="Mudkip" condition="atk=(x / 20-21 / 0-4)"}
    - Mud Shot is 32% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 22-27 / 5-11)"}
    - Mud Shot is 77.4% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 28-31 / 12-14)"}
    - Mud Shot is 90.6% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 15-31)"}
    - Mud Shot is 100% range to 2HKO
    :::
    ::damage[Spinda's Dizzy Punch]{source="Mudkip" offensive=false movePower=70 level=30 evolution=1 opponentLevel=26 opponentStat=39 special=false stab=true type=normal}
    ::damage[Spinda's Focus Punch]{source="Mudkip" offensive=false movePower=150 level=30 evolution=1 opponentLevel=26 opponentStat=39 special=false stab=false type=normal}
  :::::
:::::::

Heal to full and go to next room

:::::::trainer[Cool Trainer Jody]
  :::::pokemon[Zangoose]
    - Mud Shot (+Water Gun) + Mud Shot
    :::if{source="Mudkip" condition="atk=(x / 20-21 / 0-4)"}
    - Mud Shot is 0% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 22-27 / 5-11)"}
    - Mud Shot is 5.1% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / 28-31 / 12-14)"}
    - Mud Shot is 16.8% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 15-24)"}
    - Mud Shot is 60.5% range to 2HKO
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 25-31)"}
    - Mud Shot is 79.3% range to 2HKO
    :::
    ::damage[Zangoose's Slash]{source="Mudkip" offensive=false movePower=70 level=30 evolution=1 opponentLevel=26 opponentStat=72 special=false stab=true type=normal}
    ::damage[Zangoose's Slash(+2)]{source="Mudkip" offensive=false movePower=70 level=30 evolution=1 opponentLevel=26 opponentStat=72 opponentCombatStages=2 special=false stab=true type=normal}
    ::damage[Zangoose's Slash(+4)]{source="Mudkip" offensive=false movePower=70 level=30 evolution=1 opponentLevel=26 opponentStat=72 opponentCombatStages=4 special=false stab=true type=normal}
  :::::
:::::::

Heal to full before fithing Norman

:::::::trainer[Gym Leader Norman]
  :::::pokemon[Spinda]
    :::if{source="Mudkip" condition="atk=(x / 20-31 / 0-23)"}
    - X Attack x3
    :::
    :::if{source="Mudkip" condition="atk=(x / x / 24-31)"}
    - X Attack x4
    :::
    :::if{source="Mudkip" condition="speed=(20-27 / 0-10 / 0-1)"}
    - X Speed x1
    :::
    :::if{source="Mudkip" condition="speed=(27-31 / 11-31 / 2-31)"}
    - X Speed x1
    :::
    - (Heal Confusion +) Strength
    ::damage[Spinda's Facade]{source="Mudkip" offensive=false movePower=70 level=31 evolution=1 opponentLevel=27 opponentStat=43 special=false stab=true type=normal}
  :::::
  :::::pokemon[Vigoroth]
    - Water Gun + Strength
    ::damage[Vigoroth's Facade/Slash]{source="Mudkip" offensive=false movePower=70 level=31 evolution=1 opponentLevel=27 opponentStat=54 special=false stab=true type=normal}
  :::::
  :::::pokemon[Linoone]
    - Mud Shot / Strength
    - If you missed and Linoone use Belly Drum Strength again
    ::damage[Linoone's Facade/Slash]{source="Mudkip" offensive=false movePower=70 level=31 evolution=1 opponentLevel=29 opponentStat=57 special=false stab=true type=normal}
  :::::
  :::::pokemon[Slaking]
    - Heal Turn 1 unless you tank facade and want to risk counter
    :::if{source="Mudkip" condition="atk=(x / x / 24-31)"}
    - Mud Shot x2
    - Mud Shot is 99.6% range to 2HKO at +4
    :::
    :::if{source="Mudkip" condition="atk=(x / 20-31 / 0-23)"}
    - Rock Smash
    - If Defense Drop
      - Rock Smash + Mud Shot
    - Otherwise
      - Rock Smash
        - If Defense Drop
          - Mud Shot
        - Otherwise
          - Mud Shot x2
    :::
    ::damage[Slaking's Facade]{source="Mudkip" offensive=false movePower=70 level=32 evolution=1 opponentLevel=31 opponentStat=113 special=false stab=true type=normal}
  :::::
:::::::

Head down to Lake Candy Water

Menu:
  - Teach Surf over Water Gun
  - Super Repel
  
Get Petalburg Candy

## Ice Beam Sidetrack

Head to Oldale Town
  - Go north to Route 103 then Surf East
  - Go to Slateport and head towards Abondoned Ship

At the water Super Repel

Grab this Rare Candy below ship

Grab Storage key and head to grab TM13 Ice Beam

Menu:
  - Escape Rope
  - Super Repel
  
Surf back to Petalburg City
  - Head North to Route 110
  - Repel when previous wears off
  - Grab Route 110 Rare Candy
  - Head to Mauville City

## Weather Institute

Head East to Route 118
  - Super Repel once in water
  - Avoid Level 35 Tentacool encounter(Skill Issue)

Meet with Steven

Reach Weather Institute avoiding all the trainers

:::::::trainer[Aqua Grunt]
  :::::pokemon[Carvanha]
    - Strength / Mud Shot / Surf*
    - Strength if get out of torrent after Evolving
    :::if{source="Mudkip" condition="hp=(x / 0-28 / x)"}
    - Rough Skin does 5 damage
    :::
    :::if{source="Mudkip" condition="hp=(x / 29-31 / x)"}
    - Rough Skin does 6 damage
    :::
    :::if{source="Mudkip" condition="speed=(x / 0-1 / x)"}
    - Speed tied with Carvanha
    ::damage[Carvanha's Crunch]{source="Mudkip" offensive=false movePower=80 level=32 evolution=1 opponentLevel=28 opponentStat=45 special=true stab=true type=dark}
    :::
    :::if{source="Mudkip" condition="speed=(20-31 / 2-31 / 0-31)"}
    - Faster than Carvanha
    :::
  :::::
:::::::

Fight the right trainer after going upstrairs

:::::::trainer[Aqua Grunt]
  :::::pokemon[Zubat]
    - Surf
  :::::
  :::::pokemon[Poochyena]
    - Surf
  :::::
:::::::

:::::::trainer[Aqua Grunt]
  :::::pokemon[Poochyena]
    - Surf
  :::::
  :::::pokemon[Carvanha]
    - Strength / Mud Shot / Surf*
  :::::
:::::::

At Spinner Pass Menu:
  - Rare Candy x3 to Level 36 and evolve

:::::::trainer[Team Aqua Amin Shelly]
  :::::pokemon[Carvanha]
    - Strength / Mud Shot / Surf
    :::if{source="Mudkip" condition="hp=(x / 0-26 / x)"}
    - Rough Skin does 7 damage
    :::
    :::if{source="Mudkip" condition="hp=(x / 27-31 / x)"}
    - Rough Skin does 8 damage
    :::
  :::::
  :::::pokemon[Mightyena]
    - Surf / Surf*
    ::damage[Mudkip's Surf]{source="Mudkip" offensive=true movePower=95 level=36 evolution=2 opponentLevel=28 healthThreshold=78 special=true opponentStat=40 stab=true type=water}
  :::::
:::::::

Give Castform one character name

## Rival 3

Grab this Elixir and then Menu(Pokemon):
  - Take Soft Sand from Swampert
  - Take Mystic Water from Castform
  - Move Castform to slot 2
  
Menu(Bag):
  - Equip Mystic Water to Swampert
  - Teach Ice Beam to Swampert over Mud Shot
  - Teach Facade to Castform over Rain Dance
  - Super Repel

**PP is quite tight in this section, depending on no of protects used by Pelipper you might need to elixir early on Winnona or Mt Pyre, just keep a good eye at Surf and Ice Beam PP**

:::::::trainer[Rival 3]
  :::::pokemon[Slugma]
    :::if{source="Mudkip" condition="speed=(x / 21-31 / 7-31)"}
    - X Special + Strength(Surf if Harden)
    :::
    :::if{source="Mudkip" condition="speed=(20-31 / 0-20 / 0-6)"}
    - X Speed + X Special + Strength(Surf if Harden)
    :::
  :::::
  :::::pokemon[Grovyle]
    - Ice Beam
  :::::
  :::::pokemon[Pelliper]
    - Rock Smash + Surf or Rock Smash + Ice Beam spam(Strength + Ice Beam is guranteed)
    ::damage[Swampert's Surf*(+1)]{source="Mudkip" offensive=true movePower=95 level=36 evolution=2 opponentLevel=29 opponentStat=49 healthThreshold=77 special=true torrent=true combatStages=1 otherPowerModifier=1.1 stab=true type=water effectiveness=0.5}
    ::damage[Pelipper's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=36 evolution=2 opponentLevel=29 statModifier=1.09 opponentStat=37 special=false stab=true type=flying}
  :::::
:::::::

Head towards Fortree City

Menu before Grass:
  - Super Repel
  - Potion to High Torrent if possible

## Fortree City

Head East towards Steven
  - Run away from Kecleon and get Devon Scope

Head back to Fortree Gym

:::::::trainer[Bird Keeper Edwardo and Camper Flint]
  :::::pokemon[Swellow and Doduo]
    - Surf* + Facade Swellow
    - Always faster than Doduo
    - Always slower than Swellow
    ::damage[Swellow's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=36 evolution=2 opponentLevel=29 statModifier=1.1 opponentStat=59 special=false stab=true type=flying}
  :::::
  :::::pokemon[Xatu and Pelipper]
    - Surf* + Facade Pelipper
    - Xatu's Nght Shade does 29 HP damage
  :::if{source="Mudkip" condition="speed=(20-31 / 0-20 / 0-7)"}
    - Slower than Xatu
  :::
  :::if{source="Mudkip" condition="speed=(x / 21-31 / 8-31)"}
    - Faster than Xatu
  :::
  :::::
  :::::pokemon[Pelipper]
    - Ice Beam + Facade Pelipper
    - Always faster than Pelipper
    ::damage[Pelipper's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=36 evolution=2 opponentLevel=29 statModifier=1.1 opponentStat=39 special=false stab=true type=flying}
  :::::
:::::::

:::::::trainer[Bird Keeper Darius]
  :::::pokemon[Tropius]
    - Ice Beam
  :::::
:::::::

**Heal if low HP torrent**

:::::::trainer[Leader Winnona]
  :::::pokemon[Swablue]
    - Surf * Ice Beam
    ::damage[Swampert's Ice Beam]{source="Mudkip" offensive=true movePower=95 level=37 evolution=2 opponentLevel=29 opponentStat=55 healthThreshold=72 special=true stab=false type=ice effectiveness=2}
  :::::
  :::::pokemon[Tropius]
    - Ice Beam
  :::::
  :::::pokemon[Pelipper]
    - If Torrent
      - Rock Smash + Surf x2
      - X Special + Ice Beam x2 / Surf x2
    - **Save 1 Ice Beam PP for Altaria**
  :::if{source="Mudkip" condition="spatk=(x / 0-1 / x)"}
    - Swampert's Surf* x2 is a 94.9% range to 2HKO
  :::
  :::if{source="Mudkip" condition="spatk=(x / 2-4 / x)"}
    - Swampert's Surf* x2 is a 99.6% range to 2HKO
  ::: 
  :::if{source="Mudkip" condition="spatk=(x / 5-31 / 0-31)"}
    - Swampert's Surf* x2 is a 100% range to 2HKO 
    ::damage[Pelipper's Aerial Ace]{source="Mudkip" offensive=false movePower=60 level=38 evolution=2 opponentLevel=30 statModifier=1.1 opponentStat=37 special=false stab=true type=flying}
    ::damage[Pelipper's Water Gun]{source="Mudkip" offensive=false movePower=40 level=38 evolution=2 opponentLevel=30 opponentStat=63 special=true stab=true type=water}
  :::
  :::::
  :::::pokemon[Skarmory]
    - Surf*(x2)
    ::damage[Swampert's Surf* or Surf(+1)]{source="Mudkip" offensive=true movePower=95 level=38 evolution=2 opponentLevel=31 opponentStat=61 healthThreshold=89 special=true torrent=true stab=true otherPowerModifier=1.1 type=water}
    ::damage[Skarmory's Aerial Ace]{source="Mudkip" offensive=false movePower=60 level=38 evolution=2 opponentLevel=31 statModifier=1.1 opponentStat=55 special=false stab=true type=flying}
  :::::
  :::::pokemon[Altaria]
    - Ice Beam
  :::if{source="Mudkip" condition="speed=(20-31 / 0-21 / 0-8)"}
    - Slower than Altaria
  :::
  :::if{source="Mudkip" condition="speed=(x / 22-24 / 9-11)"}
    - Speed tied with Altaria
  :::
  :::if{source="Mudkip" condition="speed=(x / 25-31 / 12-31)"}
    - Faster than Altaria
  :::
    ::damage[Swampert's Ice Beam]{source="Mudkip" offensive=true movePower=95 level=38 evolution=2 opponentLevel=33 opponentStat=84 healthThreshold=102 special=true stab=false type=ice effectiveness=4}
    ::damage[Altaria's Earthquake]{source="Mudkip" offensive=false movePower=100 level=38 evolution=2 opponentLevel=33 statModifier=1.1 opponentStat=61 special=false stab=false type=ground}
    ::damage[Altaria's Dragon Breath]{source="Mudkip" offensive=false movePower=60 level=38 evolution=2 opponentLevel=33 opponentStat=61 special=true stab=true type=dragon}
    ::damage[Altaria's Earthquake(+1)]{source="Mudkip" offensive=false movePower=100 level=38 opponentCombatStages=1 evolution=2 opponentLevel=33 statModifier=1.1 opponentStat=61 special=false stab=false type=ground}
  :::::
:::::::

Go through Route 120
  - Super Repel before Grass(need to use 2 more to get through Mount Pyre)

Get the Lake Rare Candy

Grab this Persim Berry

**Teach Fly to Swablu**

Flag Lilycove as fly location and head back to Mount Pyre

## Mount Pyre

Bike Flash while entering to skip Bike Music Audio Lag
  - Inside take the left exit
  - Bike up to Mountain
  - Dismount bike again before the warp to upper area
  - Remount after warping and head to Grunt 1

:::::::trainer[Aqua Gunt 1]
  :::::pokemon[Carvanha]
    - Strength
  :::if{source="Mudkip" condition="hp=(x / 0-8 / x)"}
    - Rough Skin does 7 HP Damage
  :::
  :::if{source="Mudkip" condition="hp=(x / 9-31 / x)"}
    - Rough Skin does 8 HP Damage
  :::
  :::::
:::::::

:::::::trainer[Aqua Gunt 2]
  :::::pokemon[Zubat]
    - Strength
  :::::
:::::::

:::::::trainer[Aqua Gunt 3 and 4]
  :::::pokemon[Wailmer and Poochyena]
    - Surf, Facade Wailmer
  :::::
  :::::pokemon[Wailmer and Carvanha]
    - Surf, Facade Wailmer
    ::damage[Wailmer's Water Pulse]{source="Mudkip" offensive=false movePower=60 level=39 evolution=2 opponentLevel=30 opponentStat=42 special=true stab=true type=water}
  :::::
  :::::pokemon[Zubat and Carvanha]
    - Strength(Surf if 2 mons are alive)
  :::::
:::::::

Get Hidden Mount Pyre Candy

## Magma Hideout

Fly to Lavaridge

Bag Manip the Hiker Spinner and Menu:
  - Elixir Swampert(Cursor on Swablu)
  - Super Repel
  - Heal to high torrent HP if below 28 HP

Head east to cable car
  - Head to Jagged Path and Enter Magma Hideout

**Need 13 Surf PP for the following secionts if lower can use alternative moves mentioned during fights**

:::::::trainer[Magma Gunt 1]
  :::::pokemon[Poochyena]
    - Ice Beam
  :::::
:::::::

In room 2 approach and fight the trainer immediately for a fast pass on upcoming optionals

:::::::trainer[Magma Gunt 2]
  :::::pokemon[Numel]
    - Ice Beam / Strength
    ::damage[Swampert's Ice Beam]{source="Mudkip" offensive=true movePower=95 level=39 evolution=2 opponentLevel=29 opponentStat=31 healthThreshold=73 special=true stab=false type=ice}
  :::::
:::::::

Immediately after battle, bike 1 tile up and over left down the right side of the stairs
  - Then turn right immediately off of the stairs to avoid the optional
  - Then turn down to the next set of stairs and continue to the next room. 
  - (Watch a video of this before attempting it, if you don’t get the timing correct you will hit an optional)

Use Super Repel when it runs out

:::::::trainer[Magma Gunt 3]
  :::::pokemon[Zubat]
    - Strength
  :::::
:::::::

:::::::trainer[Magma Gunt 4]
  :::::pokemon[Baltoy]
    - Strength
  :::::
:::::::

:::::::trainer[Magma Gunt 5]
  :::::pokemon[Baltoy]
    - Strength
  :::::
:::::::

:::::::trainer[Magma Gunt 6 and 7]
  :::::pokemon[Numel and Zubat]
    - Surf + Powder Snow
:::::::

:::::::trainer[Magma Admin Tabitha]
  :::::pokemon[Numel]
    - Ice Beam
  :::::
  :::::pokemon[Mightyena]
    - Surf
  :::::
  :::::pokemon[Zubat]
    - Surf(Strength if low on PP)
  :::::
  :::::pokemon[Camerupt]
    - Surf
  :::::
:::::::

Gat this Max Revive if want to play Super Safe

:::::::trainer[Magma Leader Maxie 2]
  :::::pokemon[Mightyena]
    - Surf*
    - Stall or use X Special(if you have extra) if not in torrent
  :::if{source="Mudkip" condition="speed=(20 / 0-3 / x)"}
    - Slower than Mightyena
  :::
  :::if{source="Mudkip" condition="speed=(21-23 / 4-6 / x)"}
    - Speed Tied with Mightyena
  :::
  :::if{source="Mudkip" condition="speed=(24-31 / 6-31 / 0-31)"}
    - Faster than Mightyena
  :::
    ::damage[Mightyena's Take Down]{source="Mudkip" offensive=false movePower=90 level=40 evolution=2 opponentLevel=37 statModifier=1.1 opponentStat=78 special=false stab=false type=normal}
  :::::
  :::::pokemon[Crobat]
    - Surf x2
    - Stall or use X Special(if you have extra) if not in torrent
  :::if{source="Mudkip" condition="spatk=(x / 0-1 / x)"}
    - Swampert's Surf x2 is 1.2% to 2HKO if no torrent for both turns
    - Recommended to use Ice Beam x2
  :::
  :::if{source="Mudkip" condition="spatk=(x / 2-6 / x)"}
    - Swampert's Surf x2 is 5.5% to 2HKO if no torrent for both turns
    - Recommended to use Ice Beam x2
  :::
  :::if{source="Mudkip" condition="spatk=(x / 7-11 / x)"}
    - Swampert's Surf x2 is 25.4% to 2HKO if no torrent for both turns
    - Recommended to use Ice Beam x2
  :::
  :::if{source="Mudkip" condition="spatk=(x / 12-13 / x)"}
    - Swampert's Surf x2 is 40.2% to 2HKO if no torrent for both turns
    - Recommended to use Ice Beam x2
  :::
  :::if{source="Mudkip" condition="spatk=(x / 14-18 / 0-1)"}
    - Swampert's Surf x2 is 72.7% to 2HKO if no torrent for both turns
    - Recommended to use Ice Beam x2
  :::
  :::if{source="Mudkip" condition="spatk=(x / 19-23 / 2-6)"}
    - Swampert's Surf x2 is 80.9% to 2HKO if no torrent for both turns
    - Recommended to use Ice Beam x2
  :::
  :::if{source="Mudkip" condition="spatk=(x / 24-28 / 7-11)"}
    - Swampert's Surf x2 is 96.9% to 2HKO if no torrent for both turns
  :::
  :::if{source="Mudkip" condition="spatk=(x / 29-31 / 12-13)"}
    - Swampert's Surf x2 is 99.6% to 2HKO if no torrent for both turns
  :::
  :::if{source="Mudkip" condition="spatk=(x / x / 14-31)"}
    - Swampert's Surf x2 is 100% to 2HKO if no torrent for both turns
  :::
    ::damage[Crobat's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=40 evolution=2 opponentLevel=38 statModifier=1.1 opponentStat=88 special=false stab=true type=flying}
  :::::
  :::::pokemon[Camerupt]
    - Surf
    - Slower at -2(Scary Faced by Mightyena)
    ::damage[Camerupt's Earthquake]{source="Mudkip" offensive=false movePower=100 level=41 evolution=2 opponentLevel=39 statModifier=1.1 opponentStat=99 special=false stab=true type=ground}
  :::::
:::::::

## Aqua Hideout

:::if{source="Mudkip" condition="speed=(20-28 / 0-11 / x)"}
You are slower than Matt's Golbat Potion to high torrent if possible
:::

Use Escape Rope and fly to Slateport

Go to the docks north of the museum for a cutscene
  - Talk to Stern here
  - After the submarine leaves, Fly to Lilycove City

Grab this Elixir if low on Surf PP and use before Matt

Head to Aqua Hideout

Grab Master Ball

:::::::trainer[Aqua Gunt 1 and 2]
  :::::pokemon[Zubat and Poochyena]
    - Surf + Facade the right side
  :::::
  :::::pokemon[Zubat(and Carvanha)]
    - Strength 
    - Facade Caranha if it lived
  :::::
:::::::

:::::::trainer[Aqua Gunt 3 and 4]
  :::::pokemon[Zubat and Carvanha]
    - Surf + Powder Snow
  :::::
:::::::

:::::::trainer[Aqua Admin Matt]
  :::::pokemon[Mightyena]
    - Surf*
  :::::
  :::::pokemon[Golbat]
    - Surf* / Ice Beam
    ::damage[Swampert's Ice Beam]{source="Mudkip" offensive=true movePower=95 level=41 evolution=2 opponentLevel=34 opponentStat=58 healthThreshold=97 special=true stab=false type=ice effectiveness=2}
    ::damage[Swampert's Surf*]{source="Mudkip" offensive=true movePower=95 level=41 evolution=2 opponentLevel=34 opponentStat=58 healthThreshold=97 special=true torrent=true otherPowerModifier=1.09 stab=true type=water}
    :::if{source="Mudkip" condition="speed=(20-26 / 0-9 / x)"}
    - Slower than Golbat
    :::
    :::if{source="Mudkip" condition="speed=(27-28 / 10-11 / x)"}
    - Slower than Golbat
    :::
    :::if{source="Mudkip" condition="speed=(29-31 / 12-31 / 0-31)"}
    - Faster than Golbat
    :::
  :::::
:::::::

Remeber to Grab this Elixir before leaving

Menu:
  - Super Repel
  - Rare Candy to Level 44
  - Use Max Elixir
  - Heal to full

## Route 124

Surf east towards Mossdeep City

There is a spinner on the right(initial movement is look down)
  - Fight the male swimmer South of her

:::::::trainer[Swimmer Declan]
  :::::pokemon[Gyarados]
    - Ice beam + Strength + Ice Beam(Surf* x2)
    - Dragon Rage does 40 Damage
    ::damage[Gyarados's Thrash]{source="Mudkip" offensive=false movePower=90 level=44 evolution=2 opponentLevel=34 statModifier=1.1 opponentStat=90 special=false stab=false type=normal}
    :::if{source="Mudkip" condition="spatk=(x / 0-3 / x)"}
    - Swampert's Surf* x2 is a 23.4% range to 2HKO
    :::
    :::if{source="Mudkip" condition="spatk=(x / 4-5 / x)"}
    - Swampert's Surf* x2 is a 38.7% range to 2HKO
    :::
    :::if{source="Mudkip" condition="spatk=(x / 6-8 / x)"}
    - Swampert's Surf* x2 is a 56.6% range to 2HKO
    :::
    :::if{source="Mudkip" condition="spatk=(x / 9-14 / x)"}
    - Swampert's Surf* x2 is a 74.6% range to 2HKO
    :::
    :::if{source="Mudkip" condition="spatk=(x / 14-17 / x)"}
    - Swampert's Surf* x2 is a 84.4% range to 2HKO
    :::
    :::if{source="Mudkip" condition="spatk=(x / 18-23 / 0-5)"}
    - Swampert's Surf* x2 is a 98% range to 2HKO
    :::
    :::if{source="Mudkip" condition="spatk=(x / 24-31 / 6-31)"}
    - Swampert's Surf* x2 is a 100% range to 2HKO
    :::
  :::::
:::::::

Bag Manip to pass the Swimmer
  - Can use this to heal or revive something if you need to

Enter Mossdeep Mart

:::card{theme=neutral}
### Shopping
#### Buy:
  - 11 Hyper Potions (vvv)
  - 4 Full Heals (v)
  - 1-2 Revives (v) **Only if want to play super safe or one of the mon is dead**
  - 11 Max Repels(vv)
  - 11(or Max) X Attacks(v)
:::

Head to the Gym

## Mossdeep Gym

**Fight first double battle as singles**

:::::::trainer[Psychic Preston]
  :::::pokemon[Kirlia]
    - Strength
  :::::
:::::::

Press the yellow Button

:::::::trainer[Psychic Maura]
  :::::pokemon[Kadabra]
    - Strength
  :::::
:::::::

Use the teleport tile 
  - Step on the next yellow switch 2 times
  - Then use the right Teleporter
  - Double Press the both Purple Switched
  - Fight the female trainer to the right

:::::::trainer[Psychic Macey]
  :::::pokemon[Natu]
    - Strength
  :::::
:::::::

Walk down to the green switch, pressing it twice
  - Then go all the way back, pressing the lower purple switch two more times
  - This time use the left teleporter
  - Here press the blue switch 3 times, allowing you to walk up to the trainer on the orange rotating tiles and battle her

:::::::trainer[Hex Maniac Sylvia]
  :::::pokemon[Meditite]
    - Surf
  :::::
:::::::

Press the orange switch 3 times and walk around, fighting one more trainer

:::::::trainer[Psychic Hannah]
  :::::pokemon[Kirlia]
    - Strength
  :::::
:::::::

Use the blue switches to avoid trainers, Continue to the teleport tile in the upper right corner

Menu:
  - Revive Mons if needed
  - Heal out of Xatu Psychic x2 Range

::damage[Xatu's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=95 special=true stab=true type=psychic}

::::::::if{source="Mudkip" condition="speed=(20-31 / 0-13 / 0)"}
:::::::trainer[Gym Leader Tate & Liza]
  :::::pokemon[Xatu]
    - X Special + Powder Snow(Send Swablu in when Castform dies)
    - Ice Beam Xatu and fly with Swablu
    ::damage[Xatu's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=95 special=true stab=true type=psychic}
  :::::
  :::::pokemon[Claydol, Solrock and Lunatone]
    - X Speed + Surf Spam
    ::damage[Claydol's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=74 special=true stab=true type=psychic}
    ::damage[Claydol's Earthquake]{source="Mudkip" offensive=false movePower=100 level=45 evolution=2 opponentLevel=41 opponentStat=74 statModifier=1.1 special=false stab=true type=ground}
    ::damage[Solrock's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=42 opponentStat=69 special=true stab=true type=psychic}
    ::damage[Lunatone's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=42 opponentStat=87 special=true stab=true type=psychic}
  :::::
:::::::
::::::::

::::::::if{source="Mudkip" condition="speed=(x / 14-17 / 1-4)"}
:::::::trainer[Gym Leader Tate & Liza]
  :::::pokemon[Xatu]
    - X Special + Powder Snow(Send Swablu in when Castform dies)
    - Ice Beam Xatu and fly with Swablu /  Heal if Swampert is in range of Earthquake x2
    ::damage[Xatu's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=95 special=true stab=true type=psychic}
  :::::
  :::::pokemon[Claydol, Solrock and Lunatone]
    - Strength Claydol and then spam Surf if Claydol Surf*(+1) isn't a good range
    - Surf spam if Claydol Surf*(+1) is a good range
    ::damage[Swampert's Surf*]{source="Mudkip" offensive=true movePower=95 level=45 evolution=2 opponentLevel=41 opponentStat=103 healthThreshold=112 special=true torrent=true combatStages=1 otherPowerModifier=1.1 stab=true type=water multiTarget=true effectiveness=2}
    ::damage[Claydol's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=74 special=true stab=true type=psychic}
    ::damage[Claydol's Earthquake]{source="Mudkip" offensive=false movePower=100 level=45 evolution=2 opponentLevel=41 opponentStat=74 statModifier=1.1 special=false stab=true type=ground}
    ::damage[Solrock's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=42 opponentStat=69 special=true stab=true type=psychic}
    ::damage[Lunatone's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=42 opponentStat=87 special=true stab=true type=psychic}
  :::::
:::::::
::::::::

::::::::if{source="Mudkip" condition="speed=(x / 18-31 / 5-31)"}
:::::::trainer[Gym Leader Tate & Liza]
  :::::pokemon[Xatu]
    - X Special + Powder Snow(Send Swablu in when Castform dies)
    - Ice Beam Xatu and fly with Swablu
    ::damage[Xatu's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=95 special=true stab=true type=psychic}
  :::::
  :::::pokemon[Claydol, Solrock and Lunatone]
    - Surf Spam
    ::damage[Swampert's Surf*]{source="Mudkip" offensive=true movePower=95 level=45 evolution=2 opponentLevel=41 opponentStat=103 healthThreshold=112 special=true torrent=true combatStages=1 otherPowerModifier=1.1 stab=true type=water multiTarget=true effectiveness=2}
    ::damage[Claydol's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=41 opponentStat=74 special=true stab=true type=psychic}
    ::damage[Claydol's Earthquake]{source="Mudkip" offensive=false movePower=100 level=45 evolution=2 opponentLevel=41 opponentStat=74 statModifier=1.1 special=false stab=true type=ground}
    ::damage[Solrock's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=42 opponentStat=69 special=true stab=true type=psychic}
    ::damage[Lunatone's Psychic]{source="Mudkip" offensive=false movePower=90 level=45 evolution=2 opponentLevel=42 opponentStat=87 special=true stab=true type=psychic}
  :::::
:::::::
::::::::

## Space Center

Head towards Mossdeep Space Center

Skip optional trainers and fight two trainer near stairs in the top right

:::::::trainer[Magma Grunt 1]
  :::::pokemon[Baltoy]
    - Strength
  :::::
:::::::

:::::::trainer[Magma Grunt 2]
  :::::pokemon[Mightyena]
    - Ice Beam
  :::::
  :::::pokemon[Mightyena]
    - Ice Beam
  :::::
  :::::pokemon[Numel]
    - Ice Beam
  :::::
:::::::

Go Upstaris and Accept the battle

:::::::trainer[Magma Grunt 3]
  :::::pokemon[Zubat]
    - Strength
  :::::
:::::::

:::::::trainer[Magma Grunt 4]
  :::::pokemon[Mightyena]
    - Surf
  :::::
:::::::

:::::::trainer[Magma Grunt 5]
  :::::pokemon[Baltoy]
    - Strength
  :::::
:::::::

**Consider Potion if you can get into High Torrent**

**You at least need 7 Surfs for True Double and Archie**

Talk to steven to start the battle

:::::::trainer[True Double]
  - Press Start to see HP of Pokemon
  - Then Guard Spec and X Special
  - Surf x3
  ::damage[Mightyena's Take Down]{source="Mudkip" offensive=false movePower=90 level=46 evolution=2 opponentLevel=42 statModifier=1.1 opponentStat=88 special=false stab=false type=normal}
  ::damage[Camerupt's Earthquake]{source="Mudkip" offensive=false movePower=100 level=46 evolution=2 opponentLevel=36 statModifier=1.1 opponentStat=81 special=false stab=true multiTarge=true type=ground}
  ::damage[Golbat's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=46 evolution=2 opponentLevel=40 statModifier=1.1 opponentStat=73 special=false stab=true type=flying}
  ::damage[Crobat's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=46 evolution=2 opponentLevel=43 statModifier=1.1 opponentStat=99 special=false stab=true type=flying}
:::::::

Visit Steven's House(Top Left house in the City) to aquire Dive

## Seafloor Cavern

Bike down to ocean and Menu:
  - Teach Dive to Swampert over Ice Beam
  - Move Escape Rope to above Max Repels
  - Max Repel

Head to Seafloor Cavern
  - Avoid all the trainers

Max Repel here

:::::::trainer[Team Aqua Leader Archie]
  :::::pokemon[Mightyena]
    - Surf*
    - X Special if no Torrent
  ::damage[Mightyena's Take Down]{source="Mudkip" offensive=false movePower=90 level=47 evolution=2 opponentLevel=41 statModifier=1.1 opponentStat=94 special=false stab=false type=normal}
  :::::
  :::::pokemon[Crobat]
    - X Speed + Super Potion + X Special + Surf
    - Super Potion turn 1 if it takes you to around 50% HP
  ::damage[Crobat's Wing Attack]{source="Mudkip" offensive=false movePower=60 level=47 evolution=2 opponentLevel=41 statModifier=1.1 opponentStat=86   special=false stab=true type=flying}
  :::::
  :::::pokemon[Sharpedo]
    - Surf* (x2)
    - Strength to kill if got Swaggered
    :::if{source="Mudkip" condition="hp=(x / 0-17 / x)"}
    - Rough Skin does 9 damage
    :::
    :::if{source="Mudkip" condition="hp=(x / 18-31 / x)"}
    - Rough Skin does 10 damage
    :::
  ::damage[Sharpedo's Slash]{source="Mudkip" offensive=false movePower=70 level=47 evolution=2 opponentLevel=43 statModifier=1.1 opponentStat=115 special=false stab=false type=normal}
:::::::

## Save the World

Max Repel then follow this Movement

After flagging Pacifidlog fly to Mossdeep
  - Surf to Sootopolis
  - Dive and enjoy the Cutscene

Go talk to Steven
  - Select Sky Pillar while talking to Wallace

Menu(Cursor on Pokemon):
  - Max Repel
  - Escape Rope

Fly to Pacifidlog and head to Sky Pillar
  - Awaken Rayquaza
  - Fly back to Sootopolis
  - Enjoy another Cutscene(Pray for good Rain RNG)

Fly to Pacifidlog again
  - Head to Sky Pillar
  - Catch Rayquaza with Master Ball
  
Menu:
  - Swap Rayquaza to Slot 1
  - Eqip Persim Berry if no X Special left
  - Fly to Sootopolis

## Juan

Talk to Archie, Maxie then Wallace

Do the Gym Puzzle

:::::::trainer[Leader Juan]
  :::::pokemon[Luvdisc]
    - Extremespeed
  :::::
  :::::pokemon[Kingdra]
    - Outrage
  :::::
  :::::pokemon[Sealeo]
    - Outrage
  :::::
  :::::pokemon[Whiscash]
    - (Heal Confusion) Outrage
  :::::
  :::::pokemon[Crawdaunt]
    - (Heal Confusion) Outrage
  :::::
:::::::

## Victory Road

Fly back to Mosdeep
  - Head towards Seafloor Cavern
  - Head right instead of diving

After turning right before the seafloor cavern, go past the next island then all the way down to the edge of the island where there is a fisherman
  - Going right along the edge here allows you to perfectly avoid all of the upcoming swimmers

During next Repel Menu
  - Equip Persim Berry on Rayquaza(if applicable)
  - Teach Waterfall over Rest(Slot 2)
  - Teach Aerial Ace over Extremespeed(Slot 3)
  - Max Repel

In Victory Road bike up, use the stairs and go left
  - Wally will appear and challenge you

:::::::trainer[Trainer Wally]
  :::::pokemon[Altaria]
    - Aerial Ace / Fly
    ::damage[Rayquaza's Aerial Ace]{source="Rayquaza" offensive=true movePower=60 level=70 opponentLevel=44 opponentStat=92 healthThreshold=127 statModifier=1.1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Delcatty]
    - Waterfall
  :::::
  :::::pokemon[Magneton]
    - Waterfall
  :::::
  :::::pokemon[Roselia]
    - Outrage
  :::::
  :::::pokemon[Gardevoir]
    - Outrage
  :::::
:::::::

:::::::trainer[Cooltrainer Hope]
  :::::pokemon[Roselia]
    - Outrage
  :::::
:::::::

:::::::trainer[Cooltrainer Shannon]
  :::::pokemon[Claydol]
    - Outrage
  :::::
:::::::

:::::::trainer[Cooltrainer Julie]
  :::::pokemon[Sandslash]
    - Waterfall
  :::::
  :::::pokemon[Ninetales]
    - Outrage
  :::::
  :::::pokemon[Tropius]
    - Outrage
  :::::
:::::::

Either bag manip or run to bike the final spinner in the dark

:::::::trainer[Cooltrainer Edgar]
  :::::pokemon[Cacturne]
    - Outrage
  :::::
  :::::pokemon[Pelipper]
    - Outrage
  :::::
:::::::

## Elite 4

Talk to the two door homeboys

Go to the PC and:-
  - Deposit Castform, Swablu and Swampert
  - Press Select to Deposit faster

:::::::trainer[Elite 4 Sidney]
  :::::pokemon[Mightyena]
    - Waterfall
  :::::
  :::::pokemon[Absol]
    - Waterfall(x2) / Outrage(use if have persim berry equipped) / Aerial Ace x2
    ::damage[Rayquaza's Waterfall]{source="Rayquaza" offensive=true movePower=80 level=71 opponentLevel=49 opponentStat=78 healthThreshold=137 statModifier=1.1 special=true stab=false type=water}
  :::::
  :::::pokemon[Shiftry]
    - Aerial Ace / Outrage(if used on Absol)
  :::::
  :::::pokemon[Cacturne]
    - Outrage
  :::::
  :::::pokemon[Crawdaunt]
    - Outrage
  :::::
:::::::

::::::::if{source="Rayquaza" condition="atk=(0-31 / x / x)"}
:::::::trainer[Elite 4 Phoebe]
  :::::pokemon[Dusclops]
    - X Attack x2 + Fly
    - Aerial Ace if got double protected
  :::::
  :::::pokemon[Dusclops]
    - Aerial Ace
  :::::
  :::::pokemon[Bannete]
    - Aerial Ace
  :::::
  :::::pokemon[Sabelye]
    - Outrage
  :::::
  :::::pokemon[Bannete]
    - Outrage
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(x / 0-31 / 0-31)"}
:::::::trainer[Elite 4 Phoebe]
  :::::pokemon[Dusclops]
    - X Attack + Fly
    - Aerial Ace if got double protected
  :::::
  :::::pokemon[Dusclops]
    - Aerial Ace(+Waterfall) / Fly
    ::damage[Rayquaza's Aerial Ace]{source="Rayquaza" offensive=true movePower=60 level=71 opponentLevel=51 opponentStat=153 healthThreshold=117 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
    ::damage[Rayquaza's Fly]{source="Rayquaza" offensive=true movePower=70 level=71 opponentLevel=51 opponentStat=153 healthThreshold=117 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Bannete]
    - Aerial Ace
  :::::
  :::::pokemon[Sabelye]
    - Outrage
  :::::
  :::::pokemon[Bannete]
    - Outrage
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="spatk=(x / 0-31 / 0-31)"}

If you have your Persim Berry still remaining and can live an Ice Beam from Walrein use this non X Attack fight

::damage[Rayquaza's Outrage on Walrein]{source="Rayquaza" offensive=true movePower=90 level=72 opponentLevel=53 opponentStat=104 healthThreshold=196 statModifier=1.1 special=true stab=true type=dragon}

:::::::trainer[Elite 4 Glacia]
  :::::pokemon[Sealeo]
    - Outrage
  :::::
  :::::pokemon[Glalie]
    - Outrage
  :::::
  :::::pokemon[Sealeo]
    - Outrage
  :::::
  :::::pokemon[Glalie]
    - Outrage
  :::::
  :::::pokemon[Walrein]
    - Outrage(x2)
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(0-31 / 0-31 / 0-12)"}
:::::::trainer[Elite 4 Glacia]
  :::::pokemon[Sealeo]
    - X Attack x2 + Aerial Ace
  :::::
  :::::pokemon[Glalie]
    - Aerial Ace
  :::::
  :::::pokemon[Sealeo]
    - Aerial Ace
  :::::
  :::::pokemon[Glalie]
    - Aerial Ace
  :::::
  :::::pokemon[Walrein]
    - Aerial Ace / Fly
    - Fly is a 100% range
    ::damage[Rayquaza's Aerial Ace]{source="Rayquaza" offensive=true movePower=60 level=72 opponentLevel=53 opponentStat=116 healthThreshold=196 statModifier=1.1 combatStages=2 special=false stab=true type=flying}
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(x / x / 13-31)"}
:::::::trainer[Elite 4 Glacia]
  :::::pokemon[Sealeo]
    - X Attack + Aerial Ace
  :::::
  :::::pokemon[Glalie]
    - Aerial Ace
  :::::
  :::::pokemon[Sealeo]
    - Aerial Ace
  :::::
  :::::pokemon[Glalie]
    - Aerial Ace
  :::::
  :::::pokemon[Walrein]
    - Fly
    ::damage[Rayquaza's Fly]{source="Rayquaza" offensive=true movePower=70 level=72 opponentLevel=53 opponentStat=116 healthThreshold=196 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(0-31 / 0-23 / x)"}

If you still have Persim Berry Equipped or one is left in bag
  - Also heal to tank Blizzard on Champ

:::::::trainer[Elite 4 Drake]
  :::::pokemon[Shelgon]
    - Outrage
  :::::
  :::::pokemon[Altaria]
    - Outrage
  :::::
  :::::pokemon[Flygon]
    - Outrage
  :::::
  :::::pokemon[Salamence]
    - Outrage
  :::::
  :::::pokemon[Kingdra]
    - Outrage
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(0-31 / 0-31 / 0-6)"}
:::::::trainer[Elite 4 Drake]
  :::::pokemon[Shelgon]
    - X Attack x2 (+X Speed if Rock Tomb) + Aerial Ace(x2 if Protect)
  :::::
  :::::pokemon[Altaria]
    - Aerial Ace
  :::::
  :::::pokemon[Flygon]
    - Aerial Ace
  :::::
  :::::pokemon[Salamence]
    - Aerial Ace
  :::::
  :::::pokemon[Kingdra]
    - Aerial Ace
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(x / x / 7-31)"}
:::::::trainer[Elite 4 Drake]
  :::::pokemon[Shelgon]
    - X Attack (+X Speed if Rock Tomb) + Aerial Ace(x2 if Protect)
  :::::
  :::::pokemon[Altaria]
    - Aerial Ace
  :::::
  :::::pokemon[Flygon]
    - Aerial Ace
  :::::
  :::::pokemon[Salamence]
    - Aerial Ace
  :::::
  :::::pokemon[Kingdra]
    - Aerial Ace
  :::::
:::::::
::::::::

**Heal to full if you don't tank Blizzard right now**

::damage[Wailord's Blizard]{source="Rayquaza" offensive=false movePower=120 level=73 opponentLevel=57 statModifier=1.1 opponentStat=137 special=true stab=false type=ice effectiveness=4}

::::::::if{source="Rayquaza" condition="atk=(0-19 / x / x)"}
:::::::trainer[Chamption Wallace]
  :::::pokemon[Wailord]
    - Either X Attack + Fly
    - Or X Attack x2 by stalling Wailord Blizzard with Hyper Potions(Wailord using Rain Dance also works)
    ::damage[Rayquaza's Fly(+1)]{source="Rayquaza" offensive=true movePower=70 level=73 opponentLevel=57 opponentStat=73 healthThreshold=278 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Tentacruel]
    - Aerial Ace
  :::::
  :::::pokemon[Milotic]
    - Aerial Ace(Fly if only used 1 X Attack on Wailord)
    ::damage[Rayquaza's Fly(+1)]{source="Rayquaza" offensive=true movePower=70 level=73 opponentLevel=58 opponentStat=102 healthThreshold=196 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Gyarados]
    - X Attack(x2 if only used 1 X Attack on Wailord) + Aerial Ace
    ::damage[Gyarados's Hyper Beam]{source="Rayquaza" offensive=false movePower=150 level=73 opponentLevel=56 opponentStat=162 statModifier=1.1 special=false stab=false type=normal}
  :::::
  :::::pokemon[Ludicolo]
    - Aerial Ace
  :::::
  :::::pokemon[Whiscash]
    - Aerial Ace
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(20-31 / 0-30 / 0)"}
:::::::trainer[Chamption Wallace]
  :::::pokemon[Wailord]
    - X Attack + Fly
    ::damage[Rayquaza's Fly(+1)]{source="Rayquaza" offensive=true movePower=70 level=73 opponentLevel=57 opponentStat=73 healthThreshold=278 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Tentacruel]
    - Aerial Ace
  :::::
  :::::pokemon[Milotic]
    - Fly
    ::damage[Rayquaza's Fly(+1)]{source="Rayquaza" offensive=true movePower=70 level=73 opponentLevel=58 opponentStat=102 healthThreshold=196 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
    ::damage[Rayquaza's Aerial Ace(+1)]{source="Rayquaza" offensive=true movePower=60 level=73 opponentLevel=58 opponentStat=102 healthThreshold=196 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Gyarados]
    - X Attack x2 + Aerial Ace
    ::damage[Gyarados's Hyper Beam]{source="Rayquaza" offensive=false movePower=150 level=73 opponentLevel=56 opponentStat=162 statModifier=1.1 special=false stab=false type=normal}
  :::::
  :::::pokemon[Ludicolo]
    - Aerial Ace
  :::::
  :::::pokemon[Whiscash]
    - Aerial Ace
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(x / 31 / 1-5)"}
:::::::trainer[Chamption Wallace]
  :::::pokemon[Wailord]
    - X Attack + Fly
  :::::
  :::::pokemon[Tentacruel]
    - Aerial Ace
  :::::
  :::::pokemon[Milotic]
    - Aerial Ace / Fly
    ::damage[Rayquaza's Aerial Ace(+1)]{source="Rayquaza" offensive=true movePower=60 level=73 opponentLevel=58 opponentStat=102 healthThreshold=196 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Gyarados]
    - X Attack x2 + Aerial Ace
    ::damage[Gyarados's Hyper Beam]{source="Rayquaza" offensive=false movePower=150 level=73 opponentLevel=56 opponentStat=162 statModifier=1.1 special=false stab=false type=normal}
  :::::
  :::::pokemon[Ludicolo]
    - Aerial Ace
  :::::
  :::::pokemon[Whiscash]
    - Aerial Ace
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(x / x / 6-16)"}
:::::::trainer[Chamption Wallace]
  :::::pokemon[Wailord]
    - X Attack + Aerial Ace / Fly
    ::damage[Rayquaza's Aerial Ace(+1)]{source="Rayquaza" offensive=true movePower=60 level=73 opponentLevel=57 opponentStat=73 healthThreshold=278 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
  :::::pokemon[Tentacruel]
    - Aerial Ace
  :::::
  :::::pokemon[Milotic]
    - Aerial Ace
  :::::
  :::::pokemon[Gyarados]
    - X Attack x2 + Aerial Ace
    ::damage[Gyarados's Hyper Beam]{source="Rayquaza" offensive=false movePower=150 level=73 opponentLevel=56 opponentStat=162 statModifier=1.1 special=false stab=false type=normal}
  :::::
  :::::pokemon[Ludicolo]
    - Aerial Ace
  :::::
  :::::pokemon[Whiscash]
    - Aerial Ace
  :::::
:::::::
::::::::

::::::::if{source="Rayquaza" condition="atk=(x / x / 17-31)"}
:::::::trainer[Chamption Wallace]
  :::::pokemon[Wailord]
    - X Attack + Aerial Ace
  :::::
  :::::pokemon[Tentacruel]
    - Aerial Ace
  :::::
  :::::pokemon[Milotic]
    - Aerial Ace
  :::::
  :::::pokemon[Gyarados]
    - X Attack + Aerial Ace
    ::damage[Gyarados's Hyper Beam]{source="Rayquaza" offensive=false movePower=150 level=73 opponentLevel=56 opponentStat=162 statModifier=1.1 special=false stab=false type=normal}
  :::::
  :::::pokemon[Ludicolo]
    - Aerial Ace
  :::::
  :::::pokemon[Whiscash]
    - Aerial Ace
    ::damage[Rayquaza's Aerial Ace(+1)]{source="Rayquaza" offensive=true movePower=60 level=73 opponentLevel=57 opponentStat=104 healthThreshold=206 statModifier=1.1 combatStages=1 special=false stab=true type=flying}
  :::::
:::::::
::::::::
