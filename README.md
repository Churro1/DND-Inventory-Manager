# DND-Inventory-Manager
D&D Inventory & Campaign Manager – A tool to track character inventories, manage campaign notes, and organize game sessions efficiently. Features include item tracking, party management, and session logs. Built for DMs and players alike!


# DND Inventory Manmager (I can't bring myself to change it...)

## General Description
This application is aiming to be a D&amp;D group's new best friend! It is going to be a convenient and easy way for players to manage their character sheets without having to constantly erase information, as well as displaying information about all their items from the D&amp;D Handbook so they dont have to look anything up! DMs will also have tools to manage their sessions and campaigns, and can take notes for a session or for the campaign overall to give to the players so everyone can have the same information!


## Feature List 
### Must Have Fetures 
- Log in
- Helpful Character Sheets
    - Have the most important information available by default.
    - Name, backstory, class & level, Race, alignment, XP etc.
    - Individual campaign notes.
- Inventory management
    - API to tell what everything does
    - Custom items are available too
- Highlight equipped weapons / Armor
- Money conversions and tracker
- DM has access to party members
- DM has campaign notes that are available to be viewed by all.  


### Nice to Have Features
- Modules on character sheets so they are personalizable
- Audio transcription that will give a written summary 
- Items in categories (So I can look at all healing items with one search)
- Auto update AC and attack bonuses based on equiped items
- Character sheet creation helper (Auto math some stuff)
- Party management (Trade items between party members, view other character backstory as made available)


## Technical Challenges
- Having both a DM and an adventurer side of things might be hard, so we will have to learn to make sure that if statement works haha. 
- Viewing and editing permissions based on Player or DM and cmapaign. 
- Having people be able to see other peoples stuff depending on campaign. 
- We will need to learn to use this API to get descriptions of items. 

Link to website -> https://www.dnd5eapi.co/

API Link -> https://www.dnd5eapi.co/api/2014/



## Requirments

1. This application will be using React as the front end to quickly and dynamically display user input for changes in the users' character sheet, to display the campaign and session information for the DM, and for the UI. Django will be used to store the relevant data in a database and for authentication.
2. There will be a landing page that will welcome users and ask them to sign in, the login page, the "Players" page that will allow players to manage their character sheet, inventory, manage personal notes, view session notes, etc., and a "DM" page that will allow the DM to view information about each group's characters, and to manage their session and campaign notes.
3. We will require a log in system. Each user will be able to have multiple characters and campaigns
4. This application is attempting to solve the issue of having to manage a D&amp;D character sheet on paper, something that can be very tedious, as well as helping the DM organize their sessions and campaigns easily, and giving players and DM's unified session and campaign notes.
5. There will be common CSS and styling through out. Each page will be similar in look and style to feel unfied.
6. Each user will be able to have multiple characters and campaigns that will be saved. each of these may have any number of items, quests, notes, etc. 


## Group Members

- Group 1

- Charlie Miner 
    - A02325182
- Chadler Neeley
    - A02429680