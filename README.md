# projector-dog-game

A single-file HTML game for dogs who love chasing laser pointers. Point a spare projector at a wall (or floor), map the picture to a patch of it, and a squirrel scampers around for your dog to chase.

No install, no dependencies, works offline: open `index.html` in a browser.

## Setup

1. Connect the projector and make the browser fullscreen on it (`F`).
2. On first run you get a calibration grid with four yellow corner dots. Drag them onto the corners of the area you want to use (corner-pin / keystone mapping, so it works even when the projector is at an angle). Arrow keys nudge the selected dot, Shift for bigger steps.
3. Press `C` or `Enter`. Your layout is saved in the browser, so next time it opens ready to go. Press `C` again to recalibrate.

## Controls

| Key | Action |
| --- | --- |
| `1`-`5` | Critter: squirrel, mouse, beetle, butterfly, glow dot |
| `Up` / `Down` | Speed |
| `B` | Background: black or dim forest |
| `R` | "Catch" the critter: poof, stars, it respawns elsewhere (treat moment) |
| `C` | Toggle calibration |
| `F` | Fullscreen |
| `H` | Hide the on-screen help |

Click or tap: the critter darts away from the tap, or is "caught" if you tap it.

## Tips for the dog

- Projectors can't show black, so the area outside the critter stays dark. A dim room works best.
- Dogs see blues and yellows best, so the yellow glow dot and high-contrast critters read well.
- Keep sessions short, and let your dog "win" sometimes (`R`, then give a treat). Endless unwinnable chasing can frustrate dogs, which is the known downside of laser pointers.
- Keep the projector out of reach and don't let the dog stare into the lens.

## License

MIT
