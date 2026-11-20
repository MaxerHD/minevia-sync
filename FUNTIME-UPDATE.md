Minevia 0.4.5 added a fourth mode, «FunTime», for the FunTime server (versions 1.16.5–1.21.11 accepted).
Since 0.4.6 the mode runs its own game version, 1.21.11; the other modes stay on 1.21.1.

The mode has its own instance `fabric-1.21.11-funtime` and its own list `manifest-funtime.json`.
It contains no Minevia mods. It has only rendering and FPS mods (Sodium, Iris, ImmediatelyFast, FerriteCore,
Dynamic FPS, Entity Culling, Mod Menu, YACL) and mods named in FunTime's allowed list on
https://forum.funtime.su/modifications (checked 20.11.2026): Jade, MiniHUD, Item Scroller, Chunks fade in,
Gamma Utils, Custom FOV, Opponent Armor Indicator, Do a Barrel Roll, wWaypoints, ItemLocks, ContainerSearcher,
Better Hitreg. Required libraries come with them.
The music player Overtone was added at the owner's request, but it only exists for 1.21.1, so the 1.21.11 mode has no music.

On first launch the mode copies settings, shader packs and resource packs from «Уютное выживание», never mods or worlds.
The list is built by `scripts/funtime-manifest.py`. Before adding a mod, check FunTime's allowed and forbidden lists:
the server bans forbidden mods at its checks.

Existing users run Minevia-Setup.exe once to get launcher 0.4.6.
