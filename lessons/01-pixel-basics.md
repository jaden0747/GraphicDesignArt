# Lesson 01 · Pixel basics

## The core idea

Pixel art is drawn one pixel at a time, with no smoothing or blurring. Every pixel is a deliberate choice. Good pixel art looks clean because the artist controlled every pixel, not because the image is small.

## Canvas size

Pick a canvas size before you start and keep it.

| Size | Typical use |
| --- | --- |
| 16×16 | Icons, tiny characters, item sprites |
| 32×32 | Classic characters and props |
| 64×64 | Detailed characters, larger props |

Small canvases force you to decide what matters. Start at 16×16 or 32×32.

## Pixel-perfect lines

A line is pixel-perfect when each step moves exactly one pixel in one direction. Avoid "double pixels" in the staircase, where two pixels in a row sit at the same step, unless the stair is intentional.

- Good: a diagonal that steps 1 across, 1 down
- Problem: a diagonal with a lone pixel that breaks the rhythm
- Test: zoom in and look for pixels that stick out of the pattern

## The squint test

Shrink your sprite or squint at it. Can you still tell what it is? If not, the silhouette is unclear. Fix the outer shape before you add detail.

## Outline styles

- **Black outline:** simple, high contrast, common for beginners
- **Colored outline:** outline uses a dark version of the fill color, which looks softer
- **No outline:** works for some styles, but harder to make read on busy backgrounds

Pick one style for a project and keep it. Mixing outline styles looks accidental.

## Practice rules

1. Work at 1× zoom as often as you can. Zoom in only to fix pixels.
2. Sketch the silhouette first in one color. Add detail after it reads.
3. Check your work at the size it will be used.

## Key takeaways

- Choose a canvas size and stick to it.
- Clean lines come from controlling each step.
- If the silhouette doesn't read, detail won't rescue it.

## Try it

See Week 1 and Week 2 in [exercises/README.md](../exercises/README.md).
