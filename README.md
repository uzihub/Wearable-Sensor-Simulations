# Wearable Sensor Simulations & Frameworks

An open-source repository providing validated COMSOL Multiphysics simulation models and design frameworks for multi-layered stretchable sensors, alongside pre-formatted LaTeX documentation templates.

## Overview
While there is an abundance of open-source software, there is a critical gap in open-source hardware and simulation assets for microelectronics. This project aims to bridge the gap between theoretical microelectronics research and practical engineering. 

By sharing structural parameters and simulation data derived from academic research, this repository allows engineers and researchers developing next-generation wearable health monitors to bypass weeks of baseline testing and complex setup.

## Repository Structure
* `/models`: Contains the baseline COMSOL Multiphysics (`.mph`) files for multi-layered stretchable architectures, along with raw material parameter data.
* `/docs/latex_templates`: Comprehensive, pre-formatted LaTeX templates designed for academic publishing. These templates are optimized for seamlessly integrating complex sensor models, data tables, and figures into technical reports.

## Getting Started
1. **Simulations:** Open the files in the `/models` directory using COMSOL Multiphysics. Ensure you have the Structural Mechanics and AC/DC modules active.
2. **Documentation:** Compile the `main.tex` file in your preferred LaTeX editor (e.g., Overleaf, TeXStudio) to generate the baseline technical report format.

## Contributing
We welcome contributions from the hardware and microelectronics community. If you have optimized a mesh, improved a material model, or created a new LaTeX macro for data tables, please open a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
