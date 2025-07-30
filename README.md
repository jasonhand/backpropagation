# Backpropagation Visualization 🧠

An interactive web-based visualization tool that demonstrates how neural networks learn through backpropagation. Watch in real-time as errors propagate backward through the network and weights get updated during the training process.

## What is this?

This project provides an educational visualization of a simple neural network that learns using the backpropagation algorithm. It's designed to help students and enthusiasts understand how neural networks adjust their weights based on prediction errors.

## Network Architecture

The visualization features a simple 3-layer neural network:
- **Input Layer**: 2 neurons (configurable input values)
- **Hidden Layer**: 2 neurons with sigmoid activation
- **Output Layer**: 1 neuron with sigmoid activation

## Features

### Interactive Controls
- **Learning Rate**: Adjustable slider (0.01 - 1.0) to control how fast the network learns
- **Input Values**: Two configurable inputs (0.0 - 1.0)
- **Target Value**: Set the desired output for training (0.0 - 1.0)
- **Step-by-Step Training**: Manual forward and backward pass execution
- **Auto Training**: Continuous training mode with real-time updates
- **Network Reset**: Reinitialize with random weights

### Visual Elements
- **Network Diagram**: Interactive SVG showing neurons and connections
- **Weight Visualization**: Connection thickness represents weight magnitude, color indicates positive (teal) or negative (red) weights
- **Real-time Updates**: Live display of neuron activations and weight values
- **Phase Indicators**: Shows current training phase (Forward Pass, Backward Pass, Ready)
- **Training Metrics**: Displays current epoch, error, and output values

### Educational Value
- **Step-by-step Learning**: Watch individual forward and backward passes
- **Weight Evolution**: See how weights change during training
- **Error Visualization**: Observe how prediction errors drive learning
- **Gradient Flow**: Understand how gradients propagate through layers

## How it Works

1. **Forward Pass**: Input values flow through the network, passing through weighted connections and activation functions to produce an output
2. **Error Calculation**: The difference between the predicted output and target value is computed
3. **Backward Pass**: The error is propagated backward through the network using the chain rule to calculate gradients
4. **Weight Updates**: Network weights are adjusted using the calculated gradients and learning rate

## Getting Started

Simply open `index.html` in any modern web browser. No installation or setup required!

## Usage

1. **Set Parameters**: Adjust input values, target output, and learning rate using the controls
2. **Single Step**: Click "Forward Pass" to perform one forward pass, then click again for the backward pass
3. **Auto Training**: Click "Auto Train" to watch the network learn continuously
4. **Experiment**: Try different learning rates and input combinations to see how they affect learning
5. **Reset**: Click "Reset Network" to start over with new random weights

## Educational Applications

Perfect for:
- Machine learning courses and workshops
- Self-study of neural network concepts
- Demonstrating backpropagation algorithms
- Understanding gradient descent optimization
- Visualizing the relationship between learning rate and convergence

## Technical Implementation

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **SVG Graphics**: Scalable vector graphics for network visualization
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Animations**: Smooth transitions and weight update animations
