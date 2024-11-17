# diffusion2D

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description
This project simulates the diffusion equation in 2D domain using finite difference methods. The simulation demonstrates how heat diffuses in a square region with an initial high-temperature circle at the center. The resulting temperature distrubution is visualized using Matplotliib.

## Installing the package
You can install this package from TestPyPI using the following command:
```bash
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple <your_username>_diffusion2D
```

### Using pip3 to install from PyPI
Once your package is live on PyPI, you can install it using:
```bash
pip install <your_username>_diffusion2D
```

### Required dependencies
This package requires numpy and matplotlib libraries.
These dependencies are automatically installed when you install the package via pip.

## Running this package
After installation, you can use following command to run the simulation:
```bash
python3 -m diffusion2d
```
This will generate a 2D plot showing the diffusion process at different time steps.

## Citing
This project is based on materials from book [Learning Scientific Programming with Python](https://scipython.com/book/chapter-7-matplotlib/examples/two-dimensional-diffusion-equation/)
