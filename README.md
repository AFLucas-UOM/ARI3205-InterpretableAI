# ARI3205 - InterpretableAI (Course Project)

This project focuses on **Interpretable Artificial Intelligence** by implementing and evaluating various interpretability techniques across different machine learning models and datasets. The aim is to build, evaluate, and interpret models in a methodologically robust manner.

## Summary 
The project is divided into four main parts:
1. **Feature-Level Interpretability**: Focused on the Boston Housing and Titanic datasets.
2. **Local Interpretability Techniques**: Applied to the Titanic dataset.
3. **Example-Based Explanations**: Explored using the Titanic dataset.
4. **Interpretable AI for Computer Vision**: Applied to the CIFAR-10 dataset using CNNs.

## Techniques Implemented

### Part 1: Feature-Level Interpretability
- Partial Dependence Plots (PDP) & Individual Conditional Expectation (ICE)
- Permutation Feature Importance (PFI)
- Accumulated Local Effects (ALE)
- Global Surrogate Models

### Part 2: Local Interpretability Techniques
- Local Interpretable Model-agnostic Explanations (LIME)
- Shapley Additive Explanations (SHAP)
- Anchors

### Part 3: Example-Based Explanations
- Counterfactual Explanations
- Prototypes and Criticisms

### Part 4: Interpretable AI for Computer Vision
- Integrated Gradients
- Grad-CAM

## Structure

The repository is organized as follows:

- **`Datasets/`**
  - **`Boston/`**: Contains the Boston Housing dataset.
  - **`Titanic/`**: Contains the Titanic dataset.

- **`Jupyter Notebooks/`**
  - **`Part1_BostonDataset.ipynb`**: Notebook for feature-level interpretability with the Boston dataset.
  - **`Part1_TitanicDataset.ipynb`**: Notebook for feature-level interpretability with the Titanic dataset.
  - **`Part4_CIFAR-10Dataset.ipynb`**: Notebook for computer vision interpretability with the CIFAR-10 dataset.

- **`Libraries/`**
  - **`Part1_Lib.json`**: JSON file with library dependencies for Part 1.
  - **`Part4_Lib.json`**: JSON file with library dependencies for Part 4.

- **`Models/`**
  - **`AFL_1T.h5`**: Trained model file for `Part 4 with 1 Epoch`.
  - **`AFL_15T.h5`**: Trained model file for `Part 4 with 15 Epochs`.

- **Root Files**
  - **`.gitignore`**: File for Git exclusions.
  - **`README.md`**: Project documentation.


## Clone the repository:
  ```bash
    git clone https://github.com/AFLucas-UOM/ARI3205-InterpretableAI.git
  ```

## Acknowledgments
This project was developed as part of the `ARI3205` course at the `University of Malta`.


## Contact
For any inquiries or feedback, please contact [Andrea Filiberto Lucas](mailto:andrea.f.lucas.22@um.edu.mt) & [Sean David Muscat](mailto:sean.muscat.22@um.edu.mt)
