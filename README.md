# Data_Processing_Kristine

Data processing for qPCR.

## Features
* Load qPCR file by change the file name in the script.
* Simple and easy to use, change the variables in cell 2 and get the result ready for Prism.

## Requirements

* Jupyter Notebook
* Python 3.6+

For anyone not familiar with python and jupyter notebook, please download Anaconda here:
<html>https://www.anaconda.com/products/individual-d

## Usage
Simply change the variables in cell 2.

Set folder as where your qPCR result saved at;

Set file same as the qPCR result file, don't forget ".csv";

Set gene1-gene4 as how many rows are the gene loaded on qPCR plate, i.e. when gene1 have row "A to D", gene1 = 4;

If need si control, set si as Ture, otherwise false;

Input UR as the delta Ct value, like [gene1 UR, gene2 UR, gene3 UR];

Input hRPL19 Cq average value in cq_avg.


---
For any problem and new feature request, feel free to new a issue on Github or contact me at nz2343@columbia.edu
