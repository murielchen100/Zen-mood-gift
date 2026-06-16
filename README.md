# 🎋 Zen Mood Gift

## Project Overview
The core driving force behind this project was a profound fascination with the concept of recursion—a mathematical elegance too captivating to overlook. 

While researching methods to generate procedural fractal patterns through code, I discovered ShaderToy and noticed how heavily it relies on sine and cosine mathematical waveforms to control light, shadow, and space. I observed a striking parallel between these trigonometric curves and human brainwaves. This realization led me to dive into scientific literature to understand the nuances of the four primary brainwaves—$\alpha$, $\beta$, $\gamma$, and $\theta$. From this research, I extracted three specific waveform combinations mathematically tailored to induce relaxation, enhance focus, and support emotional healing.

## Technical Implementation
By integrating these algorithmic brainwave parameters, I developed the web application *Zen Mood Gift*. Based on the user's responses to a series of mood-reflective questions, the system dynamically shifts the underlying waveform variables to generate a personalized, real-time therapeutic visual experience.

Specifically, the application translates three distinct mood-regulating wave groups—derived directly from EEG brainwave research—into precise mathematical formulas within a GLSL fragment shader. Operating entirely on the GPU, the shader uses these parameters to render fluid, real-time visual rhythms designed to theoretically resonate with and elevate the user's cognitive state.

## Current Limitations & Future Work
As a significant portion of the development cycle was dedicated to fine-tuning the mathematical parameters up until the final deadline, certain features remain on the roadmap. Specifically, I aim to implement code-driven generative audio and record a comprehensive video walkthrough explaining the parameter configurations. While the project is currently a work in progress, the long-term plan is to refine the interactive details and fully integrate the generative soundscapes.
