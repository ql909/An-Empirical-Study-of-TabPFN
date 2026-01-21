# An-Empirical-Study-of-TabPFN
Supplementary materials for the paper "Causal Pre-training Under the Fairness Lens: An Empirical Study of TabPFN" submitted to WWW'26 conference.

The specific labelling for Table 1 regarding to each dataset can be seen below:

**For the Bank Dataset:**
*   `DP₁` / `EO₁`: Fairness metrics with **"Education"** as the sensitive attribute.
*   `DP₂` / `EO₂`: Fairness metrics with **"Family"** as the sensitive attribute.

**For the Heart Dataset:**
*   `DP₁` / `EO₁`: Fairness metrics with **"Age Group"** as the sensitive attribute.
*   `DP₂` / `EO₂`: Fairness metrics with **"Sex"** as the sensitive attribute.

**For the Adult Dataset:**
*   `DP₁` / `EO₁`: Fairness metrics with **"Race"** as the sensitive attribute.
*   `DP₂` / `EO₂`: Fairness metrics with **"Sex"** as the sensitive attribute.

**For the Law Dataset:**
*   `DP₁` / `EO₁`: Fairness metrics with **"Race"** as the sensitive attribute.
*   `DP₂` / `EO₂`: Fairness metrics with **"Sex"** as the sensitive attribute.


## Folders

- Datasets/: Contains datasets used in the paper.
- RQ1/: Contains scripts and full results for RQ1. 
- RQ2/: Contains scripts and full results for RQ2.



## Prerequisite
The required package version

```
numpy==2.0.2
torch==2.8.0
pandas==2.2.2
sklearn==1.6.1
scipy==1.16.3
huggingface-hub==0.36.0
fairlearn==0.13.0
tabpfn==6.0.6
```

**Additional Setup for TabPFN-2.5**:
- After installing `tabpfn`, authenticate with Hugging Face CLI: `huggingface-cli login` to access the gated model at [https://huggingface.co/Prior-Labs/tabpfn_2_5](https://huggingface.co/Prior-Labs/tabpfn_2_5) (accept license for non-commercial use).

