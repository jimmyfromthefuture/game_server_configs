# game_server_configs
Using this to store dedicated server config files so we don't have to research them everytime we go through this.

Use git client to pull down the repo on the server.
From your game server either configure the server/startup to point directly at the file in the git repo, or you can use a symlink.

Use the command below from a cmd prompt to make a symlink in windows:
- mklink [new link] [source file]
