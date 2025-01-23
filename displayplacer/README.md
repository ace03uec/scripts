displayplacer scripts
=====================

These scripts use the (displayplacer)[https://github.com/jakehilborn/displayplacer] to move the laptop and monitor between different arrangements.

2 potential common laptop/monitor arrangements are :
1. The laptop to the left and monitor in front.
   - This configuration typically uses a keyboard and mouse
2. The laptop directly in front, with the monitor behind.
   - This configuration typically uses the laptop keyboard and mouse.

These changes can be written as a simple alias as well, but writing a separate script allows us to allow triggering the change via Raycast etc.

To use the scripts, make sure to first install displayplacer. 

```
brew install displayplacer
```

Then keep the laptop in the appropriate configuration and run 
```
displayplacer list
```

Copy the configuration showed at the end of displayplacer list to the script in your local.
Replace the appropriate script in the raycast folder as well, if used.
```
