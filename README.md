# Experiment results of "Exploring the use of Language Models to Enhance Datasets Explainability via Documentation"

## What is it in this repository?

This repository is anonymized to comply with the anonymization policies of the CKIM 2023 conference.

In this repository, you will find the results and the code to reproduce the experiments of the submission titled: "Exploring the Use of Language Models to Enhance Datasets Explainability via Documentation."

#### Checking the results 
To check out the results of the experiment, please, go to the **ExperimentResults.xlsx.**  in the **"/results"** folder.

You will find instructions and guides inside the file to help you follow and understand the results.

#### Reproducing the results 
To reproduce the results can execute the notebook **"dataset_extraction.ipynb"** to reproduce the results.

You must install Java and Python 3 in your system to execute this file.

Inside the notebook, you must point to one of the dataset files (in .txt) in the "/sources" folder. For instance: 
```documentPath = "sources/Nature-Scientific-Data/A whole-body FDG.txt" ```

And to set up an output file name.

Once all the notebook cells are executed, an output file with the results will be stored at the project's root.

To reproduce the steps done by the authors during the evaluation, you can paste the results to the file /results/Sample-results-sheet.xlsx in the sheet "Results-raw." Then, the results can be seen as the provided results in the same file "Results-formatted" sheet.
