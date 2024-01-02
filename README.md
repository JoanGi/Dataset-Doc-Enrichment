# Experiment results and replication package of the paper "Using Large Language Models to Enrich the Documentation of Datasets for Machine Learning"

## What is it in this repository?

In this repository  readers will find:

1 - **results** folder: The full results of the experiment

2 - **code** folder: The code to reproduce the experiments of the submission titled: "Exploring the Use of Language Models to Enhance Datasets Explainability via Documentation."

3 - **data** folder: A dataset with 12 data papers annotated with the ground truth annotation of the researchers. The PDF and the extracted running text of the 12 data papers.

## Results: Checking the full results of the experiments 
To check out the results of the experiment, please, go to the **ExperimentResults.xlsx.**  in the **"/results"** folder. 

**Users should download the file to properly visualize the .xlsx content**

There are instructions in the file's main sheet to help readers understand the results.

## Code: Reproducing the results 
To reproduce the results users can execute the notebook **"dataset_extraction.ipynb"**

Users must install Java and Python 3 in their system to execute this file.

Note that users will need a OpenAI APIKEY to reproduce results using GPT3.5, and a HuggingFace APIKEY to reproduce the results using FLAN-UL2

Inside the notebook, users must point to one of the dataset files (in .txt) in the “data/sources” folder. For instance: 
```documentPath = "../data/sources/Nature-Scientific-Data/A whole-body FDG.txt" ```

And to set up an output file name.


Once all the notebook cells are executed, an output file with the results will be stored at the project's root.

To reproduce the steps done by the authors during the evaluation, users can paste the results to the file “**/results/Sample-results-sheet.xlsx**” in the sheet **Results-raw**. Then, the results can be seen as the provided results in the same file **Results-formatted** sheet.

## Data: The annotated dataset and the source of data papers

In this folder readers can find the generated dataset for this experiment and the PDF of the data papers used as a source along with the extracted running text.

Each row of the dataset is composed of the DOI of the data papers, the title, the dimension, subdimensions, the explanation of the subdimensions, and the ground truth annotated by the researchers. To annotate the datasets, at least two researchers have read the data paper and the definition of the subdimension. Then they have annotated a short explanation. Then the explanation have been compared and the disagreements have been corrected in reiterative meetings. The results shown in the column ground truth is the agreement between boths.

The dataset is presented in two formats, .csv and .xlsx with the exact same context.
