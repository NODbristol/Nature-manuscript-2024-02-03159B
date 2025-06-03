# Nature-manuscript-2024-02-03159B

Code created and run on a standard computer running the operating system Windows 11 Enterprise, Version: 23H2.

The code as tested is run on VScode: 
Version: 1.98.2 (system setup)
Commit: ddc367ed5c8936efe395cffeec279b04ffd7db78
Date: 2025-03-12T13:32:45.399Z
Electron: 34.2.0
ElectronBuildId: 11161602
Chromium: 132.0.6834.196
Node.js: 20.18.2
V8: 13.2.152.36-electron.0
OS: Windows_NT x64 10.0.22631

The following extensions are installed:
Jupyter (ms-toolsai.jupyter), Version: 2025.3.0
Pylance (ms-python.vscode-pylance), Version: 2025.4.1
Jupyter Keymap (ms-toolsai.jupyter-keymap), Version: 1.1.2
Jupyter Cell Tags (ms-toolsai.vscode-jupyter-cell-tags), Version: 0.1.9
Jupyter Notebook Renderers (ms-toolsai.jupyter-renderers), Version: 1.1.0
Jupyter Slide Show (ms-toolsai.vscode-jupyter-slideshow), Version: 0.1.6
Python (ms-python.python), Version: 2025.2.0
Python Debugger (ms-python.debugpy), Version: 2025.4.1

The code uses packages:
Python version: 3.7.12 | packaged by conda-forge | (default, Oct 26 2021, 05:35:01) [MSC v.1916 64 bit (AMD64)]
NumPy version: 1.19.5
Matplotlib version: 3.5.3

No non-standard hardware is required, no special installation is required, except for NumPy and Matplotlib which take around a minute to install. 

The code can be copied into a Jupyter notebook and should work provided the above packages are installed. The input data is simulated in the code. The expected output is given in the SI Section 11, and gives the histogram, as show in the manuscript and SI (Figure 4c and Figure S49), and a line of text where the mean rotations of the population of simulated molecules in the specified time is given in degrees. The code takes around 20 seconds to run, which includes the importing of NumPy and Mapplotlib packages, on a standard system.

The cell with the code in on the Jupyter Notebook can be run to produce the desired output, due to the nature of probabilities extreme cases (+3780, -900) may appear/diappear from the x-axis which may affect the formatting of the histogram.



