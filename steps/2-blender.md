# 2. Shape the gasket in Blender

Here you cut your face shape into a gasket model, so the cushion follows your face.

<!-- PHOTO / VIDEO: Blender with face scan and gasket -->

## Import

1. Open Blender and delete the default cube.
2. **File → Import** the face scan (OBJ / STL / glTF).
3. Import or model the gasket base: the part that attaches to your headset.

## Line them up

1. Scale the face scan to real size. Measure something known, for example the distance between your pupils, and scale until it matches.
2. Place the face where it sits when you wear the headset, with your eyes at the lens position.
3. Push the face slightly into the gasket so the cushion will touch everywhere. Start with a few millimetres and adjust after a test print.

## Cut your face shape in

1. Select the gasket and add a **Boolean** modifier.
2. Set it to **Difference** and pick the face scan as the object.
3. Apply the modifier, then hide or delete the face scan.
4. Check the result for holes or stray bits, and clean them up.

## Split into parts (if needed)

Some designs need a stiff part and a soft part:

- **PLA**: the part that clips onto the headset and has to hold its shape.
- **TPU**: the cushion that touches your face.

Cut the model into two objects where the stiff part ends and the soft part begins, and plan how they join (a press fit, a lip, or glue).

<!-- TODO: how I joined the PLA and TPU parts -->

## Export

1. Select the gasket (or each part on its own).
2. **File → Export → STL**, with "Selection only" ticked.
3. Export one STL per part.

Next: [Print it](3-print.md)
