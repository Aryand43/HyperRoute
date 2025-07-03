# HyperRoute

Latency-optimized signal routing simulator for cross-exchange financial infrastructure. Models network performance between NYSE, LSE, and SGX under realistic transmission conditions.

## Overview

Simulates 105 routing scenarios using:
- Microwave
- Fiber optics
- Intelligent Reflecting Surfaces (IRS)
- Movable Antennas (MA)

Benchmarks under stochastic propagation models to identify sub-70ms transmission paths suitable for high-frequency trading (HFT).

## Features

- Deterministic and stochastic latency modeling
- Comparative benchmarks: IRS+MA vs. baseline infrastructure
- Atmospheric and beamforming impact modeling
- Path analysis across NY-LDN-SG triangle

## Tech Stack

- Python 3.10+
- NumPy: vectorized latency computation
- Matplotlib: route and latency visualization
- Threading / Multiprocessing: parallel scenario simulation
- CSV / JSON: structured output logging

## Usage

```bash
git clone https://github.com/Aryand43/HyperRoute.git
cd HyperRoute
python simulate.py
