# Neon Cue Club

8-ball pool in a late-night neon pool hall. It's 3D, built with Three.js, and runs in the browser as one HTML file.

## How to play

Clone or download this repo and open `index.html` in a modern browser (Chrome, Edge, Firefox or Safari). You don't need to install or build anything. It works on desktop and on phones.

## Game modes

- **Play vs Computer**: three opponents, from rookie to shark. Win to climb the club ladder.
- **2 Players**: take turns on the same device.
- **Practice**: a free table with undo and ball-in-hand.
- **Trick Shots**: 8 challenges. You get one shot to pull each one off, and fewer tries earn more stars.

## Controls

| Action | Input |
| --- | --- |
| Turn the cue | Drag on the table, or ← → / A D (hold Shift for fine steps) |
| Aim straight at a ball | Click the ball |
| Shoot | Drag the power bar down and release, or hold Space to charge and release |
| Spin | Drag the red dot on the cue ball. Low = backspin, high = follow, sides = english |
| Switch cue view / top-down view | V |
| Zoom | Mouse wheel / W S |
| Aim guide (long, short, off) | G |
| Pause | Esc |

## 8-ball rules

- The table is **open** after the break. Pot a ball to claim **Solids (1–7)** or **Stripes (9–15)**.
- Pot one of your balls and you shoot again. Miss, and it's your opponent's turn.
- **Fouls** give your opponent ball in hand: potting the cue ball, hitting nothing, or hitting the wrong group first.
- Clear your group, then pot the **8-ball** to win. If you pot it early or scratch on it, you lose.

## Settings

You can change the cloth colour, aim guide, sound effects, music and graphics quality.

## Built with

- HTML, CSS and JavaScript
- [Three.js](https://threejs.org/) for 3D graphics
- Web Audio API for sound
