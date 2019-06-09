# An Introduction to Machine Learning

Materials for a talk given on an introduction to Machine Learning and Boosted Decision Trees for the IceCube 2019 Bootcamp. Slides can be found at https://github.com/apizzuto/bootcamp-machine-learning/Bootcamp-Machine-Learning.slides.html

## Installation

The dependencies for generating the slides are:

- `numpy`
- `pandas`
- `jupyter`
- `scikit-learn`
- `matplotlib`

### Using `conda`

A `conda` environment with these dependencies installed can be created via:

```bash
conda env create --file environment.yml
source activate bootcamp-ml-2019
```

### Using `pip`

Inside a virtual environment, `pip` install the needed packages via:

```bash
pip install -r requirements.txt
```

## Usage

The slides for this talk can be generated via:

```bash
jupyter nbconvert Bootcamp-Machine-Learning.ipynb --to slides --post serve
```

To run the corresponding notebook use

```bash
jupyter notebook Bootcamp-Machine-Learning.ipynb
```
