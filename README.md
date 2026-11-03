# Assessment Submission for Applied Statistics

This repository contains my submission for the module Applied Statistics.

The notebook focuses on the [Iris Dataset](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv).

## Contents
- `problems.ipynb`: the main notebook with four problems, explanations and results.
- `requirements.txt`: the Python packages needed to run the notebook.
- `AGENTS.md`: the agents file required by the assessment brief.
- `data/`: the dataset used by the notebook.
- `img/`: saved plots and figures.

## Requirements
- Python 3.13 (developed with 3.13.9)
- The packages listed in `requirements.txt`: [numpy](https://numpy.org), [pandas](https://pandas.pydata.org/), [matplotlib](https://matplotlib.org/), [scipy](https://scipy.org/) and [notebook](https://jupyter.org/)

## How to run
1. Clone the repository:

   ```
   git clone https://github.com/aiswarialajan124-png/appstat-assessment.git
   cd appstat-assessment
   ```
2. (Optional) Create and activate a virtual environment:

   ```
   python -m venv .venv
   source .venv/bin/activate
   ```

   On Windows, activate it with:

   ```
   .venv\Scripts\activate
   ```
3. Install the dependencies:`

   ```
   pip install -r requirements.txt
   ```
4. Open the notebook:

   ```
   jupyter notebook problems.ipynb
   ```

5. Run all cells from top to bottom (Kernel > Restart Kernel and Run all Cells).

## Problems covered
1. **Exploring petal length:** histograms with fitted normal distributions, overall and per species.
2. **Correlation:** Pearson correlation between petal length and petal width, overall and per species.
3. **t-tests:** pairwise independent-samples t-tests between species.
4. **ANOVA:** one-way ANOVA, and why it is preferable to multiple t-tests.

## About the Author

I am a student in Higher Diploma in Science in Computing in Data Analytics.