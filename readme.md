# A19 Modlet Template

This is a sample modlet template for modders to use. 


# How do I get the modlet template to work?

To get the modlet working, there are one of two ways depending on whether you're using DMT.

## Not using DMT (Most of you will probably not use it or need to do so):
- Find your 7 Days to Die game folder. On windows, it should be in ```Program Files (x86)/steam/steamapps/common/7 Days to Die/```
- Once in this folder, create a new folder called 'Mods' (MUST have capital 'M' to work)
- Paste the Modlet Template into this new Mods folder.
- Launch game.

## Using DMT:
- You will have specified a folder where all your mods are loaded. Simply paste the Modlet Template into the folder.
- Refresh mods in DMT and it should now appear.
- Tick the modlet and Build.
- Launch game.


# How to change the name of my modlet?
- Change the modlet name on the template folder. For example, 'ModletTemplate' could become 'Furniture Overhaul'.
- Open modinfo.xml and change the name here too. This is required for DMT to see the change too so anyone building your mod in DMT will need this.


# I'm not using anything in a certain folder. Can I remove it and all these readme files?
- Yes you can. Removing stuff that you don't need is good practice and will make your modlet smaller, faster to download, and less resource intensive.
- If not using any new images or icons, delete 'UIAtlases'.
- If not using any new models, sounds, or textures, delete 'Resources'.
- If not using DMT, delete 'Harmony', 'PatchScripts' and 'Scripts'.
- If not using some of the XMLs in Config, delete the unused ones.
- Also feel free to delete the readme.md as it's not necessary for your modlet.
