# Shake Slider

A flat-cartoon diner milkshake-sliding game. Hold to wind up, let go to slide the shake down the counter, and stop it in the green zone. Land 3 shakes per level. After each landing the shake is served and the counter shuffles into a new course (same counter, moved green zone and hazards).

Open `index.html` in a browser (phone or desktop). Everything is in that one file: graphics are drawn on a canvas and all sound and music are synthesized with WebAudio.

## Maps
Each map has 30 levels, 3 shakes each. Beat all 30 to unlock the next map. Levels are generated from a fixed seed (so they're the same every play) and each one is simulated to make sure it can be won. Every map mixes ramps, jumps, slick patches and sticky patches, plus its own extras:

1. **Main Street Diner** – syrup, ice, ramps, jumps, ketchup backstops, lifting pie domes
2. **Midnight Neon** – counter gaps and jump-over-the-gap combos
3. **Boardwalk Shack** – sand, wet boards and a pinching crab
4. **Orbit Café** – conveyor belts (some run backwards), timed lasers, oil and goo

Controls: press and hold (or hold Space), release to slide. Esc pauses.
