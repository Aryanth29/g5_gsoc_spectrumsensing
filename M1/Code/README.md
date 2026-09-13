# Code / Technical Artefacts — M1 (Group 05)

## Status
For Milestone 1 our focus was defining and narrowing the problem statement
(an open-set / "unknown signal" aware AI classifier for GNU Radio) and
setting up the dataset we will build on. Accordingly, the technical work for
M1 is limited to importing and exploring the RadioML 2016.10A dataset. No
model has been trained at this stage.

## Contents
- `src/radioml_exploration.ipynb` — Loads the RadioML 2016.10A dataset and
  explores it: lists the modulation types and SNR levels, reports the sample
  shape and total sample count, and plots a few example I/Q waveforms and
  constellations. Figures are saved to `../Results/`.
- `requirements.txt` — Python libraries needed to run the notebook.

## Dataset
We use the RadioML 2016.10A dataset (O'Shea & West, 2016). It is large, so it
is not uploaded here. See `../Data/README.md` for download instructions.

## How to run
```
pip install -r requirements.txt
jupyter notebook src/radioml_exploration.ipynb
```
Place the downloaded dataset file in the `../Data/` folder first.
