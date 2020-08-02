# Rhythm-Game-CSVs

CSV files (formatted in UTF-8) that list playable songs + charts in different rhythm games.

Licensed under CC-BY-4.0

# Status

- :heavy_check_mark: Beatmania IIDX 16 EMPRESS + PREMIUM BEST
    - `iidx-16-empress-cs.csv`
- :part_alternation_mark: Beatmania IIDX 25 CANNON BALLERS
    - `iidx-25-cannon-ballers.csv`
    - Contains all CANNON BALLERS and SINOBUZ songs
    - Needs leftover songs from other styles
- :heavy_check_mark: Beatmania IIDX ULTIMATE MOBILE
    - `iidx-ultimate-mobile.csv`
    - Current as of July 22nd, 2020
- :x: DJMax Respect
    - Really want to do this one, what with the pandemic still happening
- :part_alternation_mark: Groove Coaster (PC)
    - `groove-coaster-pc.csv`
    - Needs to be updated for current updates (base game + DLC)
- :heavy_check_mark: Muse Dash
    - `muse-dash.csv`
    - Current as of August 1st, 2020
- :heavy_check_mark: Pump It Up Prime 2
    - `piu-prime-2.csv`
- :heavy_check_mark: Sound Voltex Booth
    - `sound-voltex-booth.csv`
    
# Repository Rules

These are the current rules the repository adheres to;

1. A rhythm game's CSV file is not created until the game is publicly available.
    - AKA this repo doesn't track song lists and charts for unreleased rhythm games.
2. The CSV files do _NOT_ track chart re-ratings across game updates.
    - If a new chart "Replaces" an old chart _but that old chart is still playable_, then the old chart is still tracked.
3. Song removals across game updates are tracked and their related game content (ex; charts) is tracked.
4. The CSV files are updated when the corresponding rhythm games get a new update. Song and chart additions regarding unreleased content are not tracked.
5. _For now,_ this repository only tracks songs and charts for commercially released rhythm games. Any additions or requests for Osu! beatmap and Stepmania song pack CSV files will be rejected.

If you have any qualms with these rules, create a **[New Issue](https://github.com/Michael-A-Berger/Rhythm-Game-CSVs/issues/new/choose)** and we'll discuss your proposal.

# Contribution Instructions

If you'd like to contribute to this collection, please follow these steps;

1. Fork the repository.
2. In your project fork, make the changes.
    - **Adding New Game File:** Create the CSV file and include as many included songs and charts as you can.
    - **Editing Game File:** Edit the specific information.
3. Commit the changes and push them to the `master` branch of your fork.
4. Create a **[New Pull Request](https://github.com/Michael-A-Berger/Rhythm-Game-CSVs/compare)** asking to merge the forked `master` branch into the original `master` branch on this repository.
    - In the pull request, please list the sources for your information (be they official patch notes or forums).

I will do my best to review new pull requests ASAP, although they may take me several days to get to.

# New CSV Addition Suggestions

If you are looking to add a new CSV file that tracks songs and charts for a rhythm game not already included in this reposiroty, these are my _personal_ suggestions for how to approach completing the task;

- Don't feel bad about taking the main bulk of your info from other websites. The only caveat I ask is that you list your sources for your information.
    - The best artists steal ideas and morph them into something new. Honest artists list their inspirations, and data is nothing but honest art.
- More information is better, but don't burden yourself with overkill details. Focus on the key elements (song name, chart ratings, BPM, length, etc) instead of superfluous details (song production tools, background artists, etc).
- If each chart has an in-game classification that groups it and other charts together (ex; "Basic", "Difficult", "Expert", "Challenge", etc), you should make each classification its own column in the CSV file.
    - If charts are not distinguished by any in-game classification (or if there exists multiple charts for the same classification), list their ratings in the same column but separate them by spaces (ex; song "Cool Tune" with the charts S11, S22, and S33 becomes "11 22 33" under the column "S").

# Sources

- Beatmania IIDX 16 EMPRESS + PREMIUM BEST
    - https://remywiki.com/CS_EMPRESS
- Beatmania IIDX 25 CANNON BALLERS
    - https://remywiki.com/Beatmania_IIDX_25_CANNON_BALLERS_Full_Songlist
- Beatmania IIDX ULTIMATE MOBILE
    - https://remywiki.com/CS_ULTIMATE_MOBILE
    - https://remywiki.com/CS_ULTIMATE_MOBILE/Arcade_Songs
- DJMax Respect
    - http://cyphergate.net/index.php?title=DJMAX_RESPECT:Tracklist
- Groove Coaster (PC)
    - (personal observations)
- Muse Dash
    - https://musedash.gamepedia.com/Songs
- Pump It Up Prime 2
    - http://www.piugame.com/piu.prime2/intro/pdf/PumpItUp_Prime2_FullSongList.pdf
    - http://www.piugame.com/piu.prime2/itemshop/stepShop.php
    - (personal observations)
- Sound Voltex Booth
    - https://remywiki.com/AC_SDVX

# To-Do List

1. Start DJMax Respect CSV
2. Add newest songs to Groove Coaster PC CSV
3. Complete IIDX 25 song + chart CSV