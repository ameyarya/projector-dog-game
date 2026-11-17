# projector-dog-game

A single-file HTML game for dogs who love chasing laser pointers. Point a spare projector at the floor (or a wall), map the picture to a patch of it, and glowing burrows appear. The grass rustles at a random hole, a squirrel leaps out and sprints across the floor (with decoy turns and sudden freezes) for your dog to chase, then dives into a different hole and vanishes. A moment later it pops out of another one. There are also two other modes: a simple pop-up whack-a-mole style game, and a roam mode.

No install, no dependencies, works offline: open `index.html` in a browser.

## Setup

1. Connect the projector and make the browser fullscreen on it (`F`).
2. On first run you get a calibration grid with four yellow corner dots. Drag them onto the corners of the area you want to use (corner-pin / keystone mapping, so it works even when the projector is at an angle). Arrow keys nudge the selected dot, Shift for bigger steps.
3. Press `C` or `Enter`. Your layout is saved in the browser, so next time it opens ready to go. Press `C` again to recalibrate.

## Controls

| Key | Action |
| --- | --- |
| `M` | Cycle game: chase (default), burrows (pop-up), roam |
| `1`-`4` | Critter: squirrel, mole, bunny, glow dot |
| `Up` / `Down` | Speed |
| `B` | Background: black or dim forest |
| `R` | "Catch" the critter: dizzy stars, it ducks back down (treat moment) |
| `C` | Toggle calibration |
| `F` | Fullscreen |
| `H` | Hide the on-screen help |

Click or tap the critter to "catch" it (it freezes dizzy for a second, then bolts). In chase and roam modes, tapping elsewhere makes it run faster.

## Tips for the dog

- Projectors can't show black, so the area outside the critter stays dark. A dim room works best.
- Dogs see blues and yellows best, so the yellow glow dot and high-contrast critters read well.
- Keep sessions short, and let your dog "win" sometimes (`R`, then give a treat). Endless unwinnable chasing can frustrate dogs, which is the known downside of laser pointers.
- Keep the projector out of reach and don't let the dog stare into the lens.

## License

MIT
