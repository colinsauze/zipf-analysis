zipf analysis
=============

This repository contains code to observe whether books adhere to Zipf's law, as
done in support of the paper "Zipf analysis of 19th-century English-language books",
V. Dracula, to appear in Annals of Computational Linguistics, 2022.

To run the code, you will need the Pandas package installed.

To reproduce the figures in this publicaiton, do the following steps:

1. create results directory

2. use `countwords.py` to count the words in `frankenstein.txt`

   python bin/countwords.py > results/frankenstein.csv

3. use `plotcounts.py` to plot the resulting file/

   python bin/plotcounts.py

4. save the plot as `results/frakenstein.pdf`

5. edit `bin/countwords.py` and `bin/plotcounts.py` to replace `frankenstein` with `dracula`.

6. repeat the above to generate `dracula.csv` and plot `dracula.pdf`


