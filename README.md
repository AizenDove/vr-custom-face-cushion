# Custom-fit VR face gaskets

Scan your face with your phone, shape a VR face gasket around it in Blender, and 3D print it in soft TPU. The result is a cushion that follows your own face: less light leaking in, less pressure on the cheekbones and forehead, and a better fit if the stock one never sat right.

Everything here is free except the filament.

<!-- PHOTO: finished gasket on the headset, next to the stock one -->

## Credit

This guide builds on [How to Make a Custom DIY Facial Interface or Cushion for Any VR Headset](https://www.youtube.com/watch?v=hF4OpnH7aOA) by [Richard Virgosky](https://www.youtube.com/@RichardVirgosky). Watch it for the original idea. This repo adds my print settings, a two-part PLA + TPU design for parts that need to be stiff, and what I learned from the prints that failed.

## What you need

| | |
|---|---|
| **Phone** | Any phone that can run [Polycam](https://play.google.com/store/apps/details?id=ai.polycam) |
| **Software** | [Blender](https://www.blender.org/) and [Bambu Studio](https://bambulab.com/en/download/studio) (free) |
| **Printer** | A printer that handles TPU. I used a Bambu Lab printer |
| **Filament** | 95A TPU for the soft cushion, PLA for stiff parts |
| **Finishing** | Flush cutters, sandpaper (fine grit) |

## Steps

1. [Scan your face](steps/1-scan.md) with Polycam
2. [Shape the gasket in Blender](steps/2-blender.md) and export an STL
3. [Print it](steps/3-print.md) in TPU (and PLA where needed)
4. [Finish and test the fit](steps/4-finish.md)

## Print settings at a glance

| Setting | Value | Why |
|---|---|---|
| Material | 95A TPU | Soft and flexible against the skin |
| Walls | 1 | A thin shell squishes instead of pressing |
| Infill | 7% | Low infill keeps it soft |
| Orientation | 45°, face side up | Avoids long overhangs on the curve and gives a clean surface where it touches your face |
| Supports | On | Needed for the angled overhangs |

## Folders

- `steps/`: the step-by-step guide
- `files/`: models and Bambu Studio project files (coming)
- `gallery/`: photos of results (coming)

## Safety

The gasket sits on your skin, so:

- Sand every edge that touches your face smooth.
- Wipe it clean after use. TPU can be cleaned with mild soap and water or alcohol-free wipes.
- Stop using it if it irritates your skin.
- Make sure it doesn't push your eyes closer to the lenses than the stock gasket does.
