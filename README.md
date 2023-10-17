# Documentation for configurable-world-domination-game
## What is this project?
configurable-world-domination-game (or cwdg for short) is an open source, platform independant video game adaptation of the board game "Risk". It is, as the name implies, highly configurable and supports rules from various releases of the official rule book as well as many well-established house rules.

## How to play?
1. Make sure you have the latest JRE (Java Runtime Environment) installed.
   
2. Download the latest version of ```cwdg.jar``` from our Discord.
   
3. Double click to play.

### Hosting a server
1.
   a. To host a local server for LAN play, simply click "Host new game" from the main menu.
  
   b. To create an online server you should first open any TCP port in your router. The default port is 10836.
2. Specify a player amount, the rules and the port.
3. Click "Open lobby". Your server is now open and people may join.

### Joining a server
1. Click "Join game" from the main menu.
   
2.
   a. To join a local server enter "localhost" into the IP field and click on the "Join game" button.
  
   b. To join an online game enter the public IP of the host and the port number he specified for the server. By default this is TCP port 10836. Then, click the "Join game" button.

## Data storage
cwdg will store all save data to ```[USER_HOME]/.cwdg```

This means that for Windows it will by default use ```C:\Users\your_username\.cwdg```

And for Linux and macOS it will use ```/home/your_username/.cwdg```
