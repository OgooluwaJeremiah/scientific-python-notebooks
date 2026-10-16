# Scientific Python Notebooks: Genetics and Biochemistry

Three short notebooks that apply NumPy, SciPy, pandas-style data handling and scikit-learn to problems from genomics and enzymology. Each notebook explains the concept, builds the calculation step by step, checks the result against a known answer, and ends with questions and limitations.

**All data in these notebooks is simulated** so that results can be checked against a known truth. None of it is real sequencing or laboratory data.

| Notebook | What it does | Main tools |
|---|---|---|
| `01_allele_frequency_hwe_fst.ipynb` | Estimates allele frequencies, tests Hardy-Weinberg equilibrium, and ranks loci by FST to recover deliberately differentiated loci | NumPy, SciPy, Matplotlib |
| `02_enzyme_kinetics_michaelis_menten.ipynb` | Fits Michaelis-Menten and competitive-inhibition models with confidence intervals, and compares nonlinear fitting with Lineweaver-Burk over 500 simulated experiments | NumPy, SciPy, Matplotlib |
| `03_pca_logistic_regression_genotypes.ipynb` | Implements PCA from scratch with SVD and verifies it against scikit-learn, then classifies groups with logistic regression and checks which loci the model finds | NumPy, scikit-learn, Matplotlib |

## Run it yourself

```bash
pip install numpy scipy matplotlib scikit-learn jupyter
jupyter notebook
```

Random seeds are fixed, so you should get the same numbers shown in the saved outputs.

## Author

Ogooluwa Zachariah, M.Sc. Bioinformatics (Genome Bioinformatics), B.Sc. Biochemistry and Molecular Biology.
