# Lab 2: Matrix Multiplication - Tiling & Caches

## Part 1: Cache Basics

In the first part, we will go through the basic concepts about caches, such as direct mapped caches and set associative caches, using a simple matrix multiplication example. Answer Questions 1 ~ 7 in the notebook `1_cache_basics.ipynb`. 

## Part 2: Tiled Matrix Multiplication

The second part of this lab analyzes tiled matrix multiplication. We are using [Fibertree](https://github.com/Fibertree-Project/fibertree) to visualize each step in the matrix multiplication examples. You will then analyze how tiling changes memory access patterns. Answer Question 8 in the notebook `2_cache_tiling.ipynb`.

## Part 3: Optimize Matrix Multiplication & Caches

Finally, we will optimize matrix multiplication between large matrices to minimize the total area and energy consumed by caches. You can design your own caches and optimize matrix multiplication with tiling. Answer Question 9 in the notebook `3_cache_design.ipynb`. 

Furthermore, please answer conceptual Questions 10 and 11.

## Submission
After finishing the lab, please run `make submit` in the root directory (NOT in
the Docker container. Outside the workspace directory) of your repository to
submit your code. Check your submission on the GitHub website and ensure that
all notebooks have all cells run and all outputs visible. Additionally, ensure
that the `answers.yaml` file in the website matches the answers you have in your
notebooks. If either the notebooks or the `answers.yaml` file are not up to
date, you may lose points or receive a zero for the assignment.