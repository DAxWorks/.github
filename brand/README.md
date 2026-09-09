# Brand assets

The DAxWorks wordmark, short mark and icons.

**Every SVG contains outlines, not text.** The letterforms are vector paths with
kerning already applied, so nothing depends on a font being installed and there
is no webfont licensing question. The consequence: the wordmark cannot be edited
as text. Regenerate it rather than trying to retype it.

---

## Files

| File | Use |
|---|---|
| `daxworks-wordmark.svg` | Primary wordmark, for light backgrounds |
| `daxworks-wordmark-reverse.svg` | Primary wordmark, for dark backgrounds |
| `daxworks-mark.svg` / `-reverse.svg` | Short mark `DAx`, where the full wordmark does not fit |
| `daxworks-icon-dark.svg` | App icon, ink plate |
| `daxworks-icon-light.svg` | App icon, light plate with a hairline edge |
| `daxworks-icon-purple.svg` | App icon, purple disc |
| `daxworks-favicon.svg` | Browser favicon source. A separate, tighter cut |
| `favicon-16/32/48.png` | Rendered at true pixel size, not downscaled from large art |
| `apple-touch-180.png`, `apple-touch-512.png` | Home screen and store sizes, from the light icon |
| `daxworks-lockup.svg` / `-reverse.svg` | Wordmark with the BUILD AUTOMATE SCALE tagline |

---

## Typeface

**Playfair Display**, weight 400, for the wordmark and every icon.

**The favicon is weight 600, deliberately.** At 16 pixels the 400 hairlines
disappear and the three letters merge. A favicon is its own optical size, not a
shrunk logo, and the heavier cut is the only one that survives a browser tab.
For the same reason the 180 and 512 sizes come from the light icon rather than
the favicon cut, whose proportions are too tight to be shown large.

Tagline lockups use **Inter** 500, letterspaced.

---

## Colours

| | Hex | Use |
|---|---|---|
| Purple | `#5B2BD6` | The accent. The `x`, rules, and primary actions |
| Ink | `#0F172A` | Wordmark on light, icon plate |
| White | `#FFFFFF` | Wordmark on dark, light icon plate |
| Hairline | `#E2E0DC` | The edge on the light icon, so it does not vanish on white |

**On the purple disc the `x` is white, not purple.** Purple on purple would
disappear. It is the one lockup that loses the accent, and that is deliberate.

---

## Use

- Give the wordmark clear space of at least the height of the `D` on every side.
- Never recolour the `x` to anything but the purple, or white on the purple disc.
- Never stretch, condense, outline, or add a shadow.
- Use the reverse artwork on dark backgrounds rather than placing a plate behind
  the standard one. Both reverse files are transparent.
- Below roughly 120px wide, use the short mark instead of the wordmark.

The organisation avatar has to be uploaded by hand in organisation settings; it
cannot be set through the API. Use `apple-touch-512.png`.
