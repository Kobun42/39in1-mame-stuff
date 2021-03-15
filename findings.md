# Findings
1. "demo-8-11k-s-adpcm.wav.xgz" from a hex editor in 16mflash.bin. Knowing the name, i'd expect it to be the menu music used for these boards.
2. All of the roms in xgz format with them following "xZIP" before a lot of data. This could be a lead to cracking the encryption.
3. More sounds ending with "-adpcm.wav.xgz" which are presumably the sound effects. As always, following "xZIP" like all other entries.
4. ".bmp.xgz" files which must be the icons for the games when selecting, no doubt.
