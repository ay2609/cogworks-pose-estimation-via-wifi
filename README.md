# cogworks-pose-estimation-via-wifi

Pose/activity estimation from WiFi channel-state-information (antenna phase data), built for a BWSI/CogWorks capstone.

## What it is

A PyTorch project that trains a neural net (`Net` model, `CSIDataset`) on WiFi antenna
phase-difference data to estimate pose or activity — inferring body position/movement from radio
signals instead of a camera ("WiFi sensing"). Includes a full training loop with a `rich`-based
progress UI, checkpoint save/resume (`model.pth`), and Jupyter notebooks for experimentation.

## Stack

- Python, PyTorch
- rich (console UI)
- Jupyter

## Credits

Built during a Beginning Workshop in Science and Innovation (BWSI) / CogWorks summer program, in
collaboration with teammate Hunter Baker.

## Status

Training pipeline and checkpoints are in place; see the notebooks for example experiments.
