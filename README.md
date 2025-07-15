# Anatomy of a Universe: A Self-Similar Geometry Simulation

## Abstract

This repository contains the Python script for a speculative cosmological model named "Anatomy of a Universe." The project's central thesis is that a complex, structured universe can emerge from a non-arbitrary axiomatic foundation. Instead of relying on free parameters or externally imposed laws, this model derives all its initial conditions, physical constants, and dynamical rules from a single, fundamental source: the mathematical constant Pi ($\pi$).

The final simulation presented here, **v37.3: Self-Similar Geometry**, is designed to test the hypothesis that the fabric of such a universe is inherently fractal. It employs a recursive construction algorithm to generate a universe that evolves across scales, rather than in time. The script then analyzes the resulting structure to demonstrate that the fractal dimension of the whole universe is nearly identical to that of its constituent parts, providing computational evidence for a scale-invariant, holographic geometric identity.

## 1. Philosophical Framework

The model is predicated on a set of core axioms developed over a series of thought experiments:

* **Law as Ontological Identity:** The most fundamental law of reality is not an equation of motion (describing *how* things behave), but an ontological identity (describing *what* things are). This is conceptually linked to mathematical identities like Euler's Identity ($e^{i\pi} + 1 = 0$), which unify fundamental constants in a single, timeless statement.
* **The Non-Arbitrary Principle:** To build a model of the "only possible universe," all forms of human arbitrariness must be eliminated. The mathematical constant Pi ($\pi$)—an infinite, non-repeating, and fundamental descriptor of cycles and geometry—is chosen as the sole, non-arbitrary source of all information and laws for the simulation. It serves as a digital analogue for a foundational, indivisible context (`Ω`).
* **The Universe as a Testable Consequence:** From this foundation, three key properties are hypothesized to emerge naturally:
    1.  **Cyclicality (`Bengi Dönüş`):** The universe undergoes super-deterministic, identical cycles of expansion and collapse.
    2.  **Holography (`Ortak Ruh`):** The information of the whole is encoded in every part, and vice-versa.
    3.  **Fractal Geometry (`Fraktal Doku`):** The texture of the universe is self-similar across all scales. This script is the computational proof-of-concept for this final property.

## 2. The Simulation Model: "Self-Similar Geometry"

To demonstrate the fractal nature of the universe, this simulation does not evolve in time but **evolves across scales**. It uses a "Recursive Construction" process to build the final universe texture.

### How It Works

The process can be broken down into a repeating, four-stage cycle:

1.  **SEED:** A small, low-resolution grid (e.g., 8x8) is initialized. Its state is not random but is directly derived from the initial digits of Pi, normalized to a continuous field of values.
2.  **EVOLVE:** This grid evolves for a fixed number of steps. The physics is governed by a **Pi-Based Reaction-Diffusion System**. This system's rules (diffusion rate, stability forces, chaos drivers) are not arbitrary numbers but are themselves derived from powers and ratios of $\pi$, ensuring the evolution is a direct consequence of the foundational constant.
3.  **GROW:** The evolved grid is upscaled to the next resolution (e.g., from 8x8 to 16x16) using smooth cubic interpolation. This ensures that the structure generated at the smaller scale is faithfully preserved and magnified.
4.  **DETAIL:** A new layer of information, derived from the *next available* digits of Pi, is added to the upscaled grid. The influence of this new detail is scaled down at larger resolutions. This mimics how natural fractals form, where large-scale structures are preserved while new, finer details emerge upon magnification.

This **Seed -> Evolve -> Grow -> Detail** cycle repeats recursively until the final target resolution is reached, resulting in a complex texture where every scale contains the imprint of the scales that came before it.

## 3. Key Features

* **Non-Arbitrary by Design:** All fundamental "physical" constants and initial conditions used within the simulation are derived from $\pi$.
* **Deterministic:** The simulation is fully deterministic. Given the same initial seed (Pi), it will produce the exact same final universe every time.
* **Fractal by Construction:** The recursive, multi-scale process is designed to naturally generate a self-similar, fractal texture.
* **Quantifiable & Falsifiable:** The script includes a standard scientific method, **Box-Counting**, to numerically calculate the fractal dimension of the generated structure, allowing for a quantitative test of the hypothesis.

## 4. Requirements

The script requires the following Python libraries:

* `numpy`
* `matplotlib`
* `mpmath`
* `scipy`
* `numba`

You can install them using pip:
```bash
pip install numpy matplotlib mpmath scipy numba

5. Usage

Simply run the Python script from your terminal:
Bash

python anatomy_of_a_universe_v37_3.py

The script will first generate the necessary digits of Pi, then run the construction simulation, and finally display the results in a Matplotlib window.

6. Expected Output

The script will produce a window showing two images side-by-side:

    Structure of the Whole: The image of the final, high-resolution universe grid.

    Structure of the Part: A zoomed-in image of the top-left quadrant of the whole.

Each image will be titled with its calculated fractal dimension (D_whole and D_part). The primary result of the simulation is the close agreement between these two values (D_whole ≈ D_part), providing strong computational evidence for the model's scale-invariant geometric identity.

This project is a conceptual exploration into the axiomatic foundations of physics. It aims to provoke thought and offer a coherent alternative to the problem of arbitrariness in our fundamental theories.

contact: husmanmert@gmail.com
