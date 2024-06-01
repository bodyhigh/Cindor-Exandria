# DnD Adventure Journal

## Overview
Welcome to the ongoing adventures of Cindor, the Fire Genasi Eldritch Knight. This repository is divided into three main sections:
- **Journal:** Chronicles of Cindor's adventures.
- **Technical Files:** Detailed records of the game state.
- **Adventure Narrative:** The structured narrative of the ongoing campaign.

## Journal
Each session is documented as a new chapter in the journal. The journal entries include summaries, important events, and images from the sessions.

## Technical Files
This section holds structured data about Cindor's character sheet, experiences, locations, people, and missions.

### Character Sheet
```yaml
name: Cindor
race: Fire Genasi
class: Eldritch Knight
level: 3
experience: 900
stats:
  strength: 18
  dexterity: 12
  constitution: 16
  intelligence: 15
  wisdom: 12
  charisma: 13
```

### Experiences
```yaml
session1:
  - encounter: Water wheel investigation
    experience: 200
session2:
  ...
```

### Locations
```yaml
- name: Water Wheel
  description: An old, abandoned water wheel.
  events:
    - session: 1
      details: Investigation revealed a hidden mechanism.
```

### People
```yaml
- name: Tharivol
  relationship: Companion
  events:
    - session: 1
      details: Helped investigate the water wheel.
```

### Missions
```yaml
short_term:
  - mission: Investigate the water wheel
    status: Completed
long_term:
  - mission: Uncover the secrets of the Age of Arcana
    status: In Progress
```

## How to Use
1. **Updating the Journal:**
   - After each session, create a new markdown file in the `journal` directory.
   - Add a summary of the session, include generated images, and note the experience gained.
2. **Updating Technical Files:**
   - Update the YAML files in the `technical` directory with new experiences, locations, people, and missions.
   - Ensure the character sheet is updated with any changes, including experience points and level ups.
3. **Images:**
   - Save session images in the `images` directory under a session-specific folder.

## Adventure Narrative
The narrative of the campaign, titled "The Lost Forge of the Spellsmith," is detailed below. This section captures the essence of the adventure, its key scenes, and the characters involved.

### Act 1: Rumors and Preparation
#### Scene 1: The Mysterious Tip
The Embered Hearth Tavern is alive with the warm glow of hearthfire and the lively chatter of its patrons...

#### Scene 2: Research and Allies
The Grand Library of Ashenwall stands as a testament to knowledge and history, its towering shelves filled with ancient tomes and scrolls...

#### Scene 3: Political Tensions
Emberhold is a city of contrasts, its opulent mansions standing in stark contrast to the run-down shanties...

### Act 2: Journey to the Ruins
#### Scene 1: The Road Ahead
The wilderness between Emberhold and the ruins is treacherous, filled with dense forests, rocky mountains, and eerie swamps...

#### Scene 2: Friendly and Hostile Encounters
Along the way, you find both friends and foes. Elara the Hermit, a wise old woman living alone in the woods...

### Act 3: Infiltration and Discovery
#### Scene 1: Approaching the Ruins
The ancient city’s outskirts are a maze of overgrown paths and crumbling buildings, bathed in the eerie glow of the setting sun...

#### Scene 2: Exploring the Ruins
The labyrinthine ruins are filled with ancient structures and magical anomalies. The walls are covered in runes and murals...

### Act 4: The Forge and the Showdown
#### Scene 1: The Heart of the Forge
The inner sanctum is a grand chamber dominated by the ancient forge. Rivers of molten metal flow through channels in the floor...

#### Scene 2: The Cult’s Final Stand
In the forge chamber, the cult leaders are performing a dark ritual, their voices rising in a crescendo of power and madness...

### Act 5: Legacy and Future Adventures
#### Scene 1: Aftermath and Decisions
With the cult defeated, the forge’s secrets are yours. The air is filled with the scent of victory and molten metal...

## AI Integration
Use the persona file to iterate on the AI's behavior, ensuring it tracks the player's progress, assigns experience, and notifies about leveling up. The play style should emulate a Critical Role session.

## Persona File
Refer to the `persona_file.yaml` in the `persona` directory for AI instructions and persona details.
