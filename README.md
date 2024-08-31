# Memory Allocation Algorithms

This project demonstrates various memory allocation algorithms commonly used in operating systems, including First Fit, Next Fit, Best Fit, and Worst Fit. The project is built using HTML, CSS, and JavaScript to create an interactive interface where users can visualize and compare the different algorithms.

## Features

- **First Fit**: Allocates the first available memory block that is large enough to accommodate the process.
- **Next Fit**: Similar to First Fit, but it continues searching from the last allocated block rather than restarting from the beginning.
- **Best Fit**: Allocates the smallest available memory block that is large enough to accommodate the process, minimizing wasted space.
- **Worst Fit**: Allocates the largest available memory block, leaving the largest possible leftover block.



## Tech Stack

- **Frontend**: HTML, CSS, JavaScript

## How It Works

1. **User Input**: Users can input the sizes of memory blocks and the sizes of the processes they want to allocate.
2. **Algorithm Selection**: Users can choose one of the four memory allocation algorithms (First Fit, Next Fit, Best Fit, Worst Fit).
3. **Visualization**: The interface visually represents how the chosen algorithm allocates memory to the processes, showing which blocks are allocated and which are left unallocated.
4. **Comparison**: Users can run different algorithms on the same set of inputs to compare how efficiently each one uses the available memory.

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kaushalvala/Memory-Allocation-Algorithm.git
