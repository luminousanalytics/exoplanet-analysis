
# Exoplanet Analysis with Lightkurve
This repository contains Jupyter notebooks and Python scripts for analyzing exoplanet data using the lightkurve library, exoplanet package, and other scientific libraries. The project focuses on detecting and modeling exoplanet transits using light curve data from missions like Kepler and TESS.

## Project Description
Exoplanet detection is a fascinating area of astronomical research that involves analyzing the light curves of distant stars to identify periodic dips in brightness caused by orbiting planets. This repository showcases a comprehensive workflow for exoplanet analysis, including data collection, preprocessing, transit detection, modeling, and visualization.

## Features
- Data Collection: Download and preprocess light curve data from NASA's Kepler and TESS missions using the lightkurve library.
- Transit Detection: Use Box Least Squares (BLS) periodogram analysis to detect potential exoplanet transits.
- Transit Modeling: Model the detected transits using the exoplanet package and pymc3 for Bayesian inference.
- Visualization: Generate interactive and static visualizations to explore light curves and transit models.
- Documentation: Detailed Jupyter notebooks with explanations of each step in the analysis process.

## Setup
To set up the environment, follow these steps:
```
git clone https://github.com/your-username/exoplanet-analysis.git
```
Navigate to the repository folder:
```
cd exoplanet-analysis
```
Create and activate a conda environment:
```
conda create -n myenv python=3.10
conda activate myenv
```
Install the required packages with their dependancies:
```
pip install lightkurve --upgrade
pip install -U "exoplanet[pymc]"
```
## Usage
Open the Jupyter notebooks in the notebooks directory to explore the analysis and results. Each notebook contains step-by-step instructions and explanations to guide you through the process of detecting and modeling exoplanet transits.

## Contents
- `notebooks/`: Jupyter notebooks for data analysis and visualization.
- `data/`: Directory for storing datasets.
- `scripts/`: Additional Python scripts used in the project.
- `README.md`: Project description and setup instructions.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

