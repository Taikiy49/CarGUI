<div align="center">
  <h1>CarGUI</h1>
  <p><strong>Python graphics exercises with a moving-car scene, interactive controls, and a click-to-score game.</strong></p>
  <p>
    <img alt="Python" src="https://img.shields.io/badge/Python-303840?style=flat-square" />
    <img alt="Graphics" src="https://img.shields.io/badge/Graphics-303840?style=flat-square" />
  </p>
  <p><a href="#overview">Overview</a> · <a href="#getting-started">Getting started</a> · <a href="#repository-map">Repository map</a></p>
</div>

---

## Overview

Two Python graphics exercises exploring geometric drawing, animation, mouse input, and stateful interaction.

## What’s inside

- Draw cars and trucks from basic geometric shapes.
- Switch scene settings with on-screen controls.
- Start, pause, and resume an animated car-clicking game with score tracking.

## Getting started

Install Python 3 and provide the course-compatible `graphics.py` module (the Zelle-style `GraphWin` API). Run either exercise:

```sh
python stationary_car.py
python animated_car.py
```

Both scripts expect `hw5_input.txt` in the working directory. The graphics module and input file are not included, so this checkout is not self-contained. The input supplies building coordinates and colors.

## Repository map

| Location | Purpose |
| --- | --- |
| [`stationary_car.py`](./stationary_car.py) | Vehicle drawing and scene controls |
| [`animated_car.py`](./animated_car.py) | Moving cars, scoring, and pause state |

## Project status

Educational project. Requires a graphical desktop and the original supporting files; these dependencies are intentionally called out rather than represented as bundled assets.
