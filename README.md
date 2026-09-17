# NUX B-6 flute mount

3D printed clamps that mount a **NUX B-6** or **B-6 Pro** wireless microphone onto a
flute.

The B-6 is sold for saxophone. It expects to clamp onto a bell: a rigid flared metal mouth
of one known size. A flute is a straight tube, and if you play one there is nothing on the
instrument for the mic to hold. These parts sit between the two.

The clamp is in two layers, which is the whole idea:

- a **rigid PETG split ring** that carries the standard B-6 clip and provides the clamping
  force, closed with printed screws and nuts
- a **flexible TPU spacer** that takes up the difference between the clamp bore and your
  actual tube, and grips without marking the instrument

Keeping those separate is what makes one clamp cover several flutes. A rigid clamp
tightened straight onto a bamboo flute would slip or dent it, and onto a thin aluminium
tube it would crush it. The TPU does the conforming so the PETG does not have to.

Built in a day for Nazm Anwr, who plays flute for the Bangladeshi band
[Kaaktaal](https://samiulmakes.com/projects/flute-mic-clamps/), because he performs with
thirteen flutes and swaps between them mid-set. Everything here, including the fasteners,
is printed: no hardware run, nothing metal to lose in a green room, and a thumb screw big
enough to turn by hand between songs.

Full write-up, with photos of the whole set:
**<https://samiulmakes.com/projects/flute-mic-clamps/>**

## Sizes

Five clamp bores, ten spacers. Pick the clamp that fits over your flute, then the spacer
that brings it down to your diameter.

| Clamp bore | Spacer inner diameters |
| --- | --- |
| 22 mm | 15, 16, 20 |
| 24 mm | 22, 22.5 |
| 28 mm | 24.5, 26.5 |
| 30 mm | 27.5 |
| 35 mm | 30, 33 |

Measure your flute with callipers at the point you want the mic to sit, which is usually
just below the embouchure hole and clear of the finger holes.

## If your flute is between sizes

You need a **new spacer, not a new clamp**. Take the clamp bore above your diameter, open
the CAD, change the spacer's inner diameter, print it. That is a one-parameter change and
a few minutes of printing.

Which is the reason the source file is here and not just the STLs.

## Printing

| Part | Material |
| --- | --- |
| Clamp shells | PETG |
| Screws and nuts | PETG |
| Spacers | TPU |

<!-- TODO (Samiul): layer height, walls, infill, TPU shore hardness, whether the screws
     need a particular orientation. Not filled in because guessing print settings for
     someone else's printer is worse than saying nothing. -->

## Files

- `cad/` — the parametric source. This is the useful one if your flute is not on the list.
- `stl/` — ready to print, at the sizes in the table above.

## Licence

<!-- TODO: pending Samiul's decision. -->

## Credits

Designed by [Samiul Hoque](https://samiulmakes.com) with Nazm Anwr.
NUX and B-6 are trademarks of their respective owner; this project is not affiliated with
or endorsed by NUX.
