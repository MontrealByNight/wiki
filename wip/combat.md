# Montreal Combat Rule correction

This document outlines the strict, step-by-step resolution system for combat that we will use in the server. 

As integrity and fairness is the most important aspect during PvP combat, some of those rules can be hand-waived by the STs in situation of PvE. 

These rules are designed to remove ambiguity, enforce action economy, and ensure fair, balanced encounters based on the *Vampire: The Masquerade 5th Edition* Corebook.

---

## Phase 1: Initiative Order (Ref: V5 Corebook, pg. 125 - Gehenna War pg. 52)

Unless one party has successfully set up an ambush (gaining **Surprise** via a stealth or tactics test), combat actions are resolved in a strict descending order based on the action tier. 

### The Action Tiers
0. **Surprise:** Any characters who successfully snuck up on someone, has entered combat undetected, or has some other narrative means of striking unnoticed, acts first, no matter what arena of combat they fight in.
1. **Old Melee:** Characters who are *already* locked in close combat (brawling or melee) from a previous turn.
2. **Ranged:** Any characters using firearms, a Discipline that acts from a distance, or any other means of attacking outside of a person’s reach act next.
3. **New Melee:** Characters who are moving into striking distance to engage in close combat this turn.
4. **Anything Else:** Any actions that aren’t engaging in any kind of active physical or ranged combat but do require a roll act last. This includes acts of larceny, hacking, commanding animals in a non-combat manner, and any non-aggressive use of vehicles. Any characters trying social means of ending the physical combat or are involved in afull Social combat act in this order as well.

### Resolving Ties Within a Tier
When multiple players act within the same tier, use the following order to determine who resolves their action first:
* **1st Tie-Breaker:** Compare the total of **Dexterity + Wits**. The higher combined rating goes first.
* **2nd Tie-Breaker:** Compare the dots in the **Skill** being used (e.g., Firearms vs. Firearms). The higher rating goes first.
* **3rd Tie-Breaker (Server Standard):** If stats are completely identical, players roll a single standard 10-sided die. The highest number goes first.

---

## Phase 2: Action Declarations

Before any roll is made, all players must formally declare their actions for the turn. To reflect the tactical advantage of speed and awareness, declarations are made in **Reverse Initiative Order**. 

### 1. The Declaration Order
* The character who is *last* in the initiative order must declare their action first. 
* The character who is *first* in the initiative order declares last, allowing them to react to the stated intentions of slower characters.

### 2. Locked Actions (No Metagaming)
* A declaration covers the character's plan for the *entire turn*. 
* Once an action is declared, it is completely locked in. You cannot change your action mid-turn based on how another player's roll goes. If your target is killed before your turn comes up, your action is wasted. 

### 3. Declaring Powers & Rouse Checks (Mandatory)
To ensure the Storyteller can accurately calculate dice pools and damage, **ALL** powers relevant to the combat must be explicitly stated during this phase. *If a power is not declared, the character cannot use or benefit from it this turn.*
* **Active Powers:** Any action requiring a Rouse Check (e.g., activating a Discipline, using Blood Surge to boost a roll, or mending damage). 
* **Passive/Duration Powers:** You must declare any previously activated or passive powers that will affect the math of the current turn. This includes, but is not limited to: *Toughness* (Fortitude), *Fleetness* (Celerity), *Prowess* (Potence), *Feral Weapons* (Protean), or *Daunt* (Presence).
* **The Hunger Rule:** While the Rouse Checks are declared now, any resulting increases to a character's Hunger do *not* affect their dice pools for the current turn. Hunger increases only take effect at the absolute end of the turn.

### 4. Declaring Weapons & Damage Modifiers
Along with their action, players must explicitly state the mathematical damage values they are bringing to the strike. The ST will not look these up for you. You must declare:
* **Base Weapon Rating:** (e.g., Unarmed +0, Light Melee +2, Heavy Firearm +4).
* **Discipline Modifiers:** Any powers that directly alter your damage rating or type must be clearly added to this declaration (e.g., adding half your Potence rating for *Prowess*, or noting that you are using *Feral Weapons* which deal unhalved Superficial damage).

### 5. The Storyteller Summary
* Once all players have declared their actions, powers, and weapon ratings, the Storyteller (ST) will create a single, definitive post. 
* This post will outline the final Initiative Order, every character's locked action, the declared powers, the total weapon modifiers, and exactly which dice pools each player needs to roll. 
* *No rolling happens until the ST posts this summary.*

---

## Phase 3: Rolling & Resolution

Once the Storyteller has posted the official summary of actions, all declared Rouse Checks are rolled, and the action tests are made in standard Initiative order.

### 1. The Opposed Roll (Counter-Attacks)
*(Ref: V5 Corebook, pg. 124 - "Conflict Pools")*
When two characters are engaged in physical combat and have declared physical attacks against one another, the conflict is resolved via an Opposed Roll. This is referred to as a **Counter-Attack**.
* Both players roll their respective combat pools against each other simultaneously.
* **The Result:** The character with the most successes wins. They subtract the loser's successes from their own to find their **Margin**. 
* The winner deals damage based on that Margin. The loser deals *no damage*.
* In Case of a Tie: If both players roll the exact same number of successes, they strike each other simultaneously. The Margin is 0. Both characters deal damage to each other equal to their weapon rating (+ other modifiers like *Feral Weapons* or *Prowess*).

### 2. Defensive Actions & The Right to Defend
A character can **ALWAYS** roll to defend against an incoming attack unless the situation makes it absolutely impossible. Defensive options include:
* **Dodge (Dexterity + Athletics):** Evading fists, blades, or bullets (requires cover for firearms).
* **Block (Dexterity/Strength + Brawl):** Physically stopping a close-combat strike.
* **Parry (Dexterity/Strength + Melee):** Using a weapon to deflect an incoming close-combat attack.

**When Defense is Impossible:** A character cannot roll to defend if they:
* Are the victim of a successful **Surprise/Ambush** attack.
* Have declared an **All-Out Attack** (which sacrifices all defense for a single powerful strike).
* Are currently immobilized and held in a **Grapple** (more later).

**In Case of a Tie (Pure Defense):** If the opposed roll between an attacker and a purely defending character (Dodging, Blocking, or Parrying) results in a tie, the defender "wins" the contest. The attack is entirely avoided or deflected, and the defender takes zero damage.

### 3. Multiple Attackers & All-Out Defense
Every character is strictly limited to **one attack per turn**, meaning you can only Counter-Attack one declared target. For all subsequent attacks, you must roll purely to defend. 
* **The Defender Penalty:** Normally, facing multiple attacks is overwhelming. For every attack you face after the first one, your defense dice pool drops: 
    * *1st Attack:* Full pool.
    * *2nd Attack:* -1 penalty.
    * *3rd Attack:* -2 penalty (and so on).
* **All-Out Defense:** If a character declares during Phase 2 that they are taking an *All-Out Defense*, they forfeit their right to make any attacks or Counter-Attacks this turn. In exchange, their sole focus is survival, and they **do not suffer the multiple attacker penalty**. They roll their full, unpenalized defense pool against every single attack directed at them that turn.

### 4. Disciplines vs. Physical Attacks (The Parallel Resolution Rule)
If a character uses their turn to activate an offensive Discipline against someone physically attacking them, this is **not** treated as an Opposed Roll. They resolve in parallel:
* **Step A (The Physical Strike):** The physical attacker rolls their Conflict Pool. The Discipline user rolls to Defend (Dodge/Block/Parry). Damage is applied normally.
* **Step B (The Discipline):** Regardless of the physical damage taken (unless incapacitated/in Torpor), the Discipline power is rolled and resisted exactly according to its specific rules. 

---

## Phase 4: Damage Calculation

When an attack successfully lands, calculate the damage by strictly following these four steps in exact order:

### Step 1: Calculate Total Base Damage
* Take the attacker’s **Margin of Success** (the successes remaining after subtracting the defender's). 
* Add the **Weapon Modifier** (e.g., +2 for a knife, +3 for a sword, +4 for a heavy firearm). 
* *Result:* Margin + Weapon Modifier = Total Base Damage.
* If the Roll was a Tie (Attack vs Attack): The Margin is 0. Both characters take damage simultaneously. The Total Base Damage for each character is strictly equal to their Weapon Modifier (+ other modifiers like *Feral Weapons* or *Prowess*).
* If the Roll was a Tie (Attack vs Defense): If the defender was purely dodging, blocking, or parrying, they win the tie. The Margin is effectively negated, and the attacker deals 0 damage (weapon modifiers are not applied).

### Step 2: Apply Fortitude (Toughness)
*(Ref: V5 Corebook, pg. 258)*
If the defender has activated the Fortitude 2 power *Toughness* and is taking **Superficial** damage:
* Subtract the character's Fortitude rating from the Total Base Damage. 
* **The Minimum 1 Rule:** Toughness can never reduce the incoming damage to zero. If the damage drops below 1 during this step, it remains at 1.
* *(Note: Standard Toughness does NOT reduce Aggravated damage).*

### Step 3: The Halving Rule (The Vampire Default)
Because you are vampires fighting vampires, almost all physical damage (fists, blades, bullets) is considered Superficial. 
* **The Default:** Take the remaining damage from Step 2, **halve it, and round up**. 
* **Exception 1 (Unhalved Superficial):** Powers like the Protean *Feral Weapons* claws deal Superficial damage that is explicitly *not* halved. You take the full remaining damage from Step 2.
* **Exception 2 (Aggravated Damage):** If the attack is explicitly Aggravated (e.g., fire, sunlight), do *not* halve it, and remember that standard Toughness did not reduce it in Step 2. You take the full Total Base Damage.

### Step 4: Mark Health & Impairment
Apply the final damage number to the character's Health track.
* **Impairment:** If a character's Health track becomes completely filled with Superficial damage, they are **Impaired**. They suffer a strict **-2 penalty** to all physical dice pools. **This will apply to all the remaining rolls for the turn, if any.**
* **Torpor:** If a character's Health track becomes completely filled with Aggravated damage, they immediately fall into Torpor. Combat ends for them.

---

### Damage Calculation Example (The Corrected RAW Flow):
* **The Strike:** Player A shoots Player B. Player A wins the opposed roll with a Margin of 2. 
* **Step 1 (Total Damage):** Player A is using a Heavy Pistol (+3). Margin (2) + Weapon (3) = 5 Total Base Superficial Damage.
* **Step 2 (Fortitude):** Player B has activated *Toughness* (Fortitude 2) and subtracts 2 from the damage. *(Remaining damage = 3)*.
* **Step 3 (Halving):** Bullets deal standard Superficial damage to vampires. The remaining 3 damage is halved and rounded up. *(Remaining damage = 2)*.
* **Final Result:** Player B takes **2 Superficial damage** to their Health track.
