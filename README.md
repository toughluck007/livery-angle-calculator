# Livery Angle Calculator

A simple web page for calculating rotation angles when designing car liveries for iRacing. Two tools are provided:

1. **180° Flip** – Given an original angle, this finds the angle to use when the graphic is mirrored on the opposite side of the car. The formula used is `(540 - angle) mod 360`.
2. **90° Rotation** – Rotates the artwork 90° clockwise for starting angles from 0–180°, otherwise rotates 90° counterclockwise. The formula is `((angle < 180 ? angle + 90 : angle - 90) + 360) % 360`.

Open `index.html` in a browser to use the calculators.
