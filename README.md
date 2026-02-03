# Neural Activity and Thinking Process Simulation

This repository contains a simple Python simulation of neural activity and a basic thinking process in a model of 'higher intelligence'. It demonstrates how artificial neurons can process inputs to make decisions, mimicking aspects of nervous system activity and cognitive processes.

## Overview
- **Topic**: Nervous activity (neuron firing) and thinking process (signal propagation and decision-making) in higher intelligence.
- **Language**: Python (chosen for its popularity in AI/ML simulations, ease of use, and libraries like NumPy for numerical computations).
- **Why Python?** It's ideal for prototyping neural networks, has extensive scientific computing libraries, and is accessible for educational purposes. Alternatives like MATLAB or Julia could work for more advanced simulations, but Python is most suitable for GitHub sharing due to its community support.

## How It Works
1. **Neuron Class**: Represents a single neuron with weights, bias, and activation functions (sigmoid or ReLU).
2. **NeuralNetwork Class**: A simple feedforward network with one hidden layer.
3. **Simulation**: Takes sample inputs (e.g., sensory data), propagates through the network, and outputs a 'decision'.
4. **Visualization**: Plots firing rates of hidden neurons using Matplotlib.

## Requirements
- Python 3.x
- NumPy
- Matplotlib

Install dependencies:
## Running the Simulation
Run the script:
This will print the inputs, outputs, decision, and display a bar chart of neuron activations.

## Educational Notes
- This is a highly simplified model. Real nervous systems involve billions of neurons, synapses, and complex dynamics.
- For higher intelligence, concepts like recurrent networks (for memory) or deep learning could be explored in extensions.
- Extend this by adding training (e.g., backpropagation) to make the network learn from data.

## License
MIT License - Feel free to use, modify, and distribute.
