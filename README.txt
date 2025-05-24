# SampleContentPatcherMod

1. I recommend downloading VSCode for editing the .json filese: https://code.visualstudio.com/ . VS code is basically a fancy text editor and I promise it will be worth it.

2. Edit the png files under the /assets folder to your heart's content.
  - NOTE: The base game portrait sprites are all 64x64. If you want to keep using
    128x128 you will need to scale up the sprite files by a factor of 2 before editing
    them. See /assets/Portraits/Robin.png for my example.

3. If there's any particular files under /assets that you don't plan to ever change, delete them and their corresponding entries in the content.json. By default I've included all Gav's Anthro Characters portraits. Nothing bad will happen if you simply leave them there.

4. Edit the manifest.json:
  - Fill your name/your mod name in every applicable spot
  - Every time you post a new version of your mod, be sure to increment the version number
    by one. So for now it's 1.0.0, next time make it 2.0.0, then 3.0.0, etc. You can get
    more complicated with version numbers if you want but that's the basics.

5. Test your mod by copying this whole folder into your stardew mods directory. Don't forget to delete old versions if needed.

6. Edit this README file to instead describe your mod/list credits/tell people how to use it.

7. Zip up this whole folder (using 7-zip or whatever) and post on nexus