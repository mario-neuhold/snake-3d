# SNAKE³

A 3D Snake arcade game that runs entirely in the browser. No dependencies, no build step — just one HTML file with a custom canvas 3D renderer.

## Play

Open `index.html` in any modern browser, or visit the deployed URL.

## Controls

| Key | Action |
| --- | --- |
| `←` `→` / `A` `D` | Move left / right |
| `↑` `↓` / `W` `S` | Move forward / back |
| `Space` / `Q` | Rise |
| `Shift` / `E` / `Ctrl` | Dive |
| `Enter` | Start / restart |
| `P` / `Esc` | Pause |
| `M` | Mute |
| Mouse wheel | Zoom |

On touch devices, use the on-screen six-way pad.

The board is a 24³ cube. Eat the pink octahedron to grow and speed up; hitting a wall or your own tail ends the run. Your best score is saved in `localStorage`. Floor shadows and a heading arrow show where you are and where you're going.

## Deploy on Coolify

This is a static site:

1. In Coolify, create a new resource → **Static site**.
2. Select the GitHub repository `mario-neuhold/snake-3d`, branch `main`.
3. Leave the build command empty and set the output directory to `.` (the `index.html` sits at the repository root).
4. Deploy.

The app is connected through the `coolify-dev-2` GitHub App, so pushes to `main` deploy automatically.

No environment variables or packages are required.
