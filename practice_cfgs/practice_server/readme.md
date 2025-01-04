# blake++'s 4v4 PASS Time Practice Server.
Designed for easy access to a server used only for practice.

I'll probably put this up. Probably.

Rule 1: If someone is practicing, don't interfere without consent.

Shortcut Target:
```
...\srcds.exe -console -game tf +sv_pure 0 +map pass_arena2_b14b +maxplayers 6
```

### Includes
- p4sstime plugin + gamedata (obvi)
- Plugins from [2023 Offline Jump Pack](https://jump.tf/forum/index.php?topic=3294.0)
- rockthevote.smx (including a filled mapcycle.txt file)
- [Disable WFP VScript](https://gamebanana.com/mods/448996) in scripts/vscripts/
- Only STV+, tf2 comp fixes (+gamedata), improved match timer from [RGL Server Resources](https://github.com/RGLgg/server-resources-updater)

### Notes
- protected_cvars.cfg is a cfg file that has various game, rcon, STV, and fastDL passwords/links.
- Requires [pt_global_pug.cfg](https://github.com/p4sstime/p4sstime-server-resources/tree/main/cfg)