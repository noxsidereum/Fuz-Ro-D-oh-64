# Fuz Ro D'oh for Skyrim Special Edition GOG

A fork of https://github.com/shadeMe/Fuz-Ro-D-oh-64 with a few patches to make it work with GOG Skyrim.

Build it yourself or use the compiled DLL I've provided in the release page.

How to install the compiled DLL:

 1. Download official Fuz Ro D'oh for 1.6.640 (i.e. Fuz Ro D'oh 2.3) from shadeMe's page at https://www.nexusmods.com/skyrimspecialedition/mods/15109
 2. Install it as you usually would using MO2, Vortex or manual extraction
 3. Overwrite the official Fuz Ro D'oh.dll that came with the mod (typically located in the mod's folder at SKSE/Plugins/Fuz Ro D'oh.dll) with the unofficial 1.6.659 (GOG) compatible Fuz Ro D'oh.dll provided here.
 
**Important:** after downloading, rename "Fuz.Ro.Doh.dll" to "Fuz Ro D'oh.dll" (i.e. same name as the official mod). Github isn't accepting an apostrophe in the filename for some reason.

Not extensively tested, but seems to be working. I have confirmed that:

  1. the mod loads correctly with the Skyrim GOG version (see Fuz Ro D-oh.log in Documents/My Games/Skyrim Special Edition GOG/SKSE)
  2. _(having turned off dialogue subtitles in the Skyrim settings menu)_ when you talk to the NPCs Ralof and Hadvar, as they appear in the cave near Helgen with the alternate start mod, the mod correctly kicks in, recognising their dialogue is unvoiced, and displays subtitles and quirky lip movements so you can actually follow the conversation.

If I encounter any major issues with this version as I continue playing, I will likely fix and post another release. Otherwise not: my goal has been to get something that works with my modlist. If it works for you too, great. If not, wait for shadeMe to provide an official GOG version.

-- noxsidereum @ 8 nov 2022
