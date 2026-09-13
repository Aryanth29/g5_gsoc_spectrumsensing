# M1 — Group 05
## Open-Set / "Unknown Signal" Aware AI Classifier for GNU Radio
Category: GSoC (Google Summer of Code) — AI Spectrum in GNU Radio

## About the project
Existing AI signal classifiers for GNU Radio are closed-set: they always
output one of their known modulation types, even for a signal they have
never seen. Our project aims to build a GNU Radio block that classifies
known modulation types but also flags a signal as "Unknown" when the model
is not confident, instead of forcing a guess.

## M1 contents
- `Report/` — the M1 PDF report (problem statement, review of existing work,
  SOTA position, and timeline).
- `Video/` — link to / file of the recorded walkthrough.
- `Code/` — notebook that imports and explores the RadioML dataset.
  See `Code/README.md`.
- `Data/` — dataset download instructions (datasets are not stored in the
  repo). See `Data/README.md`.
- `Results/` — output figures from the exploration notebook.

## Team
Kensi Patel (AU2440102), Maitri Lad (AU2440146), Rishika Bothra (AU2440179),
Nikkesh Parekh (AU2440214), Aryan Thakkar (AU2440248)
