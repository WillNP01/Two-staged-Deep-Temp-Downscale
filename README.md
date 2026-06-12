# Two-staged Deep Learning Temperature Downscaling

A two staged deep learning based downscaling framework for air temperature downscaling

During peer review, this repository contains selected reproducibility artifacts, including the checkpoints for several baseline models and the training/validation loss curves.

The full training and testing code will be released soon upon publication.

## Repository contents  
  
- `checkpoints/`: Trained model checkpoints for several baseline models used in the comparative evaluation under the one GCM case (MPI-ESM1-2-HR). More checkpoints under all cases will be released later.
- `training_logs/`: Training and validation loss curves.   

## Checkpoint selection  
  
For all deep learning baselines and the proposed model, the testing checkpoint was selected using the same criterion. Specifically, the checkpoint with the lowest validation RMSE averaged over daily maximum and minimum temperatures was selected for testing.

## Notes  
  
The released checkpoints are intended to support reproducibility of the reported model comparison and training-convergence analyses. Some input datasets used in the study are subject to their original data-provider licenses and are therefore not redistributed in this repository.

## Code release  
  
The full source code will be made publicly available upon publication.
