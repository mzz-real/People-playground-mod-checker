# People-playground-mod-checker
Python scripts to check your people playground mods for viruses, and dismantle the virus.

First off, you need to use https://github.com/Nitro70/PPG-Mod-Enabler to even get your mods, this will put your mods in your people playground mod folder, automatically disable safe mode, and flag suspicious mods.
What does it do (modchecker.py)? Modchecker.py automatically checks your mods to see if they have a _Mod.cs file, if there is a _Mod.cs file, which is used for the payload, it automatically disables the mod.json (changes it to mod.json.VIRUS), and then it flags it as suspicous.
What about so3.py? It automatically takes the _Mod.cs and gives you the contents of the mod/the payload itself.
FYI, this was made with gemini.

Instructions on how to use:
Download modchecker.py
Put in your target directory your mods folder (Example: D:\SteamLibrary\steamapps\common\People Playground\Mods if you use a different drive.)
Run it,
It will show you the suspicious mods, you can do ctrl + f and put in mod.json.virus and you will find the mod that is a virus.
(Optional)
Download So3.py
Put it in your suspicious mod's folder
Run it
The final_payload_1.dll is the payload used in the virus.

Report any bugs to me (mzzreal on discord or u/defiant-print-6457 on reddit), And thank you for reading.
