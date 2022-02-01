# Release Notes

## Overview
**With each milestone, provide a _brief_ summary of the implementation that was completed.**

These notes should include what is done, how to launch/test it, and any known bugs. _(These release notes should also be included in the tag itself.)_

## Milestone 1
- Created HackNPlan 

- Created task division systeme for each milestone (Planned, In Progress, Testing)

- Accessed with the following link: https://app.hacknplan.com/p/112982/kanban?categoryId=0&boardId=291136

## Milestone 2
- Created external tool functionality: Basic grid of buttons that can be colored to correspond to different obstacles on the game's map.

- Tool exports to a txt file in the directory of user's choosing, exporting a grid of characters - each char corresponds to a different collideable object.

- txt grid is loaded into the main game as a map, using the object character placement in the grid to place different objects in the game world.

- No default map is present yet, but there will be a default and blank template for customization when the game is complete.

- Button grid size is dynamic based on the resolution the game will play at - can also be easily scaled using a scale variable to create more or less buttons in the length and width, for smaller or larger obstacles.

## Milestone 3
- Tiles in the exernal tool can be cleared in addition to being added 

- Fixed bug in file exporting that generated a text file whose content didn�t match that of the gid 

- While the file saved by the external tool can be named and placed anywhere, monogame currently only reads from a text file in the solutions folder named map.txt, so it has to be named that and placed there for the file generated by the external tool to work properly 


  
