# Steam Chuff Reducer

# What is this?
A small tool for the game Railroader.
The intention was to see if I could reduce the performance impact of the steam engine particle effects.
I figured I could just make it configurable so people can adjust it to what they want.

Settings are available from Preferences -> Mod Settings -> SteamChuffReducer.
You need to have a game loaded first. The Particle effect option in Graphics settings must also be enabled, and currently you need to restart the game after enabling it.
You can change the settings on the fly, and enable/disable the mod without any limits.

The game seems to have an upper limit to how many particles can be present at the same time, if you overdo it on Rate or Lifetime particle production will "stop".
Lower these settings and wait for a bit and they will come back.

For improving framerate, it seems lowering Size and Lifetime has the best effects.

# New in v1.1:
- Includes a bandaid fix for RR-324 "exhaust smoke disappears in notch 7 & 8", can be used without enabling any other functions of this mod.
- Ability to customize diesel smoke effects separately from steam smoke effects
- Ability to change the animation curve values for the particle effects, giving interesting options
- Ability to set custom color values for particle effects

# How to install?
You will need to get Zamu's Railloader from https://railroader.stelltis.ch/, install following the instructions there.
When that is done, drag this .zip onto Railloader.exe.

# What about multiplayer?
Should work fine in multiplayer, host does not need this installed to work.
![image](https://github.com/wexp/RR-SteamChuffReducer/assets/16766593/930a0554-5b67-409d-952a-1bdc3092a192)
