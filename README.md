# Linux Command Tools
A bundle of scripts that can add, search, and delete custom Linux shell commands.

## Installation:
1. Download the latest .zip from the [Releases](https://github.com/SteveGaming62/linux-command-tools/releases).
2. Extract the contents of the .zip file.
3. Open a terminal window.
4. Cd to the path of the folder (Usually /home/username/Downloads/command-tools-1.0).
5. Run ``chmod +x install-tools.sh``.
6. Run ``./install-tools.sh``.
7. Wait for the process to complete.
8. Now the tools are ready! Follow the guide below to get to know the commands.

## Guide
> [!TIP]
> Try not to use file extensions for your commands for the best experience.

Command | Description | Usage
---|---|---
mkcmd | This simply creates a command off of a shell script. | ``mkcmd [script]``
rmcmd | This removes any command specified in /usr/bin. | ``rmcmd [command]``
upcmd | This updates an existing command using a file with the same name. | ``upcmd [command]``
fncmd | This searches all of /usr/bin for commands using the specified term. | ``fncmd [-an] [search term]`` -a will show everything in /usr/bin. -n will only show the amount of items found.
