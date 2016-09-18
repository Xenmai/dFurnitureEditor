# dFurnitureEditor

Staff pick as of: 2016/07/12 13:01:15 UTC-07:00 (67 days and 16 hours ago)

Denizen Version: Release Build #1623 

Script Version: 0.8.2

Description:

dFurnitureEditor is an inventory GUI based furniture editor (surprise!).
It lets you create and remove props, as well as add and tweak their model components, without even needing to open a script file. This is all done thanks to armor stands, and the changes take place as soon as you make them. No need for reloads.

Right now prop parts have 6 available values: their offset position relative to the prop center, their rotation angles, wether or not they are small (small armor stands render smaller items), the item they hold, wether or not the player can sit on them and wether or not they emit fire particles.

If you want to get some sample props to get you started, you can do so at https://github.com/Xenmai/dFurnitureEditor/blob/master/Samples.yml. Just feel free to copy and paste the contents of the file into your Models.yml file inside your dFurnitureEditor folder. WARNING: Stop the server before pasting the samples, save the file, and then start it again. Manually editing the file while the server is live can result in data loss due to rollbacks and overrides.

It still lacks polishing and documentation, and I'll most likely add more utilities to it as time progresses.

For any questions regarding this script, or anything else, feel free to ping me in the IRC.
Usage:

/dfe edit *opens the editor GUI

/dfe place Stool *places the prop named Stool at your current location

/dfe place Stool 0 *places the prop named Stool at your current location with yaw 0

/dfe remove Stool *removes the Stool at your current location 
