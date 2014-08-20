UpgradeableItemsKVBuilder
=========================

This script can be used to generate all the item levels and recipes for your items.
You just need to write the base level for the item and the script will generate the rest.

How to use:
--------------
- Drop make_upgradeable_items_kv.py in your "dota_ugc/game/dota_addons/YOUR_ADDON/scripts/npc/" folder
- Create the "upgradeable_items" folder in the same directory
- Drop one txt file for each item you want to parse
	- The txt should only contain 1 item
	- The first line of the txt must be the item name
	- You must include "MaxUpgradeLevel" and "ItemBaseLevel"
	- The "AbilitySpecial" section must be the last thing in the item
- Run "python make_upgradeable_items_kv.py" and you'll find the auto generated items in "upgradeable_items/_output/"

**Contact: tischeldota@gmail.com**
