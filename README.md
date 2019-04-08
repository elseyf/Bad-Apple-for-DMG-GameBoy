# Bad-Apple-for-DMG-GameBoy
Bad Apple Demo for the DMG GameBoy System - by el_seyf

Demonstrates video playing capabilities of the GameBoy

The Video is encoded to 160x72 pixels, playing at 15fps and is streched to fit the screen (An empty bar of pixels was added to each frame to evenly fit into 10 tiles vertically, this is required due to how the frames are encoded).
Frames are compressed with standard LZ4 compression. Decompressing a frame is handled in 3 frames (max), tile tranfers in 1 frame.
The full video is fit into 1MB of ROM space
