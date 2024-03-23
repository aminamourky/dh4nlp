# Evaluation of CodeLlama: BLEU Score and HumanEval

This repository contains the evaluation code for CodeLlama, a state-of-the-art model in the field of code generation. The evaluation is conducted using two different metrics: BLEU score and HumanEval. The evaluation code is implemented in two Jupyter Notebooks, one for each metric.

## Repository Structure

- `BLEU_Score_Evaluation.ipynb`: This notebook contains the evaluation code for CodeLlama using the BLEU score metric. The evaluation involves comparing the generated code from CodeLlama with reference code from the CoNaLa dataset and calculating the BLEU score as a measure of similarity.
- `HumanEval_Evaluation.ipynb`: This notebook contains the evaluation code for CodeLlama using the HumanEval benchmark. The HumanEval benchmark consists of hand-written programming problems, and the evaluation involves assessing CodeLlama's ability to generate code solutions that pass predefined unit tests.

## Prerequisites

To run the evaluation code in these notebooks, you need the following prerequisites:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (specified in the notebooks)

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/aminamourky/dl4nlp.git
   ```

2. Navigate to the cloned repository:

   ```bash
   cd dl4nlp
   ```

3. Open the Jupyter Notebook corresponding to the evaluation metric you want to use:

   - For BLEU score evaluation: Open `BLEU_Score_Evaluation.ipynb`.
   - For HumanEval evaluation: Open `HumanEval_Evaluation.ipynb`.

4. Follow the instructions within the notebook to execute the evaluation code.
