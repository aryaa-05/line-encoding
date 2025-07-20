
# Line Encoding Simulator

This is a simple, interactive web-based simulator for visualizing various line encoding schemes. It allows users to input a binary sequence and observe how different encoding methods represent that data electrically.

## Features

  * **Interactive Input**: Easily enter any binary sequence.
  * **Multiple Encoding Schemes**: Supports visualization of:
      * Unipolar NRZ
      * Unipolar RZ
      * Polar NRZ-Level
      * Polar NRZ-Invert (also known as NRZI)
      * Polar RZ
      * Bipolar (Pseudoternary)
      * Manchester
      * Differential Manchester
  * **Real-time Visualization**: See the encoded waveform drawn dynamically on a canvas.

## Line Encoding Concepts

Line encoding is the process of converting digital data into digital signals. This is crucial for transmitting data over a physical medium. Different encoding schemes have various advantages and disadvantages regarding:

  * **Bandwidth Efficiency**: How much data can be transmitted per unit of bandwidth.
  * **DC Component**: Presence of a direct current component can be problematic for some transmission media.
  * **Clock Recovery**: How easily the receiver can synchronize its clock with the incoming data stream.
  * **Error Detection**: Some schemes offer built-in error detection capabilities.

This simulator helps to visually understand how each of these common encoding schemes represents binary 0s and 1s.


