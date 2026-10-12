# Lesson 03 · Shading and form

## Pick one light source

Choose a light direction, usually top-left, and keep it for the whole sprite. Every shadow and highlight should agree with it. Inconsistent light is the most common beginner problem and the easiest to spot.

## Shading layers

A simple, readable shading setup uses four zones:

1. **Base:** the main color of the surface
2. **Core shadow:** the darker area facing away from the light
3. **Highlight:** the brightest area facing the light
4. **Reflected light:** a faint lighter edge in the shadow, from light bouncing back

Core shadow and reflected light give a shape its volume. Without them, objects look flat.

## Rim light

A thin bright edge on the side away from the light helps separate a character from the background. Use it sparingly.

## Clusters, not noise

Group pixels of the same value into shapes. Stray single pixels of a different color look like noise. Ask: does this pixel belong to a shape, or is it leftover dust? Clean up dust.

## Dithering

Dithering alternates two colors in a pattern, such as a checkerboard, to suggest a third color or a gradient. Use it on purpose:

- Good: a gradient across a large sky or a worn surface
- Bad: scattered everywhere, which makes the sprite look busy

If you can get the gradient with more ramp steps, do that instead.

## Anti-aliasing by hand

Pixel art usually avoids automatic smoothing. When a curve needs a softer edge, place an intermediate color by hand, on a single pixel where it matters. Don't blur the whole edge.

## Value first

Before you add color, check the values: squint, or switch your image to grayscale. Strong contrast between the main shapes gives the sprite its readability. Get the values right, then add hue.

## Key takeaways

- One light source, always.
- Use base, core shadow, highlight, and reflected light to show form.
- Clean up stray pixels. Use dithering on purpose.
- Check value first, color second.

## Try it

See Week 5 and Week 6 in [exercises/README.md](../exercises/README.md).
