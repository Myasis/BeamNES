![logo](https://github.com/Myasis/BeamNES/blob/master/img/logo.png)


** Beam Plays NES Games

Sega released a ton of Mega Drive/Genesis games into packs onto steam that are wrapped up into a nice official emulator.

You have to download an emulator like: Nestopia.
Download link: http://www.emulator-zone.com/doc.php/nes/nestopia.html
You will also need to download the rom.

** Setup
It's not that easy to setup. These are the steps you have to complete to get it to work.

0. Make sure to have Python 2.7.11 installed
1. Get yourself [Nodejs](http://Nodejs.org) and Java
2. Download this project as a zip file
3. Unzip it.
4. Open a terminal/cmd in its folder
5. Enter npm install. This will install project dependancies
6. Write a config file in config/ called default.json follow the default.sample.json for a guide.
7. Open up your emulator and go to the keymapping!

We use 'I', 'J', 'K', 'L' for directions. '[' for start, ']' for select. The 'A' & 'B' buttons will be 'A' & 'B'.
If you want to typ things, you will have to pause the node!

** Beam plays NES:
Setup the emulator mapping like this:

![player controlls](Link to mapping)

** Use

1. Launch the rom on the emulator.
2. Set Beam to Interactive mode etc. (TODO: Once site is live)
3. Run the command prompt and move to your directory. Open up the index.js with `node index.js` or your Operating system's equivelant. 
4. If you see 'Connected to beam' your all good and can start playing.
5. If you see any messages or errors your setup may be incomplete or your config file may be missing or missconfigured. Refer to the default.sample.json config file to see how one should be layed out.
6. Leave the window open and it'll report button state changes.

** Games Tested
We've tested 'Final Fantasy I'.