# blake++'s 4v4 PASS Time Practice Server.
Designed for easy access to a server used only for practice.

I'll probably put this up. Probably.

Rule 1: If someone is practicing, don't interfere without consent.

Shortcut Target:
```
...\srcds.exe -console -game tf +sv_pure 0 +map pass_arena2_b14b +maxplayers 6
```

## Commands (TODO)

Speedo:
`sm_speedo 0/1           // Turns speedo on/off`
`sm_speedocustom # # #   // Speedo color RGB value`
SSA:
`sm_ssa 0/1             // Turns speedshot assist on/off`
SyncR:
`sm_syncr               // Turns SyncR on/off`
Tempus Spray:
`sm_spray               // Spray decal on surface; clear with r_cleardecals permanent`
Show Keys:
`sm_skeys               // Turn showkeys on/off`
`sm_skeys_coords        // Toggle edit mode of skeys coords`
`sm_skeys_colors        // Change colors`

### Includes
- [p4sstime plugin](https://github.com/p4sstime/p4sstime-server-resources/) + gamedata (obvi)
- Some plugins from [2023 Offline Jump Pack](https://jump.tf/forum/index.php?topic=3294.0) including speedo, speedshotassist, syncr, tempus_spray, jse_showkeys (+ translations).
- rockthevote.smx and mapchooser.smx (including a filled mapcycle.txt file) (included with SM but disabled)
- [Disable WFP VScript](https://gamebanana.com/mods/448996) in scripts/vscripts/
- [STV+](https://github.com/dalegaard/srctvplus)
- [tf2 comp fixes (+gamedata)](https://github.com/ldesgoui/tf2-comp-fixes)

### Notes
- protected_cvars.cfg is a cfg file that has various game, rcon, STV, and fastDL passwords/links.
- Requires [pt_global_pug.cfg](https://github.com/p4sstime/p4sstime-server-resources/tree/main/cfg)
- RGL cfgs have been edited to remove sv_pure changes since it screws things up.
- JumpQOL is not included since it doesn't work (at least on Windows) and we don't use it for 4v4 PASS Time anyway. Similar thing for groundfix.