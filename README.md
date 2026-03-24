# IAG TP1 - ArtBench-10 Generative Modeling

This repository contains the coursework for Project 1 (IAG), focused on generative modeling with ArtBench-10.

## Repository Structure

- `student_start_pack/`: main notebook, artifacts, and dataset helper files.
- `scripts/`: utility scripts for dataset loading and CSV generation.
- `.venv/`: local virtual environment (ignored by git).

## Main Notebook

Use:

- `student_start_pack/ArtBench10_Student_Start_Pack.ipynb`

The notebook includes:

- dataset loading (local Kaggle format or Hugging Face fallback),
- dataloaders and visualization helpers,
- modular implementations for VAE, DCGAN, and DDPM,
- shared FID/KID evaluation pipeline.

## Setup

1. Create and activate a Python virtual environment.
2. Install dependencies from `student_start_pack/requirements_lock.txt`.
3. Open and run the notebook from `student_start_pack/`.

## Notes

- Training and evaluation outputs are written under `student_start_pack/artifacts/`.
- Exported sample images are written under `student_start_pack/exported_data/`.