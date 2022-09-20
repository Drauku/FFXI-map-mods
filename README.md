# FFXI-Vision
## Map file overhaul for FFXI

- NOTE: As of 2021-Dec, if you use the map replacement `/ROM/119/*.dat` files on a current, updated client version, you might experience a client crash when maximizing the chat window. I cannot verify this bug, so YMMV. You may be able to fix the problem by using these files: [KenshiDRK/XiView/ROM/119](https://github.com/KenshiDRK/XiView/tree/master/ROM/119)

  If you want to use the modified map files on a current version client, consider using KenshiDRK's version instead of this repository: [KenshiDRK/XiView](https://github.com/KenshiDRK/XiView).

### Installation Options

There are two methods to install these modified maps into your FFXI client.

- Preferred method: [XIPivot](https://github.com/Shirk/XIPivot) is a dat replacement plugin available for both Windower and Ashita which allows a user to dynamically replace `.dat` files with custom versions. I advise searching for the plugin and following the setup guide. This is now the preferred method for using custom `.dat` files of any type.

- Manual method: Copy and Paste the ROM## folders directly into the `./FINAL FANTASY XI/` folder, replacing all files when prompted. This will OVERWRITE all the game dats with the updated map files.

DEPRECATED: Alternatively, if you use the Ashita launcher, you can install the "Dats" Plugin and use that Plugin to trick the FFXI client to thinking these .dat files are located in the ./FINAL FANTASY XI/ folder without actually replacing any game files. This method is preferred if you frequently update, or want/need to use some form of compatibility .dat files to play on a private server and retail at the same time.
