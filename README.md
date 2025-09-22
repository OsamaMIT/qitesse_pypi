# qitesse
[![PyPI Version](https://img.shields.io/pypi/v/qitesse.svg)](https://pypi.org/project/qitesse/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/OsamaMIT/qitesse/blob/main/LICENSE)
[![Python Versions](https://img.shields.io/pypi/pyversions/qitesse.svg)](https://pypi.org/project/qitesse/)

Python API for qitesse-sim, the performant Rust quantum simulator.

qitesse is built upon qitesse-sim, the high-performance CPU-based state-vector simulator for quantum circuits, fully built in Rust.
This PyPI module provides a high-level python interface for the purpose of production, research, and development.

## Build & run locally:

1. Install Python deps (maturin):

`pip install maturin`


2. Build and install into current venv:

`maturin develop --release`


3. Run examples:

`python examples/h_example.py`
`python examples/qft_example.py`
