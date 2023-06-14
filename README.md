# Chrono Crush
A little dating sim with characters across past and future

Created by: Ben Daly, Cassidy Aydin, Brandon Jack, and Addison Camacho

Powered by: RenJS, created by lunafromthemoon

RenJS main page here: https://renjs.net/index.html 

## Playable Link

You can play our game by clicking this link!

https://mojius.github.io/chrono-crush/

## Documentation

### Prototypes

All of our prototypes can be found by following this link: https://github.com/ascamach/CMPM-120-Final-Game-Project

Please refer to the `README.md` file to play our different prototypes.

### Theme

The theme "Neabry in Space, Distant in Time" is expressed in our game through various character interactions with people from across time.
We have 3 characters that you can choose to interact with: Teddie, our present day character, Asellus, our character from the ancient times, and Thea, our futuristic character.
Although they are nearby in space, Thea and Asellus still don't fully understand your modern world, and so those interactions play around that idea.

### Selectable Requirements
Here are our three selectable Requirements for the game:
- Data-Driven Experience Progression
  - For Data-Driven Experience, our engine RenJS uses `.yaml` files to compile the game. There are 4 different `.yaml` files, however, the ones that apply to the requirement would be `GUI.yaml` and `Config.yaml`. These files set the bounds for certain assets as well as define functions for each asset in the game.
- Procedural Graphics
  - In the file `text_log.js`, we use the Phaser.Graphics class in order to set up the scene for our text log. We make an empty graphic to disable interaction with the main game's HUD, then create a text log of previous messages.
- Narrative Tech Integration
  - With RenJS, we use the `Story.yaml` file to write out our story. With different formats and commands for each line, certain story points in the game will feel more alive with the text on-screen.

### Contributor Credits
- Production Lead: Ben Daly
- Technology Lead: Addison Camacho
- Testing Lead: Cassidy Aydin
- Backup Production Lead: Brandon Jack

### Asset Credits
- Writing by Ben Daly
- Thea's and Teddie's images by Cassidy Aydin
- Asellus' images, menu logo, and background by Brandon Jack
- Music by Evan Schaeffer
- renjs default assets (GUI) by lunafromthemoon
