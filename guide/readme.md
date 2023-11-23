
# Pro Tips

### Steam:
We'll be switching to the performance profiling build of ARMA 3 as many report performance improvements.

First, make sure ARMA 3 is closed, along with its launcher.
Find ARMA 3 in your Steam library. Right click on it and then click on "Properties."

![Screenshot of ARMA 3 in a Steam Library being right clicked, with "Properties" highlighted.](guide/img/prof1.png)


On the left side, click on "Betas".
Switch "Beta Participation" to "profiling - Performance Profiling Build." Steam should start updating.

![Screenshot of ARMA 3's Steam properties, focusing on the betas section, with "Beta Participation" switched to "profiling - Performance Profiling Build."](guide/img/prof2.png)

When you're done, click close out the window.

### ARMA 3 Launcher Parameters:
We'll be editing the launch parameters in ARMA 3. A few of these will be skipped depending on your needs or your system.

Open ARMA 3 on Steam. It should bring up the launcher.
When the launcher opens up, click on "Parameters."

![Screenshot of ARMA 3 Launcher, with an arrow pointing at parameters](guide/img/params1.png)

Let's edit some of these. Make sure you're set to view "All Parameters".
You should enable:
- Basic
	- Show static backgrounds in Menu
		- Loads into the main menu faster by loading an image instead of a 3D background.
	- Skip logos at startup
		- Speeds up launching by skipping the intro logos.
- Advanced
	- Extra Threads:
		- File operations
		- Texture Loading
		- Geometry Loading
			- Enabling these will separate these threads out of the main ARMA 3 process, which may help performance on systems with multiple cores.
	- Enable Hyper-Threading*
		- * Lets a single core run multiple threads. This may improve or harm your performance. Experiment and measure framerate with this turned on or off.
	- Memory Allocator:
		- Switch this to "Windows allocator (system)"
			- Uses Windows' built in memory management, which usually performs better. May not do anything for your system.
	- Enabled Large-page Support
		- Manages larger memory loads and (allegedly) causes less stress to the TLB.
- Client
	- Server address:*
		- Input the server address here
	- Server port:*
		- Input the server port here
	- Server Password:*
		- Input the server password here
	- * You should only enable these if you mostly play on one server. Fill them out with the server information from Discord.
- Host
	- Server port:
		- This will auto enable then "Server port" in client is enabled.
- Author
	- No Pause
		- Keeps the game running when you tab out. Helps with stability as the game pausing and unpausing can lead to crashes.
	- No Pause Audio
		- Keeps the game audio running when you tab out. Helps with awareness and doesn't pop game audio when switching in and out of ARMA 3.
![Screenshot of ARMA 3 Launcher's parameter section.](guide/img/params2.png)

## In-Game Settings
The next settings will be done in-game. You should probably do these while logged in and playing on a mission/server or in the VR rooms.

### ARMA 3 Video Settings:
We'll be switching to "Fullscreen Window" (aka Borderless Window) display modes since the game crashes when tabbing out and in in Fullscreen.

Press ESC. Click on "Configure" then click on "Video."
![Screenshot of ARMA 3's ESC menu, with Configure expanded to show "Video."](guide/img/entvid.png)

Click on "Display" then click on "Display Mode" and switch it to "Fullscreen Window"
![Screenshot of ARMA 3's "Video Options", set to the "Display" tab.](guide/img/gradis.png)

### ARMA 3 Control Settings:
Press ESC. Click on "Configure" then click on "Controls."
![Screenshot of ARMA 3's ESC menu, with Configure expanded to show "Controls."](guide/img/entctrl.png)

#### Unmapping "Last Help":
We're disabling "Last Hint" as it tends to clash with the medical menus.

In the "Common" controls category, scroll down until you see "Last Hint" then click on it.
![Screenshot of ARMA 3's Controls menu, currently focusing in the "Keyboard" section, and mousing over "Last Help."](guide/img/lasthin.png)

Click on the "H" then click on "Delete", then click "OK."
![Screenshot of ARMA 3's Controls menu, in the process of unmapping "Last Hint"](guide/img/lasthintdel.png)

#### Unmapping "Throw":
We're disabling "Throw" as it usually gets bumped by accident and causes friendly fire. Instead, Shift+G will be used to throw.

At the top in controls, you should see "Show: Common."
Click on "Common" and switch it to "Weapons."
![Screenshot of ARMA 3's Controls menu, currently at the "Show" selector, which is in the process of being switched from "Common" to "Weapons"](guide/img/swiwep.png)

Scroll down until you see "Throw" then click on it.
![Screenshot of ARMA 3's Controls menu, currently focusing in the "Keyboard" section, and mousing over "Throw."](guide/img/lasthin.png)

Click on "G", click "Delete", then click "OK.""

You can alternatively bind it to "Gx2" by double tapping G while "G" is highlighted.
![Screenshot of ARMA 3's Controls menu, in the process of unmapping "Throw"](guide/img/lasthintdel.png)

### ARMA 3 Control Settings/Configure Addons:
We'll now focus on setting up and editing key binds for mods. At the bottom of the "Controls" settings, click on "Configure Addons."
![Screenshot of ARMA 3's Controls menu, with the mouse highlighting "Configure Addons" at the bottom.](guide/img/confaddons.png)

You'll be switching which addon's binds you're configuring by clicking on "Addon: (Name of addon)" then switching it to the addon you want.
![Screenshot of ARMA 3's Controls menu in the Configure Addons, currently at the "Show" selector, explaining how to switch addons.](guide/img/swiadd.png)

#### Enhanced Movement Rework:
We'll be editing Enhanced Movement Rework key binds. These are for climbing and safely dismounting buildings and other objects.

You should bind "All-in-one action" to Shift+Space and "Assist" to Alt+V, which is default. You can alternatively bind these to your preference.
![Screenshot of ARMA 3's Controls menu, configuring the keys to "Enhanced Movement".](guide/img/enhmov.png)

#### TFAR
We'll be removing all of the cycling hotkeys in TFAR as they conflict with another mod (CH View Distance) which is used more frequently.


Scroll down until you see "Cycle Next SR Radios" and click on it.
![Screenshot of ARMA 3's Controls menu, configuring the keys to "Enhanced Movement".](guide/img/tfar.png)

Delete all of the keybinds from "Cycle Next SR Radios" to "Cycle Previous LR Channel." You can quickly go from one to another by clicking "Next" above the keybind.
![Screenshot of ARMA 3's Controls menu, in the process of unmapping "Cycle Next SR Radios"](guide/img/tfardel.png)

#### WindowBreaker:
We'll be assigning a hotkey for WindowBreaker, which helps you, surprise, breaks windows.

You should bind "Smash" to "Shift+T."
![Screenshot of ARMA 3's Controls menu, configuring the keys to "Window Breaker".](guide/img/winbrk.png)