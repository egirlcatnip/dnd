# Mara

![Character Portrait](mara_256x384.png)

| Attribute       |   Details    |
| --------------- | :----------: |
| **Race**        |    Human     |
| **Background**  |    Hermit    |
| **Class**       |     Bard     |
| **Subclass**    | ~~Unknown~~  |
| **Alignment**   | Neutral Good |
| **Level**       |     `1`      |
| **Proficiency** |      +2      |

## Ability Scores

| Ability | Score | Modifier | Proficient? | Modifier |  Save Bonus  |
| ------- | :---: | :------: | :---------: | :------: | :----------: |
| **STR** |   7   |   `-2`   |             |          |     `-2`     |
| **DEX** |  16   |   `+3`   |   **Yes**   |   `+2`   | 2 + 2 = `+4` |
| **CON** |  15   |   `+2`   |             |          |     `+2`     |
| **INT** |  12   |   `+1`   |             |          |      +0      |
| **WIS** |  17   |   `+3`   |             |   `+2`   |     `+3`     |
| **CHA** | `19`  |   `+4`   |   **Yes**   |   `+2`   | 4 + 2 = `+6` |

- `Modifier = (Score - 10) / 2`
- `Save Bonus = Ability Modifier + Proficiency Bonus`

## Combat Statistics

### Hit Points

| Remaining | Temporary | Total |
| :-------: | :-------: | :---: |
|   `10`    |           |  10   |

- `Total HP = Hit Die + CON modifier`

### Hit Dice

| Remaining | Total |
| :-------: | :---: |
|    `1`    |  1d8  |

- `Total = 1d8 + 1d8/level`

### Other Stats

| Stat                 | Modifier | Value  |
| -------------------- | :------: | :----: |
| **Armor Class (AC)** |   `+3`   |  `13`  |
| **Initiative**       |   `+2`   |  `+2`  |
| **Speed**            |          | `30ft` |

- `Armor Class = 10 + DEX + Defence (0)`
- `Initiative = 1d20 + DEX + Modifiers (0)`
- `Speed = Base Speed + Modifiers (0)`

## Skills

| Skill           | Ability | Modifier | Proficient? | Modifier | Save bonus |
| --------------- | :-----: | :------: | :---------: | :------: | :--------: |
| Athletics       |   STR   |   `-2`   |             |          |    `-2`    |
| Acrobatics      |   DEX   |   `+3`   |             |          |    `+3`    |
| Sleight of Hand |   DEX   |   `+3`   |             |          |    `+3`    |
| Stealth         |   DEX   |   `+3`   |             |          |    `+3`    |
| Arcana          |   INT   |   `+1`   |             |          |    `+1`    |
| History         |   INT   |   `+1`   |             |          |    `+1`    |
| Investigation   |   INT   |   `+1`   |             |          |    `+1`    |
| Nature          |   INT   |   `+1`   |             |          |    `+1`    |
| **Religion**    |   INT   |   `+1`   |   **Yes**   |   `+2`   | 1+2 = `3`  |
| Animal Handling |   WIS   |   `+3`   |             |          |    `+3`    |
| **Insight**     |   WIS   |   `+3`   |   **Yes**   |   `+2`   | 3+2 = `5`  |
| **Medicine**    |   WIS   |   `+3`   |   **Yes**   |   `+2`   | 3+2 = `5`  |
| Perception      |   WIS   |   `+3`   |             |          |    `+3`    |
| Survival        |   WIS   |          |             |          |            |
| Deception       |   CHA   |          |             |          |            |
| Intimidation    |   CHA   |          |             |          |            |
| **Performance** |   CHA   |   `+2`   |   **Yes**   |   `+2`   | 4+2 = `6`  |
| **Persuasion**  |   CHA   |   `+2`   |   **Yes**   |   `+2`   | 4+2 = `6`  |

## Weapons

| Weapon       | Proficient? | Modifier | Ability | Modifier | Attack Roll | Damage Roll |
| ------------ | :---------: | :------: | :-----: | :------: | :---------: | :---------: |
| **Thurible** |     No      |          |   DEX   |   `+3`   | 1d20 + `+3` |  1d4 `+3`   |
|              |             |          |         |          |             |             |

- `Attack Roll = 1d20 + Proficiency Bonus + Ability Modifier`
- `Damage Roll = Weapon's Damage Die + Ability Modifier`
-
  - _Note:_ Dagger can be thrown (range 20/60) or used in melee.

## Spells

| Attribute                |      Value       |
| ------------------------ | :--------------: |
| **Spellcasting Ability** |    `+4` (CHA)    |
| **Spell Save**           | 8 + 2 + 3 = `14` |
| **Spell Attack Bonus**   |   4 + 2 = `+6`   |
| **Spell Slots**          |  2 (1st level)   |

- `Spell Save = 8 + Proficiency Bonus + Ability Modifier`
- `Spell Attack Bonus = Proficiency Bonus + Ability Modifier`

- **Bardic Inspiration - Thurible Smoke (_Bard_)**
  - _Usage:_ Class feature
  - _Description:_:
  -
    - `You release a cloud of smoke from your thurible, affecting creatures of your choice within range.`
    - `Each target must make a CON saving throw minus your Spellcasting Ability.`
    - `On success, the target gains 1d6 Inspiration and is protected of half of the following damage while the effect lasts.`
    - `On fail, the target suffers a bad trip — they do not gain Inspiration, have disadvantage on WIS saving throws, and their movement speed is halved for the duration.`
  - _Duration:_ 10 minutes or until rest
  - _Type:_ `Bonus Action`

### Cantrips

- **Minor Illusion (Bard)**:
  - _Usage:_ Cantrip
  - _Description:_:
  -
    - `Create a sound or image of an object within range`
  - _Duration:_ Instantaneous
  - _Type:_ `Action`

- **Mending (Bard)**
  - _Usage:_ Cantrip
  - _Description:_:
  -
    - `Repair a single break or tear in an object`
    - `Object can be no larger than 1 cubic foot`
  - _Duration:_ Instantaneous
  - _Type:_ `Action`

### 1st Level Spells

- **Healing word** (Bard):
  - _Usage:_ Spell slot
  - _Description:_:
  -
    - `Heal target 1d4 + 4 (CHA)`
  - _Duration:_ Instantaneous
  - _Type:_ `Bonus`

- **Cure wounds** (Bard):
  - _Usage:_ Spell slot
  - _Description:_:
  -
    - `Heal touched creature 1d8 + 4 (CHA)`
  - _Duration:_ Instantaneous
  - _Type:_ `Bonus`

- **Sleep** (Bard):
  - _Usage:_ Spell slot
  - _Description:_:
  -
    - `5d8 hit points of creatures fall unconscious`
  - _Duration:_ 1 minute
  - _Type:_ `Action`

- **Disonant Whispers** (Bard):
  - _Usage:_ Spell slot
  - _Description:_:
  -
    - `WIS save or take 3d6 psychic damage`
    - `On fail, target must flee as a reaction`
    - `On success, target only takes half damage`

  - _Duration:_ Instantaneous
  - _Type:_ `Action`

## Species Traits

### Racial (Human) Features

| Feature                  | Description                   |
| ------------------------ | ----------------------------- |
| **Ability modifiers**    | All ability scores `+1`       |
| **Language Proficiency** | Speak `Common` and `Halfling` |

## Background (Hermit) Features

| Feature               | Description               |
| --------------------- | ------------------------- |
| **Skill Proficiency** | `Medicine` and `Religion` |
| **Tool Proficiency**  | `Herbalism kit`           |

## Class (Bard) Features

| Feature                 | Description                               |
| ----------------------- | ----------------------------------------- |
| **Ability Proficiency** | `DEX` and `CHA`                           |
| **Skill Proficiency**   | `Insight`, `Performance` and `Persuasion` |
| **Armor Proficiency**   | `Light`                                   |
| **Weapon Proficiency**  | `Simple` weapons                          |
| **Cantrips**            | `Minor Illusion`, `Mending`               |

## Equipment Proficiencies

- **Armor:** `Light`
- **Weapons:** `Simple`
- **Tools:** `Herbalism kit`

## Equipment & Inventory

### Gear

- **Weapons:** `Thurible`
- **Armor:** `None`
- **Clothing:** `Moravian-style kroj (worn)`
- **Adventuring Gear:** `Backpack`
- **Misc:** `Nothing`

### Currency

| Plat | Gold | Copr |
| :--: | :--: | :--: |
|  0   |  9   |  2   |

## Languages

| Language |
| -------- |
| Common   |
| Halfling |

## Appearance

- **Build:** Slight, somewhat undernourished
- **Skin:** Olive-tinted, smoke-stained
- **Hair:** Deep dark brown, often disheveled
- **Eyes:** Small, brown
- **Manner:** Slow, deliberate, faint aroma of ash and herbs
- **Distinctive Features:** Smoke-stained skin and hair, ever-present smell of
  incense
- **Attire:** Well-worn Moravian kroj

### Backstory

```
Mara once belonged deeply to the Church, but her whole world collapsed when it
was faith itself that betrayed her. Shortly after finding her husband, he was
wrongfully hunted down and condemned to death for heresy by formal decree. It
was an unbearably traumatic chapter of her past life. Her friends abandoned her,
the Church cast her out, and everything she knew fell apart. Left alone, shunned
by those she once saw as companions, she turned to the only thing that, sadly,
helped her forget — the azure vapors now soaked not only into her
once-respectable attire, but into her dark olive skin and tangled hair. Her
steps are no longer proud as they once were, yet in her heart still burns a
flame for Uyrik and a quiet conviction that the Mother has never truly left her
side.
```

## Session Notes

- _none yet_
