# Monte Carlo Option Pricer

- `pricer_numpy.py`: implements a simple serial monte carlo pricer
- `pricer_numba.py`: numba-ified version of `pricer_numpy.py`
- `pricer_cuda_vectorize_naive.py`: a naive implementation of the pricer using CUDA vectorize.
- `pricer_cuda_vectorize.py`: a optimized version of pricer_cuda_vectorize_naive.py
- `pricer_cuda.py`: a CUDA jit version of the pricer
- `pricer_cuda_overlap.py`: adds copy-compute overlapping to `pricer_cuda.py`

All `pricer_*.py` scripts are runnable.

    **Note**: `pricer_cuda_overlap.py` uses features in the upcoming 
              NumbaPro 0.11 release.
