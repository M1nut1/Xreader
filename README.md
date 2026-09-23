# 𝒳reader
𝒳reader is a tool to let people import multiple Deltarune mods without having to modify their data.win.

# How do I import mods?
There are 2 ways:

1) If your mod has an .xdelta then launch 𝒳reader.exe, enable auto-patcher unless you know what you're doing and select your DELTARUNE folder path. Finally, you can click the bottom "Convert .xdelta mod to .𝒳mod" and select the xdelta you want to import, the app will do everything by itself and then you can open Deltarune normally.
2) If your mod already has a .𝒳mod file then do the same thing as top BUT don't click the convert button, instead go to the DELTARUNE folder, go in "Xdelta" and directly drag your .𝒳mod file inside.

# Will my .exe and .win be modified?
Yes, but not exactly. 𝒳reader works by processing the .xdelta to .𝒳mod file and then creating a copy of itself replacing the vanilla DELTARUNE.exe, but don't worry, if something goes wrong it renames the original .exe to "DELTARUNE_vanilla.exe"
It works almost the same for the data.win, only if the game is running 𝒳reader will create a temporary data.win with the modified data inside, but if Deltarune stops then it deletes the modified .win and brings back the original one, even if you have a modified data.win!
