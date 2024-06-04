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

## How to Use
1. **Setting Up a New Adventure:**
   - Clone the repository.
   - Run the setup script to initialize the file structure.
   ```bash
   bash setup_structure.sh <directory_name>
   ```
2. **Start of Session Tasks**
    ```
    Please rehydrate our ongoing DnD adventure by scanning the repository using the `manifest.yaml` file to extract the current state. Follow these steps:
    a. **Read the Latest Journal Entry**:
        - Scan the directory listed under `journal_directory` in `manifest.yaml` for the latest markdown file to understand the most recent events.
    b. **Update Character Sheet**:
        - Read the file listed under `character_sheet` in `manifest.yaml` to get the current character stats and details.
    c. **Update Technical Files**:
        - Read the files listed under `experiences`, `locations`, `people`, and `missions` in `manifest.yaml` to understand the current state of the adventure.
        - Refer to the `manifest.yaml` file for schema hints and formatting guidelines.

    Thank you!
    ```

3. **End of Session Tasks**
    ```
    Please generate the end-of-session updates based on the following information:
    
    a. **Journal Entry**:
       - **Session Title:** [Insert Session Title Here]
       - **Overview:** [Provide a brief summary of the session.]
       - **Journey Log:** [Detailed account of the adventures and experiences.]
       - **Notable Events:** [List key events]
       - **Learnings and Reflections:** [Provide insights and reflections.]
       - **Next Steps:** [Outline plans and objectives.]
       - **Experience Gained:** Total experience points earned: [Insert Experience Points Here]
       - **Images:** [Describe images to be included]
    
    b. **Character Sheet Update**:
       - **Character Information:** [Provide updated character details]
    
    c. **Technical Files Update**:
       - **Experiences:** [Provide new experiences in the format: { "session_id": X, "date": "YYYY-MM-DD", "title": "Title", "description": "Description", "events": ["Event1", "Event2"] }]
       - **Locations:** [Provide new locations in the format: { "name": "Location Name", "description": "Description" }]
       - **People:** [Provide new people met in the format: { "name": "Person Name", "description": "Description" }]
       - **Missions:** [Provide updates on missions in the format: { "short_term": [{ "mission": "Mission Name", "status": "Status", "objectives": ["Objective1", "Objective2"] }], "long_term": [{ "mission": "Mission Name", "status": "Status", "objectives": ["Objective1", "Objective2"] }] }]
       - Refer to the `manifest.yaml` file for schema hints and formatting guidelines.
    
    Thank you!
    ```

## Adventure Narrative
The narrative of the campaign, titled "The Lost Forge of the Spellsmith," is detailed below. This adventure involves the quest to find an ancient forge of immense power, hidden within the ruins of an ancient city and guarded by a fanatical cult. The adventurers must gather knowledge and allies, face political tensions, navigate treacherous terrain, and overcome formidable foes to uncover the forge’s secrets.

For the full adventure details, see the [The Lost Forge of the Spellsmith README](./sample-adventures/the-lost-forge-of-the-spellsmith/README.md).

## Instructions for AI Assistance

### Accessing and Ingesting Files

To ensure accurate context and retrieval of all relevant files, follow these steps:

1. **Load Current Adventure First**:
    - Begin with the file specified as "current_adventure" in the manifest to provide context for the rest of the content.
    - Example: To access the current adventure, use the link provided in the manifest.

2. **Direct File Access**:
    - Always refer to the specific file links provided in the manifest for accurate content.
    - Example: To access a session, use the link: [Session 1](https://github.com/bodyhigh/Cindor-Exandria/blob/main/journal/Session_1.md).

3. **Read All Journal Entries in Order**:
    - Access each journal entry file in the order specified within the manifest or directory.
    - Ensure each entry is read sequentially to maintain the narrative flow.

4. **Content Summarization**:
    - Download and read the file content directly from the provided URLs.
    - Summarize the content accurately based on the actual text in the files.

5. **Avoid Generalizations**:
    - Do not make assumptions or generalizations about the content.
    - Stick strictly to the information provided within the files.

6. **Report Errors**:
    - If there's an issue accessing any file, report it immediately instead of generating content based on assumptions.

### Example Workflow

1. **Navigate to the Repository**:
    - Open the repository link: [Cindor-Exandria](https://github.com/bodyhigh/Cindor-Exandria).

2. **Load Current Adventure**:
    - Start with the file indicated as "current_adventure" in the manifest for initial context.

3. **Locate and Access Additional Files**:
    - Follow the paths specified in the manifest to find session journals, character sheets, and other relevant documents.

4. **Read Journal Entries in Order**:
    - Sequentially read each journal entry file as specified in the manifest or directory listing.

5. **Download and Read the Files**:
    - Use the raw file URLs to download and read the content, ensuring no details are assumed or fabricated.

6. **Summarize the Content**:
    - Provide summaries based strictly on the file content.

By following these instructions, future AI interactions should accurately access, summarize, and maintain continuity in the adventure logs.
