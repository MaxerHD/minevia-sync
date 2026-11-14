Minevia 0.4.3 adds a third game mode, «JoJo: Уютное приключение», for Fabric 1.21.1.

The mode inherits the full «Уютное выживание» mod list and updates from its existing
manifest. On first launch it copies the local cozy mode's mods, resource packs,
shader packs, shader settings, controls and mod configurations into its own
`fabric-1.21.1-jojo` instance. Worlds stay separate.

JoJo Stands 1.92 is downloaded directly from Modrinth and checked against its
SHA-512. A small bundled MIT compatibility addon fixes the old `grass` block
identifier and the invalid texture path in the D4C model.

Validation: six automated checks; three-mode UI tested at 980×620 and 1120×700;
an isolated Minecraft client started with the cozy mods, JoJo and the addon.
Full ability progression and multiplayer have not been tested.

Existing users can run Minevia-Setup.exe once to download launcher 0.4.3.
Launcher source is provided in `source/minevia-launcher-source.zip`.

Commit message:

    Add JoJo mode with cozy mods, packs and settings

    Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com>
