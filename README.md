# Soft-tactile-sensing-finger
We demonstrate the development of a recurrent neural network-based closed-loop force controller for a soft finger equipped with embedded soft sensors. This repository contains materials and code for a tutorial on developing machine learning (ML)-based controllers for soft robots with embedded sensors. The tutorial is designed to be accessible to individuals with little to no prior experience in robotics or robot control.

## Overview

Developing feedback controllers for robots with embedded sensors is traditionally a challenging task that requires expert knowledge. However, with the rise of ML, creating learning-based controllers has become more accessible. This tutorial introduces participants to ML-based sensing and control in cyber-physical systems using a soft robotic device.

In this tutorial, you will learn how to create a recurrent neural network (RNN)-based closed-loop force controller for a soft finger equipped with embedded soft sensors. The tutorial was validated in a 2.5-hour workshop with students who had no prior knowledge of robot control, demonstrating its accessibility and effectiveness.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Tutorial Structure](#tutorial-structure)
- [Getting Started](#getting-started)
- [Workshop Validation](#workshop-validation)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following:

- Basic understanding of Python programming.
- A computer with Python 3.x installed.
- Familiarity with basic ML concepts is helpful but not required.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/soft-finger-tutorial.git
    cd soft-finger-tutorial
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Tutorial Structure

The tutorial is divided into the following sections:

1. **Introduction to Soft Robotics**: Overview of soft robotic systems and their applications.
2. **Tactile Sensing with Soft Sensors**: Explanation of how embedded sensors work in soft robotic fingers.
3. **Introduction to Machine Learning**: Basics of ML and its application in robotics.
4. **Developing a Force Controller**: Step-by-step guide to creating an RNN-based closed-loop force controller.
5. **Testing and Validation**: Methods for evaluating the performance of your controller.

## Getting Started

To get started with the tutorial:

1. Follow the installation instructions above.
2. Open the Jupyter notebooks provided in the `notebooks` directory to begin the tutorial.
3. Work through each section, starting with the introduction to soft robotics.

## Workshop Validation

This tutorial was successfully validated in a 2.5-hour workshop with students who had no prior knowledge of robot control. The results demonstrated that even non-experts can create and implement ML-based controllers for soft robots using this tutorial.

## Acknowledgments

We would like to thank [Your Institution/Collaborators] for their support in developing this tutorial. Special thanks to the students who participated in the workshop and provided valuable feedback.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

