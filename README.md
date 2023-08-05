# mrp-higher-order-pairings

Major Research Project (MRP) repository for degree of Master of Science in the program of Data Science and Analytics at Toronto Metropolitan University.

## Overview

This repository contains the code and data used in my Master's Research Project (MRP) titled "CULINARY PUZZLE PIECES: HIGHER-ORDER INGREDIENT PAIRINGS IN WORLD
CUISINES".

This study applies data-driven techniques to explore the culinary structure of world cuisines, identifying correlations between shared and unique flavour compounds and frequent ingredient combinations. Analyzing food pairing and bridging, the research categorizes cuisines into four classes based on their flavour compound pairing and bridging characteristics. Frequent pattern mining is employed to identify common ingredient tuples across cuisines. It further utilizes decision tree classifiers to predict whether a cuisine's tendency towards flavour pairing or bridging can be inferred from its ingredient combinations. The findings can inform recipe creation, enhance culinary tradition understanding, and advance computational gastronomy by aiding AI recipe generators to generate palatable and tradition-respecting recipes.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Data](#data)
- [Notebooks](#notebooks)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)
- [Contact](#contact)

## Getting Started

To run the code and reproduce the results, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/JamesMarcogliese/mrp-higher-order-pairings.git
cd mrp-higher-order-pairings
```

2. Run the Juypter Notebooks in VSCode or your favourite editor with Juypter support.

## Data

Three data sources are used for this project:

1. CulinaryDB

    Bagler, Ganesh & Singh, Navjot. (2018). Data-Driven Investigations of Culinary Patterns
in Traditional Recipes Across the World. 157-162. 10.1109/ICDEW.2018.00033.

2. FlavourDB

    Neelansh Garg†, Apuroop Sethupathy†, Rudraksh Tuwani†, Rakhi NK†, Shubham
Dokania†, Arvind Iyer†, Ayushi Gupta†, Shubhra Agrawal†, Navjot Singh†, Shubham
Shukla†, Kriti Kathuria†, Rahul Badhwar, Rakesh Kanji, Anupam Jain, Avneet Kaur,
Rashmi Nagpal, and Ganesh Bagler*, FlavorDB: A database of flavour molecules,
Nucleic Acids Research, gkx957, (2017). †Equal contribution*Corresponding Author

3. Flavor Network

    Ahn Y.-Y., Ahnert, S.E., Bagrow, J.P. & Barbasi, A.-L. Flavor network and the principles
of food pairing. Sci. Rep. 1, 196; DOI:10.1038/srep00196 (2011)

The datasets used in this research project is available in their respective folder within this repository. More information about their locations, structure and format can be found in the results report.

## Notebooks

1. DB_Processing.ipynb

    Notebook containing all data preprocessing (cleaning, transformation, feature engineering).

2. HigherOrder_Analysis.ipynb

    Notebook containing all analysis and experiments, using the processed datasets output from the DB_Processing.ipynb noetbook.

Each notebook has detailed explanations and comments to guide you through the analysis and experiments. Many of the long running experiments have their data already pickled for faster execution. If wishing to re-run the notebooks from scratch, delete the contents of the 'exported_vectors' folder.

## Results

The main findings and results obtained from this research project are summarized in FinalReport_Marcogliese.pdf within this repository.

## Dependencies

Dependencies are installed by the notebooks themselves at the beginning of execution. Ensure a modern version of python is avaiable to the kernel (3.9+).

Note: It's recommended to create a virtual environment before installing the dependencies.

## License

MIT License

## Contact

If you have any questions, suggestions, or feedback related to this research project, feel free to contact me:

- Name: James Marcogliese
- Email: <james.marcogliese@gmail.com>
- LinkedIn: <https://www.linkedin.com/in/jamesmarcogliese/>