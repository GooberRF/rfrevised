# Red Faction Revised
Red Faction Revised is an overhaul patch for the Red Faction (1) single player campaign. It is to be released episodically and as a modification for the game. RF Revised is more than a balance patch and less than a full remake. RF Revised will include a set of modified levels, new assets, and modified table files.

Guiding Principles
-----
- Remove universally recognized annoyances and/or shortcomings
- Resolve universally recognized balance issues
- Restore cut content where viable
- Expand use of geomod technology
- Bolster links to other games in the series and the wider universe as a whole
- Retain overall mood/feel of stock game

The project aims to keep overall scope managable while satisfying the guiding principles listed above. RF Revised will not implement every desired change, and will determine whether to implement specific changes or concepts based on an evaluation of feasibility, reasonableness, and overall value towards realizing the project's core goals and guiding principles.

Usage
-----
RF Revised requires Alpine Faction 1.1.0+
- Check out this repo to a directory named `rfrevised` in `RedFaction\mods\`
- Populate `.\src\_tools` as described in `Build Info` below
- Run `.\src\_build_all_packfiles.bat`
- Launch the Alpine Faction launcher and select `rfrevised` from the `Mod` dropdown at the bottom of the window.
- Click `Play`

Build Info
-----
- All packfiles are created with build batch files in `.\src` with file lists from the corresponding directory under `.\src`
- To build packfiles, you must include copies of the following tools in the `.\src\_tools` directory:
  - `ccrunch.exe`
