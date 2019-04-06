Keen was nice enough to give us access to their devtools and their profiler, and with some downloading and file moving, you too can use this version of the game. This will allow you to measure the performance of your script to make sure it is running as fast as it possibly can.

## Getting started
You'll need to set up a few things before you can start using the profiling version.

First things first, is you'll need to download the ModSDK for the game. Open your Steam library, hovering your pointer over the "Library" button to get the menu. Select "Tools", and find "Space Engineers - Mod SDK" from the list, and install it. __Or__, you can just click [this link right here](steam://install/326880) to install the tool (If the link doesn't work, check the usual channels: Is it installed already? Do you own Space Engineers?)

Once the ModSDK has finished downloading an installing, you need to open the directory where it's installed (You can get to this quickly by right-clicking the tool in your library, selecting "Properties", "Local Files", "Browse Local Files...").

__Make sure you make a backup of your `Bin64` directory before you copy the files, to make restoring them easier.__ Open the `Bin64_Profile` folder from the ModSDK's install directory, select everything in this folder and copy all of the files to `Bin64` in your game's install directory, overwriting any of the files you're asked to.

### The short version
Here's how to install the profiling version of the game without all the extra fluff.
* Install the [Space Engineers - Mod SDK](steam://install/326880)
* Copy the ModSDK files in `Bin64_Profile` to the game's `Bin64` directory. __Replace all files in the destination__
* Start the game



## In the game

Once you're in the game, check the bottom left corner of the screen where you normally see the game's version number. You should see `PROFILING NON-OFFICIAL` in red text next to the game version if you did everything correctly.

Once you're in game, from the main menu, or in a loaded game world, you can press <kbd>F12</kbd>(or <kbd>Alt</kbd> + <kbd>F12</kbd> if you don't want to take a Steam screenshot) to open the debugging menu. Click on Performance at the top of the screen, and tick the box on the line next to "Profiler" to get the profiler view opened.

From here, you can use the various keybinds listed below to dig deeper into what's doing what in your game, see how long it's taking, and other _fun_ profiling things. For profiling programmable blocks specifically, you can copy the text below and then press <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>NumPad \*</kbd>..
`UpdateInternal::Update > Session.Update > Before simulation > MySector > MyGameLogic.UpdateBeforeSimulation > PROGRAMMABLE_BLOCK`

There are all kinds of debugging tools available in the profiler version of the game, but this page is only here to detail how to use the profiler specifically.


### Using the Profiler
Press <kbd>F12</kbd> in game (or <kbd>Alt</kbd>+<kbd>F12</kbd> to not make steam screenshot)
Select Performance tab
Check Profiler checkbox

Profiler has hidden controls explained on attached image.

To profile PB - You need to find your PB. It should be something like:
`Session.Update > Before Simulation > MySector > MyGameLogic.UpdateBeforeSimulation >  PROGRAMMABLE_BLOCK`

Run from terminal button will be somewhere in
`After update -> Handle input`-->



### Profiler Keybinds

The profiler has a lot of keybinds that aren't immediately obvious. They're listed here, grouped for convenience.

<table>
    <thead>
        <tr>
            <th>Key Combination</th>
            <th>Functionality</th>
        </tr>
    </thead>
    <tr>
        <td colspan="2"> <b>Profiler management</b> </td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad .</kbd></td>
        <td>Opens/closes the Profiler, doesn't reset the current profiler stack.</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad Enter</kbd></td>
        <td>Pause/unpause the profiler.</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>Insert</kbd></td>
        <td>Reset profiler data</td>
    </tr>
    <tr>
        <td colspan="2"></td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad /</kbd></td>
        <td>Decreases the level limit</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad *</kbd></td>
        <td>Increases the level limit</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>NumPad /</kbd></td>
        <td>Decreases the level limit by 1</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>NumPad *</kbd></td>
        <td>Increases the level limit by 1</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>E</kbd></td>
        <td>Toggle deep/shallow profile</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>E</kbd></td>
        <td>Toggle deep/shallow profile on connected DS</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>A</kbd></td>
        <td>Switch recording average times</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>A</kbd></td>
        <td>Switch recording average times on server</td>
    </tr>
    <tr>
        <td colspan="2"></td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>1</kbd>-<kbd>9</kbd></td>
        <td>Load profiler snapshot from file in `UserData/FullProfiler-X`</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>LCtrl</kbd> + <kbd>1</kbd>-<kbd>9</kbd></td>
        <td>Save profiler snapshot to file in `UserData/FullProfiler-X`</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>RCtrl</kbd> + <kbd>1</kbd>-<kbd>9</kbd></td>
        <td>Load snapshot from file and subtract it from current profiler data (diff)</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>LCtrl</kbd> + <kbd>1</kbd>-<kbd>9</kbd></td>
        <td>Save profiler snapshot on server</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>S</kbd></td>
        <td>Download current profiler data from server</td>
    </tr>
    <tr>
        <td colspan="2"><b>Profiler navigation</b></td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad 0</kbd></td>
        <td>Go back 1 block (Will open the profiler if it's closed, this is done for backwards compatibility with programmer muscle memory)</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad 1</kbd>-<kbd>NumPad 9</kbd></td>
        <td>Enter the next profiler block as usual</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>NumPad 1</kbd>-<kbd>NumPad 9</kbd></td>
        <td>Select block 10-19</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>Space</kbd> + <kbd>NumPad 1</kbd>-<kbd>NumPad 9</kbd></td>
        <td>Select block 20-29</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>Home</kbd></td>
        <td>Jump to root block</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad +</kbd></td>
        <td>Next thread</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad -</kbd></td>
        <td>Previous Thread</td>
    </tr>
    <tr>
        <td colspan="2" />
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>NumPad /</kbd></td>
        <td>Copy current profiler path to clipboard</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>NumPad *</kbd></td>
        <td>Try to navigate to the profiler path from the clipboard</td>
    </tr>
    <tr>
        <td colspan="2"><b>Profiler blocks optimization</b></td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>NumPad 0</kbd></td>
        <td>Toggles all child block optimization state</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>B</kbd> + <kbd>NumPad 1</kbd>-<kbd>NumPad 9</kbd></td>
        <td>Toggles block optimization state 1-9</td>
    </tr>
    <tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>B</kbd> + <kbd>NumPad 1</kbd>-<kbd>NumPad 9</kbd></td>
        <td>Toggles block optimization state 10-19</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> + <kbd>NumPad 1</kbd>-<kbd>NumPad 9</kbd></td>
        <td>Toggles block optimization state 20-29</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>B</kbd> + <kbd>NumPad Enter</kbd></td>
        <td>Toggles optimizations enabled/disabled</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>B</kbd> + <kbd>NumPad .</kbd></td>
        <td>Resets optimization on all blocks</td>
    </tr><tr>
        <td colspan="2"><b>Profiler display settings</b></td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Home</kbd></td>
        <td>Increase profiler scale</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>End</kbd></td>
        <td>Decrease profiler scale</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Insert</kbd></td>
        <td>Change profiler sorting order</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>NumPad +</kbd></td>
        <td>Increase local area (Used for calculating the average milliseconds)</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>NumPad -</kbd></td>
        <td>Decrease local area (Used for calculating the average milliseconds)</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Q</kbd></td>
        <td>Switch to alternative graph (Used for memory allocation profiling)</td>
    </tr><tr>
        <td colspan="2"><b>Profiler frame selection</b></td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>PageUp</kbd></td>
        <td>Go forward through frames</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>PageDown</kbd></td>
        <td>Go backwards through frames</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>PageUp</kbd></td>
        <td>Go forward through frames by 1 frame</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>PageDown</kbd></td>
        <td>Go backwards through frames by 1 frame</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>PageUp</kbd></td>
        <td>Fast forward through frames</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>PageDown</kbd></td>
        <td>Fast backwards through frames</td>
    </tr><tr>
        <td><kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>End</kbd></td>
        <td>Disable selection mode</td>
    </tr>
</table>


### Generally interesting paths

`UpdateInternal::Update > Session.Update > Before simulation > MySector > MyEntities.UpdateBeforeSimulation`
`UpdateInternal::Update > Session.Update > After simulation > MySector > MyEntities.UpdateAfterSimulation`

You can make use of these paths by copying the text from here, opening the profiler ingame and pressing <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>NumPad \*</kbd>.



_A big thank you goes to AndrielChaoti who was kind enough to compose this document._