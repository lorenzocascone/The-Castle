# The Groaning Pile: Shadows of the Rafter-Lands

A 2D cinematic stealth-platformer that runs entirely in the browser — one file, zero
dependencies, zero external assets. Every visual is procedurally drawn on an HTML5
canvas in a monochrome ink-wash style; the only color permitted is the dull copper
glow of candle flames.

## Play

Open `index.html` in any modern browser. That's it.

You are **Pyre**, a runaway from the Choking Scullery. The Grand Hall lies between
you and the Library Door, and Arch-Liturge Silt is preaching to his blinded flock
below. Cross the rafters, stay out of the light, and track the blind stalker
**Grizzle** by the crosshatched shockwave of his knees.

## Controls

| Key | Action |
| --- | --- |
| `A` / `D` or `←` / `→` | Move |
| `W` / `↑` / `Space` | Leap (leap wall-to-wall to climb the chimney) |
| `S` / `↓` | Crouch — silent movement, invisible to Grizzle's hearing |
| `Shift` | Sprint (drains Fortitude, loud) |
| `E` | Interact — cut the banner rope, try the door |
| `Q` | Soot bomb — snuffs candles, blinds guards for 5 s |
| `F` | Grapnel — zip up to a rafter beam overhead |
| Crouch + Leap | Drop through a beam |

## Systems

- **Ink-wash stealth** — a dynamic radial-gradient lighting engine splits the world
  into light and crosshatched shadow. Standing in light fills the Awareness gauge;
  at 100% you are captured. Three hearts, then the Liturgy endures.
- **The Click-Snap Radar** — every 3 seconds Grizzle's knee joints emit a visual
  crosshatched sound-ripple that reveals his silhouette through the dark.
- **Environmental sabotage** — cut the great banner down onto Arch-Liturge Silt to
  blind every guard, then beat the 10-second escape window to the Library Door.
- **Kinetic traversal** — momentum platforming with sprinting, crouching,
  wall-jumps, one-way rafter beams, and a grapnel line, all governed by a
  Fortitude (stamina) meter.
