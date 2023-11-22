# Trident-cross: Cross gantry for Voron Trident

## Gantry
Some delta from the Trident BOM for the gantry (not guaranteed to be complete):
|quantity|item|note|
|-|-|-|
| 4 | MGN9H 300mm ||
| 2 | MGN9C 350mm | C carriage - not H carriage|
| 2 | 5x400mm linear rod | Don't cheap out on this. I tried some random rods and it was too floppy. You only need 2, get something reasonably good [like this.](https://www.mcmaster.com/linear-rails/linear-motion-shafts-5/diameter~5-000-mm/diameter~5-mm/length~400-mm/) |
| 12 | 20t 2GT pulley | Yeah, it's a lot of pulleys. |
| 2 meters | Gates 2GT belt | You only really need 1.7 but a little more is nice for peace of mind. |
| 2 | Gates 188t 2GT belt loop | You can get one that's a little longer if you want to have more room to mount your motors. |
| 16 | 625 bearings | Yeah, it's a lot of bearings. |
| 8 | 5mm x 0.5mm shim | You want this to butt each outer belt pulley against each outer bearing. |
| a few | m5 | Some 10mm, some 8mm screws. BOM screws, you'll want to have a few extras. |
| a few | m3 | Some 6mm, some 8mm screws, maybe a couple 12's. BOM screws, you'll want to have a few extras. |

Electronics:
* 2x nema17 steppers

## Notable other changes to the Trident BoM
### Frame
The frame on the Trident is made for a core xy motion. To support a cross gantry, the top must be a full box.

Middle side extrusions are duplicated front and back.
* BOM: *2x HFSB5-2020-370-TPW*
* Cross: *4x*

Rear middle extrusion is replaced with a full length extrusion. Motors are mounted differently.
* BOM: *1x 2020-240*
* Cross: *0x*

For the vertical 4 extrusions, the middle blind drills need to be on 2 sides instead of 1 like the top corner drills. You're making a box on the top AND in the middle now.
* Cross: 4x HFSB5-2020-500-LCP-RCP-AP360
