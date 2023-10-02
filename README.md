# Tools
This repo contains tools and scripts that I find nice to have on standby. Install all dependencies from 'installDependencies' for all tools to function.

git clone https://github.com/TotalKnob/tools.git ~/tools  
printf '\nexport PATH="$PATH:\~/tools"\n\n' >> \~/.bashrc  

## Root
* **dropCache** - Drops non-essential cache from memory, freeing up memory.
* **unswapPages** - Cycles swap to empty the whole swap.
* **upgradeAndClean** - Upgrades all packages, autoremove and clean.
* **startVsCodeAsRoot** - Starts Visual Studio Code as root.
* **cleanSnaps** - Removes old revisions of snaps.
* **fixTimeDualboot** - Sets system time to local for dualboot Windows/Linux.  

## Non-root
* **toClipboard** - Copies all input to the clipboard.
* **dockerStop** - Stops all active docker containers.
* **dockerContainerRm** - Removes all docker containers.
* **dockerPruneAll** - Deletes all images and containers on the system.
* **pythonUpdateAllPackages** - Upgrades all Python packages
* **unhideCursor** - Unhides cursor if hidden.

## My pc specific
* **fixCracklingSound** - Fixes crackling sound on HP Pavilion Gaming 15 cx0670nd on Ubuntu.

