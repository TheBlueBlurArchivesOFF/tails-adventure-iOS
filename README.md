<h1 align="center">
  Tails Adventure Remake
</h1>

Tails Adventure is a Sonic the Hedgehog spin-off game, released for the Sega Game Gear and featuring Tails in a solo role. As opposed to other Sonic titles with fast-paced gameplay, Tails Adventure is a Metroidvania-styled game with emphasis on exploration, collecting items and backtracking. It's a unique "hidden gem" of the series that couldn't get attention it deserves due to low popularity of Game Gear.

This release remakes the original Game Gear for iPhone devices, based on the original remake for Windows/Linux/Android by Mechakotik. Here's what changed in the remake:
- **Balance changes:** rebalanced gameplay, enemies and bosses, to make the game more challenging
- **QoL improvements:** responsive controls, pause menu, item hotswap, tired flying
- **Display support:** runs in any resolution and refresh rate, displays subpixels, allows adjusting internal resolution to "zoom out the camera"
- **Input support:** keyboard, gamepad & touchscreen input, rumble and analog stick support, customizable mappings
- **Save system:** automatic saving, convenient data select menu in Sonic 3 style

## Completion status

The game is fully playable and can be completed 100%. However, a few non-essential features from the original game are still missing:

- Items: Wrench, Sonic, Item Radar
- *Most* in-game cutscenes
- Hover pod bullet and fire attacks
- Tails idle animation
- Helmet rotated frames

## Original Releases

The original binary releases for Windows, Android and Linux (amd64) are available at [Releases](https://github.com/mechakotik/tails-adventure/releases). This fork ONLY contains the iOS version of the remake, which is based on the source code and the Android port.

## iOS Testing

This port has been so far ONLY tested on an iPhone 16 base model, with 128GB memory and iOS27 installed. Previous models and versions of the OS should work just fine, but we reccomend that everything is up to date. Like every iOS app currently, this is a 64-bit IPA -- it won't work on 32-bit devices.

The IPA file is also **unsigned.** You WILL need to sign the game yourself, either via a paid Apple Developer account ($99/year), a free Apple Developer account (only 3 sideloaded apps at once and weekly refresh), or sideloading apps (TrollStore, KSign, SideStore, SideInstaller etc.)

## Credits

**Mechakotik** - Developer of the Tails Adventure remake, based in C++ and released for Windows, Linux and Android.

**The Blue Blur Archives** - iOS optimization and touch layout options (exclusive to this fork).

**SEGA** - developers and publishers of the original Tails Adventure game.
