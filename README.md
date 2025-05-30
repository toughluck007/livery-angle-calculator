# Livery Angle Calculator

A simple web page for calculating rotation angles when designing car liveries for iRacing. Two tools are provided:

1. **180° Flip** – Given an original angle, this finds the angle to use when the graphic is mirrored on the opposite side of the car. The formula used is `(540 - angle) mod 360`.
2. **Mirror Angle** – Calculates the mirrored orientation across the car's centerline without adding a 180° rotation. The formula used is `(360 - angle) mod 360`.

Open `index.html` in a browser to use the calculators.
