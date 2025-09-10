# Den-Saty.dctl
For RCM Color Managment
This DCTL is a color and density enhancer that makes images look richer and more cinematic, while keeping everything natural and perceptually balanced.

It works by:

Boosting saturation in a perceptual way—midtones get more vibrant while very dark or very bright areas are gently protected.

Adding color density using an overlay based on luminance, giving the image more depth and “punch.”

Preserving skin tones and hues so faces stay natural and colors don’t shift unnaturally.

Fine control with sliders, including density strength, saturation boost, saturation bias, shadow/highlight thresholds, and hue preservation.

Workflow notes:

It is designed to work between two nodes in a DaVinci Resolve pipeline:

Node 1: CST from camera to DaVinci Wide Gamut / Intermediate (DWG/I).

Node 2: This DCTL.

Node 3: CST from DWG/I to your display color space (Rec.709, P3, etc.).

Or can be used with DaVinci YRGB Color Managed

In short, it enhances colors and contrast in a perceptually natural way, protects skin tones, and fits neatly in a scene-referred workflow between camera input and display output.
