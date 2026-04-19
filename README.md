# NO3 Diffusion Code Package

This package contains the custom Jupyter notebook used to perform the 1D multi-component transient Nernst--Planck simulations and to extract intrinsic diffusion coefficients from the time-dependent ATR-SEIRAS data.

## Files

- `1D_Multi-component_Transient_Nernst-Planck_Model.ipynb`
  - Main analysis notebook for fitting diffusion coefficients.
- `requirements.txt`
  - Python package requirements used by the notebook.

## Notes

- The experimental input data file is not included in this public package.
- The bundled notebook was cleaned for sharing by removing duplicated development cells and excluding unvalidated electric-field and position-dependent diffusion-coefficient outputs.

## Environment

The notebook expects a Python 3 environment with the packages listed in `requirements.txt`.

## Usage

1. Install the required packages.
2. Open `1D_Multi-component_Transient_Nernst-Planck_Model.ipynb`.
3. Provide the required input dataset.
4. Run the notebook cells in order.
