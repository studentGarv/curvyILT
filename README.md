# Curvy ILT

The source code of 

**Yang, Haoyu** and **Ren, Haoxing**.  
**"GPU-Accelerated Inverse Lithography Towards High Quality Curvy Mask Generation."**  
*Proceedings of the 2025 International Symposium on Physical Design*, pp. 42–50, 2025.

This repo is deprecated. Future maintenance will only happen in https://github.com/NVlabs/curvyILT


## Prepare

# Create virtual environment
python3 -m venv curvyILT_env

# Activate it
source curvyILT_env/bin/activate  # On Linux/macOS
# or on Windows:
curvyILT_env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Optional: If you need CUDA support (GPU), use:
# pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121

## Usage

This is a running example on ICCAD13 benchmark images.
Change the directory for your own design.

`curvyILT_env/bin/python run_iccad13.py`

## forked from :
[Haoyu Yang](mailto:haoyuy@nvidia.com)