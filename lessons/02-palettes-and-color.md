# Lesson 02 · Palettes and color

## Why limit colors

A small palette forces consistency. Most good pixel art uses 4 to 16 colors per sprite. Limits make art look like it belongs together, and they make the work faster to finish.

## Ramps

A **ramp** is a short row of colors in one hue, from dark to light. A common ramp has 3 to 5 steps.

```
shadow  ->  base  ->  light  ->  highlight
dark red   red      orange      pale yellow
```

Build one ramp per material or hue (skin, cloth, metal, leaves). Reuse the same ramps across a whole project.

## Hue shifting

Real light changes color as it gets darker or lighter. In pixel art, this is shown with **hue shifting**:

- **Shadows** drift toward cool hues such as blue or purple.
- **Highlights** drift toward warm hues such as yellow or orange.

Shifting the hue makes shading look richer than just making the color darker. Try it: take a red ramp and push the shadows toward purple.

## Saturation at the extremes

Very dark and very light colors can look dull if they are not saturated. Check your darkest shadows and brightest highlights. They often need more saturation than the midtones.

## Avoid pure black and white

Pure black (`#000000`) and pure white (`#FFFFFF`) are rarely the best choice. A dark navy or a cream is usually easier to live with. Use pure values only when the art needs them.

## Palette checklist

- [ ] Total colors are within your limit
- [ ] Each hue has a ramp with a clear light-to-dark order
- [ ] Shadows and highlights shift hue
- [ ] The palette works on both light and dark backgrounds
- [ ] You can name each color's job: base, shadow, highlight, outline

## Importing palettes

The files in [palettes/](../palettes/) use the GIMP `.gpl` format. In Aseprite, use **Palette > Load Palette**. In Libresprite and GIMP, the import dialog is under the palette menu. For more palettes, browse [Lospec](https://lospec.com/palette-list).

## Try it

See Week 3 and Week 4 in [exercises/README.md](../exercises/README.md).
