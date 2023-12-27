# Drowsiness Detector - Installation Guide

## Overview

This repository contains the source code for a drowsiness detector made without the help of deep learning.

## Prerequisites

- Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/).

## Installation Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/ahmedelahmmar/Drowsiness-Detector.git
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install Required Libraries:**

   ```bash
   pip install -r requirements.txt
   ```

   This command will install OpenCV, Joblib, NumPy, and Pygame as specified in the `requirements.txt` file.


## Updating Libraries

To update any of the installed libraries to their latest versions, you can use the following command:

```bash
pip install --upgrade library-name
```

Replace `library-name` with the name of the library you want to update (e.g., `opencv-python`, `joblib`, `numpy`, `pygame`).


## Running the Project

To run the project, Simply run the `src/main/main_Integration2.ipynb`