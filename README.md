# fnfmods
https://github.com/FunkinCrew/Funkin

## Libs
Download and intall https://haxe.org/download/version/4.1.5/

Download and install https://haxeflixel.com/documentation/install-haxeflixel/

Install extra required libs
```bash
haxelib setup;
haxelib --global update haxelib;
haxelib install flixel;
haxelib install flixel-addons; 
haxelib install flixel-ui;
haxelib install hscript;
haxelib install newgrounds;
```

Install `haxelib git polymod https://github.com/larsiusprime/polymod.git` to install Polymod.

Intall `haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc` to install Discord RPC.

Run `haxelib git flixel-addons https://github.com/HaxeFlixel/flixel-addons` in the terminal/command-prompt.
```bash
haxelib git polymod https://github.com/larsiusprime/polymod.git;
haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc;
haxelib git flixel-addons https://github.com/HaxeFlixel/flixel-addons;
haxelib install lime;
haxelib run lime setup;
```

Lime error when runnging setup
```bash
cp: /usr/local/bin/lime: Permission denied

To finish setup, we recommend you either...

 a) Manually add an alias called "lime" to run "haxelib run lime"
 b) Run the following commands:

sudo cp "/usr/local/lib/haxe/lib/lime/8,0,1/templates/bin/lime.sh" /usr/local/bin/lime
sudo chmod 755 /usr/local/bin/lime

Set MAC_USE_CURRENT_SDK to 1
```