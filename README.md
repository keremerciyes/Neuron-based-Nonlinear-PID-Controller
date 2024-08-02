# Neuron-based PID Controller

## Overview

This project demonstrates the outputs of the controller and system response for two different reference signals using a neuron-based PID controller. The details of the parameters, reference signals, structure of the neuron-based PID controller, and the algorithm followed are provided in the "Neuron based PID controller.pdf" file.

## Table of Contents

- [Introduction](#introduction)
- [Parameters](#parameters)
- [Reference Signals](#reference-signals)
- [Neuron-based PID Controller Structure](#neuron-based-pid-controller-structure)
- [Algorithm](#algorithm)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The neuron-based PID controller is designed to enhance the performance of traditional PID controllers by incorporating neuron-based learning algorithms. This project includes the implementation of the neuron-based PID controller and the analysis of its performance on two different reference signals.

## Parameters

The specific parameters used in the neuron-based PID controller are detailed in the "Neuron based PID controller.pdf" file. These parameters include the gains, learning rates, and other necessary configurations for the controller.

## Reference Signals

The project considers two different reference signals:
1. **First Reference Signal:** Details provided in the PDF.
2. **Second Reference Signal:** Details provided in the PDF.

## Neuron-based PID Controller Structure

The structure of the neuron-based PID controller includes:
- Input layer
- Neuron-based processing layer
- Output layer

The detailed structure and connections are outlined in the "Neuron based PID controller.pdf" file.

## Algorithm

The algorithm followed for the neuron-based PID controller is as follows:
1. Initialization of parameters.
2. Processing of input signals through the neuron-based layer.
3. Adjustment of control signals based on the neuron outputs.
4. Continuous learning and adaptation based on the error signal.

The full algorithmic steps and equations are provided in the PDF.

## Results

The results of the controller and system response for the two reference signals are provided in the respective `.mlx` files:
- **First Reference Signal Outputs:** `first ref signal outputs.mlx`
- **Second Reference Signal Outputs:** `second ref signal outputs.mlx`

These files include plots and data demonstrating the performance of the neuron-based PID controller.

## Installation

To run this project, you'll need MATLAB or an environment capable of running `.mlx` files.

## Usage

1. **Clone the repository:**

```bash
git clone https://github.com/keremerciyes/neuron-based-pid-controller.git
cd neuron-based-pid-controller
```

2. **Open the MATLAB Live Script files:**

Open first ref signal outputs.mlx and second ref signal outputs.mlx in MATLAB.

3. **Run the scripts:**

Execute the scripts to view the outputs and system response for the two reference signals.
