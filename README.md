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

## Setup Instructions

- Download the MATLAB live script from the repository.
- Download the Optimization Toolbox from MATLAB. It is required to run some of the commands in the script.
- Open and run the live script in MATLAB. The results will appear after the script is done running.

## Expected Results

The script generates a 3D surface plot visualizing the energy output function E(,r) over the constrained domain θ ∈ [0°, 90°] and r ∈ [0.5, 4].

The program displays the numerical value for optimal tilt angle, optimal aspect ratio, and the maximum energy output. 

- Expected 3D plot:
<img src="https://github.com/jay-liang42/EPPMathworksSolarPanel5/blob/de60f5172b3d1f45f6634a300c4d5bc35872d372/expected_3D_plot.png"  width=500 />
- Expected optimal tilt angle: 37.5°
- Expected optimal aspect ratio: 1.0
- Expected Maximum Energy Output: 1965.9

