# Control walkthrough

[Back to the case study](../README.md)

These examples are taken from the supplied controller reference. They document existing controls; they are not a new interactive control test.

## Place an asset

Register only the product's `Asset Library` subfolder in Blender preferences, then choose the library in the Asset Browser. Place the complete `CLK##_ASSET` or `SPM##_ASSET` collection. Preserve the object hierarchy, driver targets and constraints.

The collection origins are positioned at bottom center at the starting frame. For placement, transform the complete collection instance. To edit components, make the instance real and keep the animation dependencies intact.

## Example 1 · CLK08 clock movement

Select `CLK08_ASSET_CTRL` and open Object Properties → Custom Properties.

| Property | Recorded default | Meaning |
| --- | --- | --- |
| `Start_Hour` / `Start_Minute` / `Start_Second` | 9 / 15 / 30 | Initial clock pose. |
| `Time_Scale` | 1.0 | Clock playback speed multiplier. |
| `Second_Tick_Blend` | 0.0 | 0 gives a smooth sweep; 1 gives one-second stepping. |
| `Gear_Display_Speed` | 1.0 | Visible mechanism speed multiplier. |
| `Time_Offset_Frames` | 0.0 | Procedural phase offset in frames. |
| `Addon_Movement_Speed` | 1.0 | Speed multiplier for the additional tourbillon movement. |

The property name `Addon_Movement_Speed` is an existing controller label. Using this asset library does not require installing a Blender add-on.

## Example 2 · CLK23 meridian palace

The root exposes `Master_RPM` (recorded default 3.0), `Speed_Scale`, `Time_Scale` and `Phase_Deg`. `Master_RPM` is the signed input speed; connected gears follow that input. `Input_Angle` is a calculated output rather than the main user control.

## Example 3 · SPM11 Oculus iris gate

`Master_RPM` has a recorded default of 1.5. The control reference identifies `Input_Angle`, `Ring_Angle` and `Leaf_Angle` as driven values. Adjust the upstream input controls rather than overwriting those calculated outputs.

## Playback notes

The documented range is frames 1–1441 at 24 fps. Run switches retain each asset's enable/reset semantics; they do not provide a universal pause-at-current-position operation. Controls and cycles vary between assets. The supplied animations are visualization systems, and arbitrary parameter changes have not been certified collision-free.
