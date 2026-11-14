Hello! Thanks for checking this project out!

If you want to use it, you should remember that:
- 1: Make the script executable
     You can do this by typing `chmod +x ./path/to/simpleroot.sh`
     If it fails, try running it with root privileges, like this:
     `sudo chmod +x ./path/to/simpleroot.sh`
- 2: You need to type the correct mountpoint
     For example, if your target filesystem is mounted at `/mnt/gentoo`:
     `Where is your target filesystem mounted? (default is /mnt): /mnt/gentoo`
- 3: You need to run the script as root 
     Check by typing `whoami` in a terminal
     If it does not say `root`, type `sudo ./simpleroot.sh`. 
     If you already are root, drop the `sudo`! It isn't needed.

