# blake++'s 4v4 PASS Time Practice Server Package
For quickly creating an easy 4v4 PASS Time practice server. Drag-n-drop in /tf/ in your server files.

Shortcut Target:
```
...\srcds.exe -console -game tf +map pass_arena2_b14b +maxplayers 6
```

## Commands
Speedo:\
`/speedo                // Turns speedo on/off`\
`/speedocustom          // Speedo color RGB value`\
SSA:\
`/ssa                   // Turns speedshot assist on/off`\
SyncR:\
`/syncr                 // Turns SyncR on/off`\
Tempus Spray:\
`/spray                 // Spray decal on surface; clear with r_cleardecals permanent`\
Show Keys:\
`/skeys               // Turn showkeys on/off`\
`/skeys_coords        // Toggle edit mode of skeys coords`\
`/skeys_colors        // Change colors`

### Includes
- [p4sstime plugin](https://github.com/p4sstime/p4sstime-server-resources/) + gamedata (obvi)
- Includes server.cfg that combines pt_global_pug as well as RGL cfgs (modified to remove conflicting/useless commands)
- Some plugins from [2023 Offline Jump Pack](https://jump.tf/forum/index.php?topic=3294.0) including speedo, speedshotassist, syncr, tempus_spray, jse_showkeys (+ translations).
- rockthevote.smx and mapchooser.smx (including a filled mapcycle.txt file) (included with SM but disabled)
- [Disable WFP VScript](https://gamebanana.com/mods/448996) in scripts/vscripts/
- [STV+](https://github.com/dalegaard/srctvplus)
- [tf2 comp fixes (+gamedata)](https://github.com/ldesgoui/tf2-comp-fixes)

### Notes
- JumpQOL is not included since it doesn't work (at least on Windows) and we don't use it for 4v4 PASS Time anyway. Similar thing for groundfix.
