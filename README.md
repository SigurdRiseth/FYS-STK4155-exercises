# FYS-STK4155 Exercises

This repository contains the solutions to the exercises and assignments provided in the course **FYS-STK4155 -- Applied Data Analysis and Machine Learning** at the University of Oslo (UiO). 

## Repository structure

The exercises are organized by week in the following way:

```
FYS-STK4155-exercises/
├── pyproject.toml
├── README.md
│
├── week34/
│   ├── README.md
│   ├── exercise01.ipynb
│   ├── exercise02.ipynb
│   └── src/
│       └── ...
│
├── week35/
│   ├── README.md
│   ├── exercise01.ipynb
│   └── src/
│       └── ...
│
├── week36/
│   └── ...
│
└── data/
    └── ...
```

Each `weekXX` directory contains the exercises and code for that week.

## Setup

This project uses `uv` for Python environment and dependency management.

Clone the repository:
```bash
git clone https://github.com/SigurdRiseth/FYS-STK4155-exercises.git
cd FYS-STK4155-exercises
```

Install the dependencies:
```bash
uv sync
```

