# Disposable2µ43

Reusing disposable camera lenses on mirrorless SLR cameras with the µ43 mount.

Automatically generates the body given the caracteristics of your lens.

## How it works

This system is focus-free, there are no moving parts. The computations are made so that it focuses to hyperfocal distance.

For a lens of focal distance $f$ and aperture $F$, we can compute the hyperfocal distance $H$ :

$$
H = \frac{f^2}{0.033F}
$$

As we know that the focus distance of an object to distance $p$ of the lens is $q$, with 

$$
q = \frac{1}{f^{-1} - p^{-1}}
$$

We solve this equation with $p=H$.

## Files available

We provide files for a 31mm lens of aperture F/10 taken from a FujiQuickSnap camera. To adapt to your lens, just change the values in the spreadsheet in the FreeCad file.
