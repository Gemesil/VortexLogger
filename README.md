# VortexLogger
A simple minecraft plugin written by Ofek Buchnik that adds a bunch of useful logging methods and handles plugin-toplayer hotbar / chat text.

## Methods
- sendChat(Player p, String message, boolean withPrefix)
Sends a chat message to the selected player. if withPrefix is true, the message will appear after the server name that was set as the prefix. Plays a "ding" sound to the player.

- sendActionBar(Player p, String message)
Sends an action bar message to a selected player. Plays a "ding" sound to the player.

- snedNoPermsMsg(Player p)
Sends a preconfigured message that indicates a player lacks permission to use a command.

- sendAlert(String message, boolean withPrefix)
Sends a message that only shows up inside the server console.

- sendBroadcast(String message, boolean withPrefix)
Broadcasts a message in global chat.

- centerMessage(String message)
Center a piece of text, depending on its length, inside the player's chat box.
