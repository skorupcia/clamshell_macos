# MacOS Clamshell mode on battery power.

Propably most efficient way to save up your battery life on your Macbook machines. Really fast and kind usage, in the future I will add the difference between battery cycles usage with and without clamshell.

## Create "no-Sleep" shortcut to prevent macbook going sleep after closing the lid.

  1. sudo pmset -a sleep 0
  2. sudo pmset -a disablesleep 1
  3. sudo pmset -a displaysleep 5

<img width="614" alt="image" src="https://github.com/skorupcia/clamshell_macos/assets/136620461/c4ddee7a-4cbc-407a-9494-0c1e59ebc5de">



## Create "Sleep" shortcut to get back to default sleep settings.

  1. sudo pmset -a sleep 1
  2. sudo pmset -a disablesleep 0
  3. sudo pmset -a displaysleep 1

<img width="610" alt="image" src="https://github.com/skorupcia/clamshell_macos/assets/136620461/44e569c4-79c7-420b-9638-564536907702">

## Add shortcuts to menu bar simply dropping them to "MENU BAR" folder

<img width="299" alt="image" src="https://github.com/skorupcia/clamshell_macos/assets/136620461/5ce4606b-d8fd-40fe-9f42-defb5a93e3a2">


## TroubleShooting

1. Remeber to check "Run as administrator" box to run the commands with proper permissions.

## Links

Sleep iCloud link: https://www.icloud.com/shortcuts/e2dc776519b04decaff3c9935723b1b9

No sleep iCloud link: https://www.icloud.com/shortcuts/ebbaa6956a884cd590974aad6f7596ad
