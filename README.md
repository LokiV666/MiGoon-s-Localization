## Installation instructions

1. Go to your War Thunder folder and open the file called config.blk.

2. Find the section titled "debug" within config.blk.

3. Within the debug section, add the line "testLocalization:b=yes". This must be a new line. It can be anywhere in the section, but adding it at the end is preferable. For example, this is what the debug section in my config.blk file looks like (you shouldn't copy this, this is just an example):

debug{
  screenshotAsJpeg:b=yes
  512mboughttobeenoughforanybody:b=yes
  enableNvHighlights:t="auto"
  netLogerr:b=yes
  testLocalization:b=yes
}

4. Launch the game. Once you have launched the game, a folder called lang will appear in your War Thunder folder.

5. Extract the files from "MiGoon-s-Localization.zip".

6. Drop the extracted lang file into your War Thunder folder. It will tell you that this is replacing an existing file. THIS IS OKAY. These modified localization.blk files do not remove any of the things already in the base file. They simply add this mod's files to the end of the load order so they will be read after the base game files, allowing the mod to work.

7. Launch the game. The mod should now be installed and working.
