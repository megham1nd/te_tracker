# te_tracker
Tropical cyclone tracking using NeuralGCM output data and TempestExtremes tracker

This repository contains scripts pertinent to tropical cyclone identification of NeuralGCM output data using vorticity parameters. To exactly replicate the tracking:

1) Extract variables of choice from NeuralGCM output using
   ```python ngcm_batch.py```
3) Run the TempestExtremes tracker using
   ```tracker_sbatch.sh```

Node detection files, trajectories, and plots will be located in the current year directory under
```dn_output```
```trajectories```
```plots```
respectively.
