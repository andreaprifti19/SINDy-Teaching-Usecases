# Data-Driven Discovery of Governing Equations with SINDy

Teaching use cases for the Sparse Identification of Nonlinear Dynamics (SINDy)
algorithm, developed as part of a B.Sc. thesis in Communication and Information
Engineering at Hochschule Rhein-Waal.

## Purpose

These notebooks demonstrate how governing equations of dynamical systems can be
recovered directly from measurement data using sparse regression. They are written
as guided lessons for readers with basic Python knowledge and no prior exposure to
equation discovery, and are intended both for self-study and as a basis for
course material.

Each notebook follows the same structure: explanation, implementation,
visualisation, and a short exercise.

## Notebooks

| Notebook | System | Focus | Run |
|---|---|---|---|
| `01_damped_oscillator.ipynb` | Damped harmonic oscillator | The full discovery workflow on a simple linear system | [![Open In Colab](https://colab.research.google.com/github/andreaprifti19/SINDy-Teaching-Usecases/blob/main/notebooks/01_damped_oscillator.ipynb) |
| `02_lorenz_system.ipynb` | Lorenz system | Discovery on a nonlinear, chaotic system | [![Open In Colab](https://colab.research.google.com/github/andreaprifti19/SINDy-Teaching-Usecases/blob/main/notebooks/02_lorenz_system.ipynb) |

## Running the notebooks

**In the browser (recommended):** click an Open in Colab badge above. No
installation required.

**Locally:**

```bash
git clone https://github.com/andreaprifti19/SINDy-Teaching-Usecases.git
cd SINDy-Teaching-Usecases
pip install -r requirements.txt
jupyter lab
```

## Repository structure
notebooks/ Guided use cases
figures/ Plots exported for the thesis
data/ Datasets used by the notebooks
NOTES.md Working log

## Environment

See `requirements.txt` for pinned package versions. Notebooks were developed and
tested on Python 3.11 in Google Colab.

## Author

Andrea Prifti — B.Sc. Communication and Information Engineering,
Hochschule Rhein-Waal. Supervisor: Prof. Dr. Frank Zimmer.

## License
