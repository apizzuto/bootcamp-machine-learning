# An Introduction to Machine Learning

Materials for a talk given on an introduction to Machine Learning and Boosted Decision Trees for the IceCube 2019 Bootcamp. Slides can be found at https://github.com/apizzuto/bootcamp-machine-learning/Bootcamp-Machine-Learning.slides.html

Much of the material that went into these slides came from James Bourbeau's previous talks on Machine Learning. Find him on [GitHub](https://github.com/jrbourbeau/).

## Installation

The dependencies for generating the slides are:

- `numpy`
- `pandas`
- `jupyter`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `graphviz`

### Using `conda`

A `conda` environment with these dependencies installed can be created via:

```bash
conda env create --file bootcampML.yml
source activate bootcampML
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
