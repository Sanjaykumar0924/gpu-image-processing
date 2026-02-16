# GPU Image Processing
# Description
This project demonstrates GPU-accelerated image processing using Python and OpenCV in a Kaggle Notebook. An image inversion filter was applied using both CPU and GPU to compare performance.

# Tools Used

Python

OpenCV

Numba CUDA

Kaggle Notebook (GPU Accelerator)

# GPU Usage

GPU was enabled in Kaggle Notebook settings under Accelerator → GPU.
The CUDA kernel processed image pixels in parallel, resulting in faster execution time compared to CPU.

# How to Run

Open the notebook in Kaggle

Turn Accelerator = GPU in right panel

Run all cells

Output image will be saved in /kaggle/working

# Output

CPU Time vs GPU Time comparison

Filtered output image
