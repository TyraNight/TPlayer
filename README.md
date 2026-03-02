🎵 TPlayer

TPlayer is a lightweight music player for the R36S, built with Love2D.
It supports MP3, FLAC and OGG Vorbis, displays cover art and metadata, and includes analog seek using the left thumbstick.

This project started as a personal challenge:

“What if I turned a retro console into a functional portable music player?”

✨ Features

🎧 MP3 support
🎧 FLAC support
🎧 OGG Vorbis support
🖼️ Embedded cover art (ID3v2 APIC)
🏷️ Title & artist metadata support
🎮 Analog seek (progressive rewind / forward with left thumbstick)
🔊 Volume control via D-PAD
🔒 Planned lock mode (to prevent accidental button presses in pocket use)
🎨 Dynamic background color based on cover artwork
🖼️ Custom default "no cover" placeholder

🎮 Controls

Button	Action
A	Play / Pause
D-PAD Left / Right	Previous / Next track
D-PAD Up / Down	Volume up / down
Left Stick	Analog seek (rewind / forward)
START	Quit

📦 Installation (R36S)

Download the release archive.
Extract the files.
Copy:
tplayer.sh
tplayer folder
into: 
Easyroms/ports

📦 Launch TPlayer from the Ports section.

Add your music files into:
tplayer/gui/music/
There is no track limit.

📁 Supported Formats
*.mp3
*.flac
*.ogg

📌 Changelog
v1.1

Added analog seek using left thumbstick

Added FLAC support

Added OGG Vorbis support

Improved default "no cover" image

Fixed crash when using D-PAD with no music in folder
