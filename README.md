# PRISM REBOUND

[日本語 README](README_ja.md)

A compact pseudo-3D physics score-attack game created for **js13kGames 2026**.

Pull the cue ball, choose an angle and power, then release it into the table.  
Bank shots, elastic collisions and chain reactions build your score while the seven-color spectrum rewards varied breaks.

## Controls

- **Drag / Pull**: Aim and set power
- **Release**: Shoot
- **RETRY**: Restart the current stage without adding its score to the run total
- **NEXT**: Bank the current stage score into the run total and move to the next stage
- **NEW RUN**: After Stage 3, finish the current run and return to Stage 1
- **R**: Restart the current stage
- **Audio button**: Toggle sound

## Scoring

- **STAGE SCORE**: Score earned on the current stage
- **RUN TOTAL**: Combined score for the current 3-stage run
- Bank shots and longer chains increase scoring opportunities
- Breaking all seven colors grants the Spectrum bonus
- Each stage also keeps its own best score
- Completing Stage 3 records the best full-run total

## Stages

1. **ORBIT** — bank the arc
2. **CROSSCUT** — chain the cross
3. **GLASSHOUSE** — break the grid

## js13kGames build

The competition build is a ZIP containing only `index.html`.

Current build size is generated separately and must remain at or below **13,312 bytes**.

No external art, audio samples, libraries or network resources are required.  
Graphics, pseudo-3D projection, physics and audio are generated in-browser.

## Development

Built through AI-assisted prototyping and iteration, with game direction, playtesting and final decisions performed by the project author.
