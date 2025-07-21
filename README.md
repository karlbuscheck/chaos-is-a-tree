# Chaos Isn't a Ladder -- It's a Tree

## Project Overview

There's a famous line from *Game of Thrones* that claims: "Chaos is a ladder." But, in the context of machine learning, it's actually a *tree*, specifically a decision tree. In this notebook, we'll take a look at a popular `scikit-learn` dataset -- `load_wine` -- to explore how decision trees take chaos and transform it into clarity, one split and one branch at a time. And just for fun, at the end of the notebook, we'll see what happens when you take a single tree and scale up to an entire forest.

Here's the path we'll be following through the woods:

## Pipeline:
- Import, load and explore the dataset
- Build the decision tree, reduce the chaos
- Evaluate tree performance and check feature importance
- Forget the tree, use the forest

## Tools & Libraries Used

- **Jupyter Notebook** — the interactive environment used to explore, build, and document the entire modeling process  
- **Python 3.12.7** — base language powering data prep and all modeling   
- **scikit-learn** - for building, training, and visualizing decision trees and random forests
- **matplotlib** - for data visualization
- **numpy** - for data manipulation and analysis

## Acknowkedgements
The idea for this notebook came from a lecture delivered by Tao Li, Associate Professor in the Department of Information & Analytics at Santa Clara University's Leavey School of Business. Thanks to the professor for laying the groundwork for this project.
