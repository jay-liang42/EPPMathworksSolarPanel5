# EPPMathworksSolarPanel5
## Project Description
This project will find the tilt angle and aspect ratio that maximize the energy output for a solar panel with a fixed area of 2 m².

The total energy output E(,r) is modeled as:
$$E(\theta, r) = A \cdot \eta(\theta) \cdot sunIntensity(\theta) \cdot f(r)$$

where
- **A = 2 m²** (fixed area)
- **θ** is the tilt angle (in degrees), θ ∈ [0°, 90°]
- **r** is the aspect ratio (length/width), with r ∈ [0.5, 4]
- **η(θ) = cos(θ − 30°)** (efficiency function based on tilt angle)
- **sunIntensity(θ) = 1000 · cos(θ − 45°)** (sunlight intensity variation based on tilt angle)
- **f(r) = exp(−0.1 · (r − 1)²)** (efficiency function based on aspect ratio)
