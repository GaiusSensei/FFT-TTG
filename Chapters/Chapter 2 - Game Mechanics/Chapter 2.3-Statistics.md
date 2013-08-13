Statistics
---
Each Player in FFT-TTG controls at least one Character (most probably more). Each of these characters has their own set of Statistics that defines the character; a measure of the character's abilities. There are two sets of stats that we use: Attributes and Combat Statistics.  
  
**Attributes**  

1. Strength (STR) - contributes on the character's Physical Damage.  
2. Vitality (VIT) - determines the amount of HP the character has and reduces damage recieved from Physical Attacks.   
3. Speed (SPD) - coresponds to the character's battle initiative.  
4. Magic (MAG) - contributes on the character's Magical Damage.  
5. Spirit (SPR) - determines the amount of MP the character has and reduces damage recieved from Magical Attacks.  

Each attribute starts from 10 pts. plus any modifications from Character Creation, and every 10 Job Levels gained, two of them are increased by 2 depending on the current Job, up to a maximum of 30 pts. Some Passive Abilities & Equipment also increase these attributes.  

**Combat Statistics**  

1. Level (LVL) - The total amount of Job Levels accumulated by the character, from 1 to a maximum of 100.  

2. Hit Points (HP) - Damage done to the character is subtracted to their HP; they fall unconscious when it hits 0, and can go up to a maximum of 999.  
> A character's Hit Points (HP) is calculated by: 10 + ((LVL/4) * VIT * HP Modifier of Job with the most levels)    

3. Magic Points (MP) - Magic points are used by characters to fuel their Active Abilities, and it starts from 0 to a maximum of 999.  
> A character's Magic Points (MP) is calculated by: ((LVL/3) * SPR * MP Modifier of Job with the most levels)    

4. Armor (ARM) - Armor is deducted to any physical damage dealt to the character  
>  A character's Armor (ARM) is calculated by: ((LVL/30) * VIT) + Total Equipment Bonus to ARM  

5. Magic Armor (MARM) - Magic Armor is deducted to any magical damage dealt to the character  
>  A character's Magic Points (MP) is calculated by: ((LVL/30) * SPR) + Total Equipment Bonus to MARM  

6. Base Damage Dice (BDD) - The Number of Dice used in Active Abilities.  
>  A character's Base Damage Dice is calculated by: LVL/25 (+1 every 25 levels)  

7. Physical Attack (PA) - Physical Attack is the modified Damage for Active Abilities that deal Physical Damage  
>  A character's Physical Attack (PA) is calculated by: (STR-10)/2  

8. Magical Attack (MA) - Magical Attack is the modified Damage for Active Abilities that deal Magical Damage  
>  A character's Magical Attack (MA) is calculated by: (MAG-10)/2  

9. Weapon Power (WP) - Amount of Damage added to every attack after the damage dice are rolled  
> A character's Weapon Power (WP) is calculated by: Sum of Equipment Damage  

A physical Active Ability, like a Fighter's Slash Attack (d6 damage;range 1), deals damage like so:  
> (( BDD * d6 ) * PA) + WP  

So, first the player will roll a number of dice equal to the character's BDD, multiply it with their PA, then add their WP. Subtract the target's Armor before reducing the target's Hp. Magic damage behaves the same way, except it uses the character's MA and the target's MARM.  