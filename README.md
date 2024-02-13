# SI699 Tutorial: Bias Analysis Using Word Embeddings

This tutorial is designed to help walk you through a series of analyses of biases present in word embeddings, focusing on different dimensions such as occupation, ethnicity, gender, and other stereotypes. You will explore the Gensim and word2vec libraries, and perform analyses using precomputed vectors to see how similar words are with one another to measure how public perceptions of different groups have changed over time. 

This tutorial is based on the paper "Word embeddings quantify 100 years of gender and ethnic stereotypes," by Nikhil Garga, Londa Schiebingerb, Dan Jurafskyc, and James Zoue, but uses a different dataset that is pulled from Cornell University's movie dialog corpus. After completing the tutorial, you will have a basic understanding of how word embeddings and vectors work, along with how they can be used in a practical setting in the social sciences.

## How to Use:

1. **Installation**:
    - Ensure you have Python installed on your system.
    - Install the required libraries by running:
      ```
      pip install -r requirements.txt
      ```

2. **Clone Repository**:
    - Clone this repository to your local machine using Git:
      ```
      git clone https://github.com/emanmozaffar/si699-tutorial
      ```

3. **Open Notebook**:
    - Navigate to the cloned repository directory.
    - Open the `bias-analysis.ipynb` notebook using Jupyter Notebook or JupyterLab.

4. **Run the Notebook**:
    - Execute each cell in the notebook sequentially to perform the analyses.
    - Follow the instructions provided in the notebook for each analysis section.

## What to Expect:

- The notebook `bias-analysis.ipynb` contains several sections, each focusing on a different aspect of bias analysis using word embeddings.
- Each section includes code cells for data processing, bias calculation, visualization, and interpretation.
- Expect to see visualizations such as bar plots, heatmaps, and line plots representing bias trends over time or across different categories.
- Interpretation and insights are provided along with each visualization or analysis result.
- You can also take a look at `vector-creation.ipynb` for a step-by-step guide on how to create the vector models themselves. We have precomputed all of the vectors you need and uploaded them to the `models` subfolder, but this additional notebook is provided for your reference.
- `moviedata.csv.zip` is the cleaned data file containing all of the movie dialogue from the Cornell dataset, if you would like to follow along the `vector-creation.ipynb` tutorial.
