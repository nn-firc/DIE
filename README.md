This project is aimed to improve the leaked CS:GO code, to make it more stable and to make it playable.
Use resources from CS:S to get the HUD and GameUI to work properly.

Partially used code from https://github.com/SwagSoftware/Kisak-Strike (some econ stuff, weapon recoil).

Download:
- CSGO SteamAppID: `730`
- CSGO DepotID: `731`
- CSGO ManifestID: `7043469183016184477`

Features:
- Removed Scaleform;
- Filesystem from TF2 leak (less hardcoded stuff, allows for 'custom' folder, etc);
- Some VGUI stuff and complete GameUI ported from TF2 leak;

Currently known bugs:
- sv_pure is most likely broken due to differences between CS:GO and TF2 implementations;
- Game currently crashes after shutting down;
