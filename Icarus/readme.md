# Icarus Mods

## PackMule
Gives you a ridiculous caryy weight. Never worry about being over-encumbered again!

## NoFallDamage
Removes fall damage.

## PackRat 10000
All stacks to 10000


## Create Your Own Stack Mod

1. Install IMM (https://github.com/Jimk72/Icarus-Mod-Manager-Beta/tree/main)
   1. Follow IMM installation instructions
   2. Update Data Folder
2. From IMM folder, open data/Traits/D_Itemable.json
3. Copy the contents of that file
4. Create a new folder somewhere
5. Create a new folder in that folder called 'Traits'
6. Create a new file in the Traits folder and paste teh contents you copied earlier
7. Open the file in a text editor like notepad++, something that allows regex search and replace
8. Search and replace '"MaxStack": \d+' with '"MaxStack": 10000' or whatever number you want
9. Change the Defaults back to '"MaxStack": 1'
10. In IMM, 'Extract mod from folder'
11. When Icarus updates, check the updated filed to see if D_Itemable.json was updated. If so, do steps 2 then 6-10 again.
