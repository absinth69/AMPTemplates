Expanded BF2 configuration candidate. Not yet validated in AMP.

1. Upload the two JSON files and three .template files to the root of absinth69/AMPTemplates main.
2. Replace the existing App.UpdateSources line in battlefield2.kvp with the single line in REPLACE-App.UpdateSources.txt. Keep all other KVP settings.
3. Commit, Fetch Latest in ADS, and create a disposable test instance.
4. Set a strong unique RCON password before first game start. Restrict TCP RCON access.
5. Keep other BF2 games stopped if ports overlap. Start and verify generated files and gameplay.
6. Test map rotation and a gameplay-setting change before applying to production.

69 GUI fields: 66 existing native settings, map rotation, RCON port/password.
Defaults preserve our existing configuration, not a recommendation for every mode.
No private stats backend, ranked entitlement, ModManager, timed chat MOTD, ban editor or demo hosting is installed.
Port fields are manual and must match AMP allocations and firewall rules.
Current instances do not automatically receive the new GUI manifests.
Generated outputs overwrite direct manual edits when regenerated.
The RC2 archive stays unchanged; three source templates download separately afterward.
Source template downloads overwrite templates; the RC2 archive stage does not overwrite existing files.
Advanced legacy and mode-specific settings need testing before changes.
