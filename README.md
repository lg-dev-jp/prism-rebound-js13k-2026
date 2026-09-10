# PRISM REBOUND

[日本語 README](README_ja.md)

A compact pseudo-3D physics score-attack game built around one satisfying shot, seven colors, and the chain reaction that follows.

Pull back the glowing ball, choose your angle and power, then release. Bank it off the walls, break colored targets, and turn collisions into long, satisfying chains.

## Play

https://lg-dev-jp.github.io/prism-rebound-js13k-2026/

## Controls

- **Drag / Pull**: Aim and set power
- **Release**: Shoot
- **RETRY**: Replay the current stage without adding its score to the run total
- **NEXT**: Add the current stage score to your run and continue
- **NEW RUN**: After Stage 3, finish the current run and return to Stage 1
- **R**: Restart the current stage
- **Audio**: Toggle sound

## Scoring

Build your **STAGE SCORE** with breaks, banks, and chains.

Break all seven colors to earn the **Spectrum bonus**, then carry your score through three stages and aim for the highest **RUN TOTAL** you can.

Each stage keeps its own best score, and completing Stage 3 records your best full-run total.

## Stages

1. **ORBIT** — bank the arc
2. **CROSSCUT** — chain the cross
3. **GLASSHOUSE** — break the grid

## Sound & 13KB

PRISM REBOUND was designed to feel good even between shots.

The music and sound effects are generated procedurally in the browser with Web Audio, with soft looping music, light popping impact sounds, and musical collision tones that react to the action.

No external images, audio files, or libraries are used. The graphics, pseudo-3D projection, physics, and audio all live inside the 13KB game.

The js13kGames submission ZIP contains only `index.html` and stays within the **13,312-byte** limit.

## Development

Created for **js13kGames 2026**.

Built through AI-assisted prototyping and iteration, with game direction, playtesting, and final decisions performed by the project author.
