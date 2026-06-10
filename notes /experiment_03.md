# Experiment 03 - CNN Mass Reconstruction

## Goal

Reconstruct dark matter mass maps from weak lensing observations.

## Dataset

- 1000 synthetic universes
- 64x64 maps
- gamma1 and gamma2 channels

## Model

5-layer CNN

## Results

Epoch 1 Loss: 0.6468
Epoch 25 Loss: 0.1808
Epoch 50 Loss: 0.1509

Correlation: 0.894

## Observations

The CNN successfully learned the inverse mapping between shear and mass.

## Limitations

- Simplified lensing physics
- Synthetic data only
- No realistic survey noise
- No uncertainty estimation

## Future Work

- U-Net reconstruction
- Realistic cosmology simulations
- Diffusion priors
