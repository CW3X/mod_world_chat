# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
- Latest build status with azerothcore: [![Build Status](https://travis-ci.org/azerothcore/mod-world-chat.svg?branch=master)](https://travis-ci.org/azerothcore/mod-world-chat)
# World Chat

# Description
World Chat Module is a simple global ( faction or cross-faction ) chat for AzerothCore.

# Functionality
* How to chat?
    - .chat Message - This works for everyone, GM and players.

* How a GM can send a message to the other faction chat if cross-faction is disabled?
    - Use .chat command followed by the initial of the faction ( Example: For horde use .chath <Message> )
    
* How can i show or hide by gm status?
    - You can show your GM or DEV status by having .gm chat on and .gm on. Also you can be shown as a DEV if you have .dev on

# Commands
List of fully functional commands:
* .chat <$TEXT>
  - Used to talk on the World Chat
* .chat on
  - Used to enable World Chat
* .chat off
  - Used to disable World Chat
* .chata <$TEXT>
  - Used to talk for GM's to alliance faction ( so you can talk to the other faction when cross-faction world chat is disabled )
* .chath <$TEXT>
  - Used to talk for GM's to horde faction ( so you can talk to the other factions when cross-faction world chat is disabled )
  
# Installation
## Core Setup

To add the module follow the next steps:
1. Go into the folder <source_of_335>/modules
2. Clone the repository here.

On windows, open git bash and paste this command:
```
git clone https://github.com/wizzymore/mod_world_chat.git
```
On linux:

```
git clone https://github.com/wizzymore/mod_world_chat.git
```

## Database Setup
### Setting up commands
Open DB-Assembler and use the option 8) Import-customs

OR

Run the following sql file in your database: [this](/sql/world/command.sql)



## Server Config Setup
### On Windows
Modify the config : "WorldChat.conf" by your needs.
Edit the settings in the .conf file but keep both!

### On Linux
Navigate to /etc/ folder from your azeroth build files and execute this command:
```bash
cp WorldChat.conf.dist WorldChat.conf
```
Modify the config : "WorldChat.conf" by your needs.
Edit the settings in the .conf file but keep both!
## Start the server and enjoy
Done, you are ready to use the World Chat System! Go online and try it out!
