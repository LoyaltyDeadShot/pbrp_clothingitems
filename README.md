# pbrp_clothingitems
Clothing as item script for QBCore &amp; illenium-appearance

Fisrt off, a HUGE shout out to @MrBluffz for the original ESX code https://github.com/MrBluffz

This is a simple script for doing outfits as items!

Don't forget to add the item name to your items.lua for use, add inventory pics & run the SQL

COMMANDS:

`/changeback` will allow you to remove your last used clothing item, and return it to your inventory.
Last used clothing will set back on ped after relog/server restart. 

NOTE:

The item will be removed on use. You can stop it from being deleted by removing the following line in server.lua:
`Player.Functions.RemoveItem(Config[i].itemName, 1)` 

Pull request are welcome & encouraged as I IDK WTF I am doing. 😕

PREVIEW:
https://streamable.com/etnwfd

TODO:
Animations (Feel free to PR!)
