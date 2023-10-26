# Modifying and testing in a creative copy

[Home](../home.md)\
Previous: [Installation](installation.md)\
Next: []()

---

It is **highly recommended** to paste the build you want to recreate into a creative copy of your world or server for testing. You should do this to **make sure that it works** with your **version**, **server type**, and collection of **mods/plugins**.

## Creating the copy
When making the copy, make sure you **copy over the following aspects**, for the following reasons.
- **Game Version** - updates regularly change game mechanics, and as such, some builds may work on a specific version range.
- **Server Type** - forks such as **Spigot**, **Paper**, **Purpur**, etc, are very configurable, and changing these configurations is likely to modify vital mechanics that builds may rely on.
  - **Make sure to also copy over your configurations!**
- **Mods or Plugins** - some mods or plugins can modify game mechanics.

## Pasting the build
1. Ensure you are in **creative mode**.
2. Run the command: `/carpet fillUpdates false`
   - This will ensure that nothing is triggered (for example, observers) while pasting the build in.
3. Press `M` to **open Litematica's main menu.** Remember this keybind; it's central to Litematica.
4. **Navigate into the `Configuration menu`**, and then along the list of tabs along the top, **go into `Hotkeys`**.
5. Find the setting for `executeOperation`, either by scrolling down or using the search function. Set the keybind for this as desired. (Personally, I use `M` + `O`)
6. Navigate back to the main menu.
7. **Go into `Load Schematics`**.
8. You should be presented with an in-game file explorer in your schematics folder.
   - If you haven't put your `*.litematic` files in here yet, see this page: [Navigating the `.minecraft` folder](../auxiliary/navigating_minecraft_directory.md)
9. **Select the schematic you want to use**, and then **press `Load schematic`**.
10. Exit out of the menu. You should see a blueprint of the schematic rendered over the world. 
11. **Put the tool item into your hand**. By default, this should be a **stick**. You should see a lot of information appear in the bottom-left corner of your screen. 
12. Hold `Ctrl` and scroll until the tool information shows:\
`Mode [5/9]: Paste Schematic in world`. 
13. **Move your schematic to the desired location** by holding `Alt` and scrolling in the direction you want the schematic to move. 
14. Ensure you are still in the mode for pasting the schematic, and then use your `executeOperation` keybind to paste the schematic into the world.

## Testing the build

## Modifying the build for personal use

---

[Home](../home.md)\
Previous: [Installation](installation.md)\
Next: []()