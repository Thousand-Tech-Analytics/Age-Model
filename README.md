# Age_Model

Personal portfolio experiments on age transformation using a pretrained GAN-based generator.  
This repository focuses on exploring latent manipulation and lightweight model optimization (e.g., pruning/quantization) to study age-related attribute changes in generated faces.

## What this project does
- Loads a pretrained generator and performs age-related latent edits
- Runs iterative experiments to compare different age offsets / edit strengths
- Includes optional optimization experiments (e.g., pruning, quantization, fine-tuning trials)
- Saves generated outputs for qualitative comparison

## Tech stack
- Python
- PyTorch
- (Optional) Google Colab / GPU runtime

## Repository contents
- `Agemodel_colab_code.py` — main experiment script (Colab-style workflow)

## How to run (minimal)
> Note: This code was originally executed in a Colab-like environment. Local execution may require minor path/runtime adjustments.

1. Create an environment and install dependencies:
   - `pip install torch torchvision numpy pillow matplotlib`
2. Run the script:
   - `python Agemodel_colab_code.py`

## Outputs
The script generates sample images for different settings (e.g., varying age offsets).  
Results are primarily qualitative and intended for rapid iteration.

## Notes
This is an experimental repository intended for portfolio development and iterative learning.  
It is not production-optimized and may be updated as experiments evolve.
