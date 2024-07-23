# HierMinimax_ICPP
Code for Distributed Minimax Fair Optimization over Hierarchical Networks (ICPP 2024).

We present our implementation in Jupyter Notebooks. We strongly recommend you use Google Colab to run these Jupyter Notebooks. Otherwise, you can open and run our Jupyter Notebooks via [either Jupyter Notebook or JupyterLab](https://jupyter.org/install). You will also need to install all required packages by uncommenting the first code block in each of the files.


## This repo contains all code needed to replicate the results.
The code for the convex loss function setting is in `HierMinimax_ICPP2024_CVX.ipynb` and the code for the non-convex loss function setting is in `HierMinimax_ICPP2024_NONCVX.ipynb`.

Each Jupyter Notebook contains four code blocks: `Installation` (Please uncomment the `pip` comments if not using Google Colab), `Utilities` (all the utilizities methods and training implementation), `Training` (the code to run experiments and store results), `plotting` (the code to generate results the same as the paper)

After running all blocks, all results will be stored in the `results` folder and all figures for comparison of benchmarks will be plotted and stored in the `images` folder. 

