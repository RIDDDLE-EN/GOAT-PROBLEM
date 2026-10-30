# Mathematics of the 2D goat problem

**Setup.** Field: circle of radius `R` centered at `O = (0,0)`. Goat therered at `P = (R,0)` on the edge.
Rope circle: center `P`, radius `r`. They intersect at `X± = (R cos β, ± R sin β)`

## 1. The key relation: rope length ↔ arc angle

`|PX| = r` is a chord of the field circle subtending β at `O`, so

    r = 2R sin(β/2)         β = 2.arcsin(r / 2R)

Let `X = r/2R`. Everyting below is a function of `x` alone.

## 2. How the chord length grow

The half-chord *is* the y-coordinate of the intersection point on the fixed arc:
    
    c/2 = R sin β       c = 2R sin β

So if you parameterise by the **arc angle β**, the chord is exactly `2R sin β`.
The rope length `r` is *not* proportional to β, so against `r` the chord is

    c(r) = 2r·√(1 − r²/4R²)

which peaks at `r = √2·R` where `c = 2R` (the chord is a diameter, β = 90°).
View 3 in the animation plots exactly this test (measured c/2 vs `R sin β)

##
