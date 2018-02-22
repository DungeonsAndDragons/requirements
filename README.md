# Pre-development thoughts
### Word definitions
   - Adventure
     - World in which multiple characters live and act
   - Event
     - Causality chain of happenings in the adventure that are directly associated w/ each other
   - Session
     - Meeting of players representing characters with a specific GM
     - Multiple sessions may "process" one event
   
------------
### Data
   - Player
     - isGM
     - Characters
       - Notes etc.
       - Spells
       - Stats
       - Items
       - Backstory
       - Features
       - 3D Model
       - ... (everything in char sheet)
   - Session
     - Enlisted characters
     - Time (optional - might be determined later)
     - Notes
       - GM only
       - Player visible
     - Event summary
       - Written by players after the session is completed
   - Map
     - Shared player map
     - GM visible adventure map
     
### Workflows
   - Log-in
     - If GM gets to choose between player and GM mode (otherwise just player mode)
   - GM-Mode
     - Creates a session and assigns characters
   - Player Mode
     - Character management mode
       - Create and manage characters
     - Gets a list of sessions to which one of his characters was assigned
     - Opens a session
       - Shared map
       - Character sheets (own, other enlisted)
       
### Notes
 - Different adventures are represented by different servers
   - All details (chars, maps, items) are bound to the adventure
   
## Used technologies
A list of used technologies can be seen [here](technology.md)
