# ML Overview

This repository contains an introductory overview of fundamental Machine Learning concepts.

## Contents

- `1-Numpy.ipynb`: A comprehensive Jupyter Notebook covering the basics of NumPy, including:
- `2-Pandas.ipynb`: (To be added) A Jupyter Notebook that will cover the basics of Pandas for data manipulation and analysis.
   

## Setup

To set up the environment and run the notebooks, please follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kemalozyon/MLOverView.git
   cd MLOverView
   ```

2. **Create a Conda environment (recommended):**

   ```bash
   conda create --name ml_overview --file requirements.txt
   conda activate ml_overview
   ```

3. **Install dependencies (if not using Conda):**
   If you prefer not to use Conda, you can install the dependencies using pip:

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   This will open a new tab in your web browser, from where you can navigate to and open `1-Numpy.ipynb`.

## Dependencies

The project relies on the following key libraries, as listed in `requirements.txt`:

- `numpy`: For numerical operations and array manipulation.
- `pandas`: (Implicitly used by many data science libraries built on NumPy) For data manipulation and analysis.
- `ipykernel`: For running Jupyter notebooks.

## License

This project is licensed under the MIT License.
