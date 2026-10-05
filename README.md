# Single-file Minecraft Demo

An experimental Minecraft-inspired voxel game in one self-contained HTML file.

## Run it

Download [minecraft.html](minecraft.html) using GitHub’s **Download raw file** button, then open it locally in a modern desktop browser with WebGL2 enabled. Click **Click to play** to capture the mouse.

No installation, build step, external libraries, or asset downloads are required.

## Controls

| Control | Action |
| --- | --- |
| WASD / mouse | Move / look |
| Space | Jump; hold to swim upward |
| Shift | Sneak |
| Ctrl, R, or double-tap W | Sprint |
| Hold left click | Break blocks; click to attack |
| Right click / middle click | Place / pick a block |
| 1–9 or mouse wheel | Select hotbar slot |
| E | Block and tool picker |
| F | Toggle flight |
| Escape | Pause and release the mouse |
| F3 / F1 | Debug information / toggle HUD |
| T / N | Cycle time speed / advance time |
| - / = | Decrease / increase render distance |

## Features and limitations

The file contains HTML, CSS, JavaScript, a WebGL2 renderer, procedural textures, and synthesized audio. It includes terrain, movement and collisions, block interactions, animals, and a day/night cycle.

This is an experimental recreation with approximations and possible bugs, not a complete implementation of Minecraft. World progress is not saved across reloads.

## License

Code is released under the [MIT License](LICENSE). Textures and audio are generated in code; no Mojang texture or audio files are bundled.

This is an unofficial fan-made demo, not affiliated with or endorsed by Mojang or Microsoft. Minecraft is a trademark of its respective owners. The code license does not grant rights to those trademarks.
