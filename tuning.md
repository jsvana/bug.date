# Vibroplex Bug Tuning & Descratching

Tips from the brass pounders: setting up a Vibroplex semi-automatic Morse key ("bug") from scratch, fixing scratchy dits, slowing down a bug, and maintenance/restoration. This is the Markdown version of [https://www.bug.date/tuning.html](https://www.bug.date/tuning.html), intended for AI agents and text-based clients.

## Setting up a bug from scratch

### Part 1: Pre-setup & physical maintenance

Before making any functional adjustments, ensure the mechanical integrity of the key.

1. **Tighten the base** — Ensure all screws on the underside of the base are snug to maintain electrical continuity.
2. **Clean bearing surfaces** — The arbor (pivot post) must be clean. Use alcohol and a toothpick or cotton swab to remove oxidation from the trunion screw cups.
3. **Polish the arbor tips** — Use fine sandpaper (1000 grit) to polish the cone-shaped points of the arbor for smooth movement.
4. **Adjust vertical play** — Set the top trunion screw so there is just a tad of up-and-down play — enough to prevent binding, but not so much that it feels sloppy.

### Part 2: Initial adjustments & spacing

This stage establishes the geometry of the key's movement.

1. **The damper** — Back off the right trunion screw until the pendulum rests gently against the damper — without pushing it or vibrating.
2. **Gap settings** — Using a feeler gauge, set the gap between the left trunion screw and the lever to approximately .011 to .015 inches.
3. **Dash contact** — Set the dash contact gap to a similar distance (~.015 inches) to ensure consistent spacing between dots and dashes.

### Part 3: Final functional setup

1. **Spring tension** — Start with springs at a medium (halfway) tension. They should be strong enough to return the lever quickly but light enough that the key doesn't walk across the table.
2. **Weight placement** — Place the sliding weights in the center of the pendulum for a balanced starting speed.
3. **Dot contact timing** — Move the dot contact in until the key produces roughly 12 to 15 solid dits before the vibration dies out or slurs into a continuous tone.

### Video walkthroughs

Bug Setup Series — Thomas Waits, WA9CW:

- [Nr 2 Pre-Setup Adjustment (YouTube)](https://www.youtube.com/watch?v=OiK4QwSBAZc) — Mechanical prep: tightening, cleaning, and polishing
- [Nr 3 Adjust and Set Up a Bug (YouTube)](https://www.youtube.com/watch?v=iH4uYoe34rA) — Spring tension, weight placement, and dot timing

Foundational reference — Jim, WB8SIW:

- [How to Properly Adjust and Use a Vibroplex Bug (YouTube)](https://youtu.be/qekmyx31Uxw) — The classic walkthrough on adjustment geometry and usage

## Fixing scratchy dits

### The "descratcher" debate

Capacitor-based "descratchers" are a common accessory sold to filter noise from bug contacts. Opinions vary on their effectiveness:

- **The case for:** [DL6ZB's oscilloscope measurements](https://www.dl6zb.de/MORSE_KEYER/vibroplex_debouncing.html) show that a 330nF capacitor across the bug connections visibly reduces dit bounce at ~20 WPM. He recommends 220nF at the bug plus 100nF in the keyer jack for additional RF filtering.
- **The case against:** Some operators report minimal audible difference, or find that proper adjustment and contact cleaning solve the problem without added components.
- **The radio factor:** Your radio may already have built-in filtering on the key input. Icoms and Kenwoods typically do; many Yaesus don't. If your radio already filters, an external descratcher may be redundant.

> "Same bug sounds lovely on an Icom or Kenwood and like hot trash on my Yaesu FT710." — AJ7CM

### What actually helps

Before buying a descratcher, try these proven techniques:

1. **Clean the contacts** — Match your cleaning to the bug's condition. New/clean bug? Paper between the dit contacts is usually enough. Older bug? DeoxIT on the contacts. Antique with heavy oxidation? Fine polish compound. Wiggle the contacts while testing — if you get solid dits with the post rotated off-center, they're still grimy.
2. **Adjust properly** — Don't set up your bug like iambic paddles with tiny travel. Bugs want some *slap* — put velocity into those dits. A properly adjusted bug has more travel than you might expect.
3. **The sponge trick** — Cut a small piece of kitchen sponge and wedge it inside the gap of the dit spring. This reduces wobble and makes contact more consistent. Multiple operators (WO6W, AJ7CM) swear by this simple fix.
4. **3D printed wedge** — Some ops use a 3D printed wedge instead of sponge for a more permanent solution. Placing it closer to the contact point seems to work best. See [K8CES's Thingiverse designs](https://www.thingiverse.com/ZeusK8CES/designs).

### Slowing down your bug

Need to send slower? Moving the weight only goes so far. Arm extensions add mass to the pendulum, letting you reach slower speeds without sacrificing control.

- [3D Printable Extension Arm](https://www.printables.com/model/1199720-extension-arm-to-slow-vibroplex-cw-bugs) — Free STL on Printables
- [Brass extension arm (eBay)](https://www.ebay.com/itm/186527271825) — Ready-made option
- [Another brass extension (eBay)](https://www.ebay.com/itm/187785533320) — Alternative seller

### Diagnostic tips

- **Record yourself on WebSDR:** What you hear locally (bug mechanics + sidetone) isn't what goes out on the air. Use a WebSDR to hear your actual transmitted signal.
- **Try noise-canceling headphones:** Helps you focus on sidetone rather than the mechanical clatter of the bug.
- **Test on different radios:** If possible, try your bug on another rig. Night-and-day differences between radios can reveal whether it's the bug or the radio's filtering.

### Radio filtering notes

Based on operator reports (anecdotal, not official specs):

- **Good filtering:** Icom, Kenwood (generally)
- **Less filtering:** Yaesu FT710, some others
- **Varies:** Xiegu G90 (reported better than FT710)

## Maintenance & restoration

### Ultrasonic cleaning

An ultrasonic cleaner is a game-changer for bug maintenance. It removes dirt and brightens/polishes parts without manual abrasion — no polishing compound needed. Especially handy given all the small screws and parts in a bug.

**Recommended setup:** A Vevor 6L ultrasonic cleaner works well. Mix up a gallon of ammoniated cleaning solution: ammonia, acetone, water, and Murphy's Oil Soap. Alternatively, **L&R** makes off-the-shelf water-based solutions specifically for clock cleaning that also work great.

### Replacement feet

Original rubber feet often deteriorate or go missing over the decades. [These rubber feet (eBay)](https://www.ebay.com/itm/222334042355) have been recommended by operators in the bug community.

### Parts lists

Official Vibroplex parts diagrams for current-production models:

- [Lightning Bug parts list (PDF)](http://www.vibroplex.com/techdocs/keys/PARTS-LBUG071519.pdf)
- [Champion parts list (PDF)](http://www.vibroplex.com/techdocs/keys/PARTS-Champion071519.pdf)

### Nickel plating / refinishing

For bugs with worn or tarnished nickel plating, DIY nickel plating is an option. KD7DUG has used [this nickel plating process (YouTube)](https://youtu.be/1Uy7QkLI8yU) to great effect.

**Watch the current!** After ~10 minutes, you may see blackening on the metal. Turn the current down to **0.1 amps** and voltage to **2.5V**. The blackening rubs right off. Buff with a Dremel after the bath for a clean finish.

## Related pages

- [Bug dating & model identification](https://www.bug.date/index.md) ([HTML](https://www.bug.date/))

## Credits

Tips compiled from the CW community. Thanks to WA9CW, WB8SIW, AJ7CM, KD7DUG, K8CES, WO6W, KG5VNQ, DL6ZB, and others. Site maintained by Jay, W6JY — jaysvana@gmail.com. 73!
