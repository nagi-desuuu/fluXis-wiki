# Stage

These decide how the non-playfield elements are rendered in game. These include:
`border-left.png` and `border-right.png`, which decide how the left and right side of the playfield look like.
`border-left-top` and `border-left-bottom` to change the appearance of the top and bottom of the left border.
`border-right-top` and `border-right-bottom` to change the appearance of the top and bottom of the right border.
`hitline.png` which shows where the hitwindow is for notes.

`background.png` is the image that will envelop the entire playfield, scaling itself so that it matches the width of the playfield and cropping out the excess height. You can also modify the top and bottom of this background with the images `background-top` and `background-bottom`.

## Reference

|        | Left                     | Center                  | Right                     |
| ------ | ------------------------ | ----------------------- | ------------------------- |
| Top    | `border-left-top.png`    | `background-top.png`    | `border-right-top.png`    |
| Center | `border-left.png`        | `background.png`        | `border-right.png`        |
| Bottom | `border-left-bottom.png` | `background-bottom.png` | `border-right-bottom.png` |
