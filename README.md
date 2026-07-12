# Cancer Survival Prediction with Foundation Models and MIL

An educational deep-learning project for **SEAS 2026**. Students use precomputed **UNI2-h pathology embeddings** and gated attention multiple instance learning (ABMIL) to predict relative survival risk from whole-slide images.

## What you'll learn

- Survival time, events, censoring, and the concordance index
- How foundation models represent pathology image patches
- Why a patient can be modeled as a bag of instances in MIL
- Basic PyTorch training, validation, and attention visualization

## Notebooks

- `gated_abmil_instructions.ipynb` - guided, gap-filling student notebook
- `gated_abmil_solution.ipynb` - completed reference implementation

## Quick start

Open the instructions notebook in Kaggle, attach the required TCGA-BRCA feature dataset, configure optional Kaggle Secrets for Weights & Biases, and work through the `YOUR TURN` cells in order.

> For education and research only - not for clinical decision-making.
